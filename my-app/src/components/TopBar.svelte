<script>
    export let selected = "";
</script>

<div class="fon" id="topBar"> 
    <a class={selected=="mentors" ? "selected" : ""} id="mentors" href="/mentors">
        Менторы 
    </a>
</div>

<style>
    .selected {
        color: red;
    }
</style>