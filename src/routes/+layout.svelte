<script>
    import Header from "$lib/AppComponents/Header.svelte";
import Landing from "../lib/Reusable/Landing.svelte";
</script>

<svelte:head>
    <style>
        * {
            margin: 0px;
            font-family: sans-serif;
        }

        body::-webkit-scrollbar {
            width: 0.3em;
            background: none; 
            box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
        }

        body::-webkit-scrollbar-track {
            background-color: hsla(0, 0%, 0%, 100%);
            opacity: none;
        }
 
        body::-webkit-scrollbar-thumb {
            background-color: white;
            outline: 1px solid slategrey;
            border-radius: 15px;
        }
    </style>
</svelte:head>

<Header />
<Landing />

<slot></slot>