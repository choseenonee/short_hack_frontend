<script>
    import TopBar from '../../components/TopBar.svelte';
    import DenChik from '../../components/Mentor.svelte'

    const data = [
        {
            "name": "Дэнчик",
            "surname": "Зиновьев",
            "description": "Возьму на попечение первашонка)",
            "tags": ["NTO Winner", "ML-enjoyer"],
            "img": "https://sun9-56.userapi.com/impg/A9hjhHDaEecs5meDOEk5FnL1wHKTFQC3ZNSdkQ/f1ZskUqwzS8.jpg?size=972x2160&quality=95&sign=031dae7aa9fa7da6da72abef63221b6a&c_uniq_tag=9Vr-I0ctCCDlyRqknZZDpIZxrpV9YMLMUi8iLLD-QBc&type=album"
        },
        {
            "name": "Дэнчик",
            "surname": "Зиновьев",
            "description": "Возьму на попечение первашонка)",
            "tags": ["NTO Winner", "ML-enjoyer"],
            "img": "https://sun9-56.userapi.com/impg/A9hjhHDaEecs5meDOEk5FnL1wHKTFQC3ZNSdkQ/f1ZskUqwzS8.jpg?size=972x2160&quality=95&sign=031dae7aa9fa7da6da72abef63221b6a&c_uniq_tag=9Vr-I0ctCCDlyRqknZZDpIZxrpV9YMLMUi8iLLD-QBc&type=album",
        },
        {
            "name": "Дэнчик",
            "surname": "Зиновьев",
            "description": "Возьму на попечение первашонка)",
            "tags": ["NTO Winner", "ML-enjoyer"],
            "img": "https://sun9-56.userapi.com/impg/A9hjhHDaEecs5meDOEk5FnL1wHKTFQC3ZNSdkQ/f1ZskUqwzS8.jpg?size=972x2160&quality=95&sign=031dae7aa9fa7da6da72abef63221b6a&c_uniq_tag=9Vr-I0ctCCDlyRqknZZDpIZxrpV9YMLMUi8iLLD-QBc&type=album",
        }
    ]
</script>

<div> 
    <TopBar selected="mentors"/>

    <h1> Менторы </h1>
</div>

<div class="danki">
    {#each data as object}
    <DenChik data={object}/>

    {/each}
</div>

<style>
    .danki {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-around
    }
</style>