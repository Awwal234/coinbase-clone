<script>
    import Header from "../components/header.svelte";
    import "../app.css";

    const goTo = function(){
        window.location.href="/";
    }
</script>

<svelte:head>
    <meta charset="utf-8">
    <meta name="description" content="coinbase clone by Awwal Fabowale- open source">
    <link rel="icon" href="/img/title-logo.png">
    <title>Coinbase - coming soon page</title>
</svelte:head>

<body>
    <!--header-->
    <Header/>
    <!--end header-->
    <div class="mt-80 mx-auto text-center md:mt-64">
        <div class="text-3xl md:text-4xl mx-auto lg:text-5xl font-medium text-center text-blue-700">
            Coming soon
        </div>
        <div class="mt-8 w-fit h-fit bg-black text-center shadow-md shadow-gray-500 mx-auto text-gray-300 py-3 px-8 rounded-md 
        cursor-pointer font-bold font-sans hover:shadow-sm hover:shadow-gray-500 hover:bg-white hover:text-black
        hover:-translate-y-3 animate-bounce hover:animate-none hover:border" on:click={goTo}>
            Back to home page
        </div>
    </div>
</body>