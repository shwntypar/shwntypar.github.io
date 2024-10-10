<script>
    import Navbar from "../../modules/+navbar.svelte";
</script>

<Navbar></Navbar>

<div class="flex flex-col rounded-2xl border-2 border-slate-400 max-md:my-10 my-20 max-md:mx-4 max-md:p-0 max-md:py-3 mx-12 p-8 text-center justify-start" >
    <h1 class="font-bold text-3xl text-slate-100 drop-shadow-md">MY PROJECTS</h1>

    <div class="flex max-lg:space-x-0 max-lg:flex-col max-lg:space-y-4 justify-center mt-4 p-4 space-x-8">
        <div class="p-6 bg-slate-400 w-[31%] max-lg:w-auto rounded-lg shadow-md flex flex-col justify-between items-center">
            <h1 class=" text-xl font-bold  text-slate-200 drop-shadow-md">
                PractiPro
            </h1>
            <p class=" text-slate-200 drop-shadow-md">
                An Web application project created by me and my classmates, This application provides an ease 
                of transaction between the OJT Applicants, OJT Advisers and the Companies regarding to OJT requirements.
            </p>
            <div class="flex w-full p-2 justify-end">
                <a class="flex flex-row font-semibold text-sm text-white bg-slate-700 rounded-full w-auto justify-center items-center px-2 py-1 hover:bg-slate-900" href="https://github.com/dummassdenzel/PractiPro">
                    Learn More
                    <svg class=" ml-2 w-4 h-4 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 12H5m14 0-4 4m4-4-4-4"/>
                      </svg>                          
                </a>
            </div>
        </div>
        <div class="p-8 bg-slate-400 w-[31%] max-lg:w-auto rounded-lg shadow-md flex flex-col justify-between items-center space-y-3">
            <h1 class=" text-xl font-bold  text-slate-200 drop-shadow-md">
                WeatherCast
            </h1>
            <p class=" text-slate-200 drop-shadow-md">
                 A simple weather forecast web application that uses REST API developed by me.
            </p>
            <div class="flex w-full p-2 justify-end">
                <a class="flex flex-row font-semibold text-sm text-white bg-slate-700 rounded-full w-auto justify-center items-center px-2 py-1 hover:bg-slate-900" href="https://github.com/shwntypar/WeatherCast">
                    Learn More
                    <svg class=" ml-2 w-4 h-4 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 12H5m14 0-4 4m4-4-4-4"/>
                      </svg>                          
                </a>
            </div>
        </div>
    </div>
</div>