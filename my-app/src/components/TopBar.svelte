<script>
    export let selected = "";
</script>

<div class="fon" id="topBar">
    <a class={selected=="mentors" ? "selected" : ""} id="mentors" href="/mentors">
        Главная
    </a>
    <a class={selected=="mentors" ? "selected" : ""} id="mentors" href="/mentors">
        Менторы 
    </a>
    <a class={selected=="mentors" ? "selected" : ""} id="mentors" href="/mentors">
        Форум
    </a>
    <a class={selected=="mentors" ? "selected" : ""} id="mentors" href="/mentors">
        Random<a class="pivo">Pivo<a/>
    </a>
</div>

<style>
    .topBar {
        font-size: 24px;
        height: 70px;
    }
    a {
        text-decoration: none;
        font-size: 24px;
    }
    .pivo {
        color: #D2A03D;
    }
    .selected {
        color: red;
    }
    .fon {
        display: flex;
        justify-content: flex-end;
        font-size: 50px;
        gap: 14px;
    }
    a:visited {
        color: white;
    }
    .selected:visited {
        color: red;
    }
</style>