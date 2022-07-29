<script>
    import Header from "../components/header.svelte";
    import "../app.css";
</script>


<svelte:head>
    <meta charset="utf-8">
    <meta name="description" content="coinbase clone by Awwal Fabowale- open source">
    <link rel="icon" href="/img/title-logo.png">
    <title>Coinbase - Buy, sell and track your crypto</title>
</svelte:head>

<style>
    tr, td{
        padding:15px;
    }
    #space{
        background-repeat:no-repeat;
        background-size:50% 100%;
        background-position:right, top;
    }

    @media (max-width: 640px) {
        tr, td{
            padding:10px;
        }
        #space{
            background-repeat:no-repeat;
            background-size:50% 100%;
            background-position:right, top;
        }
    }

    @media (max-width: 363px) {
        table{
            display:none;
        }
    }

    @media (min-width: 768px) {
        #space{
            background:url('/img/space.webp');
            background-repeat:no-repeat;
            background-size:50% 100%;
            background-position:right, top;
        }
    }
</style>

<body>
    <!--header-->
    <Header/>
    <!---->
    <section class="block mt-52 md:justify-between align-center md:flex">
        <div class="ml-10 md:w-2/5 md:ml-26 lg:ml-32">
            <div class="text-sm md:text-md text-blue-600 font-semibold font-sans">Jump start your portfolio &rightarrow;</div>
            <div class="text-4xl w-9/12 md:text-6xl md:w-80 font-semibold font-sans mt-4">
                Jump start your crypto portfolio
            </div>
            <div class="text-md w-10/12 md:text-xl font-semibold md:w-full mt-8">
                Coinbase is the easiest place to buy and sell cryptocurrency. Sign up and get started today.
            </div>
            <form name="form get started">
            <div class="block mt-10 w-11/12 md:w-fit md:flex space-x-0 md:space-x-3 relative align-center">
                <div class="w-3/5 md:w-fit">
                    <input type="email" class="p-2 w-full md:p-5 border-2 shadow-sm rounded-md md:w-fit shadow-gray placeholder:text-xl focus:outline-none" placeholder="Email address">
                </div>
                <button class="bg-blue-800 px-5 py-3 w-3/5 mt-2 md:w-fit md:px-10 text-white font-bold font-sans rounded-md align-center md:mt-0 hover:opacity-90">
                    <div>Get started</div>
                </button>
            </div>
            </form>
        </div>
        <!---->
        <div class="md:w-2/5 h-fit -mr-0 mx-auto">
            <img src="/img/g.png" class="mt-10 mx-auto md:-mt-12 w-64 overflow-hidden" alt=""/>
        </div>
    </section>
    <!--table-->
    <table class="w-4/5 md:w-4/5 border mx-auto h-fit mt-20 overflow-hidden">
        <tr class="text-md font-sans text-gray-500 font-semibold border-b">
            <td>#</td>
            <td>Name</td>
            <td>Price</td>
            <td>Change</td>
            <td>Chart</td>
            <td>Trade</td>
        </tr>
        <tr>
            <td>1</td>
        </tr>
    </table>
    <!---->
    <div class="mt-10"></div>
    <center>
    <div class="md:flex mx-auto md:w-4/5">
        <div class="md:w-2/5 w-4/5 md:text-left">
            <div class="text-3xl font-bold md:text-4xl">
                Earn up to $7 worth of crypto
            </div>
            <div class="text-md md:text-sm font-sans mt-4">
                Discover how specific cryptocurrencies 
                work — and get a bit of each crypto to try out for yourself.
            </div>
            <div>
                <button class="bg-blue-700 text-white mt-4 p-3 rounded-md font-bold hover:opacity-90">
                    Start earning
                </button>
            </div>
        </div>
        <!---->
        <div class="mt-3 md:w-3/5 w-4/5 lg:w-3/5 align-center md:mt-0">
            <div class="flex justify-between w-full p-5 border-2 align-center cursor-pointer md:border-0 lg:hover:shadow-xl lg:hover:shadow-gray lg:hover:rounded-md">
                <div class="inline-flex align-center">
                    <img src="/img/62365d11-b992-47f4-beed-588a457f71ed.png" class="w-10" alt=""/>
                    <div class="text-2xl md:text-3xl font-semibold ml-2">The Graph</div>
                    <div class="hidden text-xl md:text-xl font-semibold ml-2 md:inline-flex">GRT</div>
                </div>
                <!---->
                <div class="text-green-700 font-semibold lg:text-lg lg:font-bold">
                    Earn $4 GRT
                </div>
            </div>
            <!---->
            <div class="flex justify-between w-full p-5 border-2 align-center cursor-pointer md:border-0 lg:hover:shadow-xl lg:hover:shadow-gray lg:hover:rounded-md">
                <div class="inline-flex align-center">
                    <img src="/img/626691ce-b363-4e21-a0a5-f3e6579a85d3.png" class="w-10" alt=""/>
                    <div class="text-2xl md:text-3xl font-semibold ml-2">Amp</div>
                    <div class="hidden text-xl md:text-xl font-semibold ml-2 md:inline-flex">AMP</div>
                </div>
                <!---->
                <div class="text-green-700 font-semibold lg:text-lg lg:font-bold">
                    Earn $3 AMP
                </div>
            </div>
            <!---->
            <div class="text-left p-5 text-md text-blue-700 font-bold cursor-pointer">
                View more >
            </div>
        </div>
    </div>
    <!--next line after amp and grt-->
    <div class="mt-10 md:mt-20">
        <div class="w-10/12 md:w-3/5 text-4xl md:text-2xl lg:text-4xl font-sans font-bold">
            Create your cryptocurrency portfolio today
        </div>
        <div class="w-10/12 md:w-3/5 text-md text-gray-500 md:text-sm lg:text-lg font-sans font-normal mt-4">
            Coinbase has a variety of features that make it the best place to start trading
        </div>
        <!---->
        <div class="mt-10">
            <img src="/img/coinbase-app.webp" alt="" class=""/>
        </div>
    </div>
    </center>
    <!--why choose coinbase-->
    <div class="mt-20 border-t w-full p-10 md:p-10 lg:p-10">
        <center>
            <div class="w-full md:w-3/5 font-sans font-bold text-4xl md:text-2xl lg:text-4xl md:mt-3">
                The most trusted cryptocurrency platform
            </div>
            <div class="w-10/12 md:w-3/5 text-gray-500 text-md md:text-sm lg:text-lg font-sans font-semibold mt-4">
                Here are a few reasons why you should choose Coinbase
            </div>
            <!---->
            <div class="md:inline-flex mt-20 md:mt-36 w-10/12 md:w-full lg:w-10/12 md:space-x-8 flex-wrap">
                <div class="w-[80%] md:w-[30%]">
                    <div class="text-2xl md:text-2xl font-bold">
                        Secure storage
                    </div>
                    <div class="text-md md:text-md text-gray-500 font-semibold mt-3">
                        We store the vast majority of the digital assets in secure offline storage.
                    </div>
                </div>
                <!--choose 2-->
                <div class="w-[80%] md:w-[30%] mt-10 md:mt-0">
                    <div class="text-2xl md:text-2xl font-bold">
                        Protected by insurance
                    </div>
                    <div class="text-md md:text-md text-gray-500 font-semibold mt-3">
                        Coinbase maintains crypto insurance and all USD cash
                         balances are covered by FDIC insurance, up to a maximum of $250,000.
                    </div>
                </div>
                <!--choose 3-->
                <div class="w-[80%] md:w-[30%] mt-10 md:mt-0">
                    <div class="text-2xl md:text-2xl font-bold">
                        Industry best practices
                    </div>
                    <div class="text-md md:text-md text-gray-500 font-semibold mt-3">
                        Coinbase supports a variety of the most popular digital currencies.
                    </div>
                </div>
                <!--end choose-->
            </div>
        </center>
    </div>
    <!--end why choose-->
    <!--reading customer-->
    <div class="mt-0 bg-blue-700 w-full p-7 md:p-7 lg:p-7">
        <center>
            <div class="md:inline-flex w-10/12 md:w-full lg:w-10/12 md:space-x-8 flex-wrap">
                <div class="w-[80%] md:w-[30%]">
                    <div class="text-2xl md:text-6xl text-white font-bold">
                        $309B
                    </div>
                    <div class="text-md md:text-md text-gray-300 font-semibold mt-3">
                        Quarterly volume traded
                    </div>
                </div>
                <!--read 2-->
                <div class="w-[80%] md:w-[30%] mt-10 md:mt-0">
                    <div class="text-2xl md:text-6xl text-white font-bold">
                        100+
                    </div>
                    <div class="text-md md:text-md text-gray-300 font-semibold mt-3">
                        Countries supported
                    </div>
                </div>
                <!--read 3-->
                <div class="w-[80%] md:w-[30%] mt-10 md:mt-0">
                    <div class="text-2xl md:text-6xl text-white font-bold">
                        98M+
                    </div>
                    <div class="text-md md:text-md text-gray-300 font-semibold mt-3">
                        Verified users
                    </div>
                </div>
                <!--end read-->
            </div>
        </center>
    </div>
    <!--end read customer-->
    <div class="w-full h-fit md:h-[400px] p-10 md:p-20 mx-auto bg-blue-700 text-center md:text-left" id="space">
        <div class="text-center text-white md:w-2/5 w-[100%] md:text-left md:text-black">
            <div class="text-3xl font-bold md:text-4xl">
                Earn up to $7 worth of crypto
            </div>
            <div class="text-md md:text-sm font-sans mt-4">
                Discover how specific cryptocurrencies 
                work — and get a bit of each crypto to try out for yourself.
            </div>
            <div>
                <button class="bg-blue-600 text-white mt-4 p-3 rounded-md font-bold hover:opacity-90">
                    Start earning
                </button>
            </div>
        </div>
    </div>
    <!--g footer-->
</body>
