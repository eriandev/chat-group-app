<script lang="ts">
    export let app: string;
</script>

<main>
    <section>
        <h1 class="title">Chat Group {app}</h1>
    </section>
</main>

<style>
    main {
        color: white;
        min-height: 100vh;
        width: 100%;
        display: grid;
        place-items: center;
        background-color: #252329;
    }

    section {
        text-align: center;
    }

    h1 {
        font-size: 5rem;
        font-weight: 700;
    }
</style>
