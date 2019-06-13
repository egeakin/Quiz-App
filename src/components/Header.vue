<template>
    <div>
        <b-nav tabs id=tabs>
            <b-nav-item disabled>Fancy Quiz App</b-nav-item>
            <b-nav-item disabled> Counter: {{numCorrect}}/{{numTotal}}</b-nav-item>
        </b-nav>
    </div>
</template>

<script>
export default {
    props: [
        'numCorrect',
        'numTotal'
    ]
}
</script>

<style>
    #tabs{
        background:rgb(250, 255, 182);
    }

</style>



