<script>
    import { ChevronDownOutline } from 'flowbite-svelte-icons';
    import { Button, Dropdown, DropdownItem, DropdownDivider, DropdownHeader } from 'flowbite-svelte';

    export let tabs = [
        { name: "About me", link: "/about" },
        { name: "Projects", link: "/projects" },
        { name: "Socials", link: "/socials" },
    ];

    let dropdown = false;
  </script>

<div class="w-full flex px-10 justify-between items-center bg-slate-900 h-20">
    
    <a href="/home">
        <span class="text-slate-200 font-semibold">Home</span>
    </a>

    <div class="max-md:p-0 max-md:space-x-0 space-x-4 p-4 text-slate-200 font-semibold">

        <div class="max-md:hidden">
            
            <a class=" rounded-full  hover:bg-slate-950 px-4 py-3" href="{tabs[0].link}">{tabs[0].name}</a>
            <a class="rounded-full  hover:bg-slate-950 px-4 py-3 " href="{tabs[1].link}">{tabs[1].name}</a>
            <a class="rounded-full  hover:bg-slate-950 px-4 py-3 " href="{tabs[2].link}">{tabs[2].name}</a>
        </div>

        <div class="md:hidden p-0"> 

            <button class="p-2 border-2 border-slate-800 rounded-xl " on:click={() => dropdown = !dropdown}>
                <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m8 7 4 4 4-4m-8 6 4 4 4-4"/>
                  </svg>
            </button>

            {#if dropdown}
            <div class=" text-center z-20 absolute right-2 mt-2 w-28 bg-slate-400 rounded shadow-lg transition-transform transform origin-top-right duration-200 ease-out scale-100">
                <ul>
                    <li class="py-1">
                        <a href="{tabs[0].link}">
                            {tabs[0].name}
                        </a>
                    </li>
                    <li class="py-1">
                        <a href="{tabs[1].link}">
                            {tabs[1].name}
                        </a>
                    </li>
                    <li class="py-1">
                        <a href="{tabs[2].link}">
                            {tabs[2].name}
                        </a>
                    </li>
                </ul>
            </div>
            {/if}
        </div>
    
    </div>
</div>