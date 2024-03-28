<script>
    import owl1 from "$lib/images/owl1.jpg?enhanced";
    import owl2 from "$lib/images/owl2.jpg?enhanced";
    import owl3 from "$lib/images/owl3.jpg?enhanced";

    let owls = [owl1, owl2, owl3];
</script>


<enhanced:img src={owls[0]} alt="owl"/>
<enhanced:img src={owls[1]} alt="owl"/>
<enhanced:img src={owls[2]} alt="owl"/>

<style>
    img {
        width: 400px;
        height: auto;
    }
</style>