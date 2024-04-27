<script> 
    export let data;
    console.log(data);
    
</script>

<div class="den">
    <img src={data["img"]}>
    <p> {data["name"]}  {data["surname"]}</p>
    <p> {data["tags"][0]} </p>
    <p> {data["tags"][1]} </p>
    <p> {data["description"]} </p>
</div>

<style>
    .den {
        background-color: #44233B;
        width: min-content;
        border-radius: 20px;
    }
    img {
        height: 400px;
        weight: 400px;
        width: 350px;
        object-fit: cover;
        border-radius: 20px;
    }
    p {
        font-family: inter;
        color: white;
        font-size: 20px;
    }
</style>