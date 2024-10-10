<script>
    import Navbar from "../../modules/+navbar.svelte";
    import Page from "../socials/+page.svelte";
</script>

<style>
 body{
    scroll-behavior: smooth;
 }

</style>

<Navbar>

</Navbar>

<body>
    <div class="flow-root">
        <div class="flex my-6 py-12 px-16 justify-between items-center max-md:mt-2 max-md:p-4 max-lg:flex-col">
            <div class="flow-root max-lg:w-auto w-6/12">
                <h1 class="text-5xl max-md:text-3xl drop-shadow-md text-white font-extrabold">
                Hi!, i am <br>
                    Shawn Tyrone D. Rada <br>
                </h1>
                <p class="text-3xl mt-1 max-md:text-2xl drop-shadow-md text-white font-extrabold">A Student Developer.</p>
                <p class="text-xl max-md:text-lg mt-6 drop-shadow-md text-white font-bold">I am currently a Student from Gordon College under the College of Computer Studies
                    .</p>
    
                <div class="flex justify-end mt-6 w-full">
                    <a class="flex font-bold text-md max-md:text-sm text-white bg-slate-700 rounded-full max-md:w-auto w-3/12 justify-center items-center px-4 py-3 hover:bg-slate-900" href="socials">Reach out 
                        <svg class="w-6 h-6 text-gray-800 dark:text-white ml-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 12H5m14 0-4 4m4-4-4-4"/>
                        </svg>              
                    </a>
                </div>
                
            </div>
            
            <img class=" rounded-full max-md:mt-10 max-md:size-9/12 size-4/12 back" alt="shon" src="/shon.jpg">
    
        </div>
        
    
    </div>
</body>
