<template>
    <div>
        <img :src="home.images[0]" style="width: 200px;"> <br/>
            <home-card :home="home"></home-card>
    </div>
</template>

<script>
export default{
    props:{
        home: {
            type: Object,
            required: true
        }
    }
}
</script>