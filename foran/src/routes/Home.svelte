<script lang="typescript">
    import HomeLayout from "../components/HomeLayout.svelte";
    import MasterProfile from "../components/MasterProfile.svelte";
    import MasterMainInfo from "../components/MasterMainInfo.svelte";
</script>

    <HomeLayout>
        <main class="main-sector">
            <div class="first-section">
                <div class="header">
                    <h2>Professores</h2>
                    <h5>40 professores encontrados em Informática</h5>
                </div>
                <div class="content">
                    <MasterMainInfo/>
                    <MasterMainInfo/>
                    <MasterMainInfo/>
                    <MasterMainInfo/>
                    <MasterMainInfo/>
                    <MasterMainInfo/>
                    <MasterMainInfo/>
                    <MasterMainInfo/>
                </div>
            </div>
            <div class="second-section">
                <MasterProfile/>
            </div>
        </main>
    </HomeLayout>

<style>     

    .main-sector{
        width: 100%;
        height: 93vh;
        display: flex;
    }

    .first-section{
        width: 65%;
        height: 100%;
        overflow-y: scroll;
        display: flex;
        flex-direction: column;
    }

    .header{
        width: 100%;
        height: 12%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        border-bottom: 1px solid white;
    }

    .header h2,h5{
        text-align: center;
        font-family: 'Roboto Slab';
    }

    .content{
        width: 100%;
        height: 85%;
        display: flex;
        flex-wrap: wrap;
        gap: 2em;
        padding-top: 1em;
        justify-content: center;
    }

    .second-section{
        width: 35%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        border-left: 1px solid black;
    }

    

</style>
