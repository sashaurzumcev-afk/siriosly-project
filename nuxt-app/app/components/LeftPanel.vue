<template>
<div class="divi">
    <div class="lt_a"><span class="lt_pr">Programs</span></div>
    <div class="lt_a"><span class="lt_gm">Game</span></div>
    <div class="lt_a"><span class="lt_as">Achievements</span></div>
</div>
</template>

<style scoped>
.divi{
    height: 100vh;
    width: 10%;
    padding: 1% 0 1% 0;
    borde: 3px solid black;
    display: flex;
    flex-direction: column;
}
.lt_pr{
    borde: 1px solid blue;
    font-weight: 900;
    align-items: center;
    justify-content: center;
    display: flex;
    font-size: 30px;
    background-image: url('/images/d295f4b43b702872e16440c6180a749f.jfif');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: black;
    text-shadow:
    0 0 5px white,
    0 0 10px white,
    0 0 20px white,
    0 0 40px rgba(255, 255, 255, 0.8),
    0 0 80px rgba(255, 255, 255, 0.5);
}
.lt_gm{
    borde: 1px solid blue;
    font-weight: 900;
    align-items: center;
    justify-content: center;
    display: flex;
    font-size: 30px;
    background-image: url('/images/12985470-txayu373-v4.webp');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: black;
    text-shadow:
    0 0 5px white,
    0 0 10px white,
    0 0 20px white,
    0 0 40px rgba(255, 255, 255, 0.8),
    0 0 80px rgba(255, 255, 255, 0.5);
}

.lt_as{
     borde: 1px solid blue;
    font-weight: 900;
    align-items: center;
    justify-content: center;
    display: flex;
    font-size: 30px;
    background-image: url('/images/загруженное.jfif');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: black;
    text-shadow:
    0 0 5px white,
    0 0 10px white,
    0 0 20px white,
    0 0 40px rgba(255, 255, 255, 0.8),
    0 0 80px rgba(255, 255, 255, 0.5);

}
</style>

<script setup lang="ts">
import PsIcon from '~/assets/ps-icon.svg'
</script>