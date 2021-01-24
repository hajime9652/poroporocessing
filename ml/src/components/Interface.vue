<template>
    <div>
        <Movie />
        <Wave />
        <Image />
        <Lang />
    </div>
</template>

<script>
import Movie from './components/Movie.vue'
import Wave from './components/Wave.vue'
import Image from './components/Image.vue'
import Lang from './components/Lang.vue'

export default {
    name: 'Interface',
    component: {
        Movie,
        Wave,
        Image,
        Lang,
    }
}
</script>