<script>
    import "../app.css";
</script>

<header class="w-full fixed z-50 bg-white item-center top-0 p-4 shadow-md shadow-gray justify-between">
    <div class="item-center flex ml-5 mr-5 md:ml-10 md:mr-10 justify-between">
        <img src="/img/Consumer_Wordmark.svg" class="w-28 items-center" alt=""/>
        <div>
            <ul class="hidden text-sm space-x-9 font-semibold p-2 font-sans items-center md:hidden lg:inline-flex md:text-md">
                <li><a href="/">Explore</a></li>
                <li><a href="/">Learn</a></li>
                <li><a href="/">Individuals</a></li>
                <li><a href="/">Businesses</a></li>
                <li><a href="/">Developers</a></li>
                <li><a href="/">Company</a></li>
            </ul>
        </div>
        <div class="text-sm font-sans space-x-4 font-semibold item-center md:flex">
            <div class="hidden md:flex"><a href="/" class="hover:text-blue-700 p-2">Sign in</a></div>
            <span class="p-2 hidden bg-blue-700 text-white rounded-md hover:bg-blue-800 md:flex">
                <a href="comingsoon" class="">Get started</a>
            </span>
        </div>
        <div class="flex md:hidden">
            <div class="bg-blue-600 text-white rounded-md p-2 hover:bg-blue-800">
                <a href="comingsoon">Get started</a>
            </div>
            <div class="text-xl cursor-pointer p-2">&#9776;</div>
        </div>
    </div>
</header>