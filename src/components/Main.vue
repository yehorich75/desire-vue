<template>
    <main class="main">
        <div class="top">
            <div class="top__inner">
                <div class="top__slider">

                    <div class="top__slider-item">
                        <img src="../assets/images/slider/slider-colorful-gifts.jpg" alt="" class="top__slider-img">
                        <div class="top__slider-info">
                            <h2 class="top__slider-title">Чудові подарунки</h2>
                            <p class="top__slider-text">Deep v you probably haven't heard of them banh mi synth actually affogato.
                            Aesthetic lyft ethical drinking vinegar austint
                            </p>
                        </div>
                    </div>

                    <div class="top__slider-item">
                        <img src="../assets/images/slider/slider-detailed-elegance.jpg" alt="" class="top__slider-img">
                        <div class="top__slider-info">
                            <h2 class="top__slider-title">Детальна елегантність</h2>
                            <p class="top__slider-text">Deep v you probably haven't heard of them banh mi synth actually affogato.
                                Aesthetic lyft ethical drinking vinegar austint</p>
                        </div>
                    </div>

                    <div class="top__slider-item">
                        <img src="../assets/images/slider/slider-perfect-chandeliers.jpg" alt="" class="top__slider-img">
                        <div class="top__slider-info">
                            <h2 class="top__slider-title">Ідеальні люстри</h2>
                            <p class="top__slider-text">Deep v you probably haven't heard of them banh mi synth actually affogato.
                                Aesthetic lyft ethical drinking vinegar austint</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>    
    </main>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'Main',
        components: {
        
        }
    })
</script>

<style scoped>
/* Slider */

.top__inner {
    margin-bottom: 7rem;
    position: relative;  
}

.top__inner::after {
    content: '';
    background-image: url(../../images/slider-top-bg.jpg);
    width: 100%;
    height: 72.2rem;
    position: absolute;
    top: 0;
    z-index: -1;
}

.top__slider-item {
    display: flex !important;
    justify-content: center;
    align-items: center;
}

.top__slider-info {
    max-width: 64.5rem;
}

.top__slider-img {
    max-width: 70.3rem;
    object-fit: cover;
    margin-right: 2.5rem;
    margin-left: -1.5rem;
}

.top__slider-title {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    font-size: 11rem;
    line-height: 13.5rem;
    color: #363838;
    position: relative;
}

.top__slider-title::after {
    content: '';
    width: 18.5rem;
    background-color: #6d7278;
    height: 1px;
    display: block;
    margin: 2.6rem 0;
}

.top__slider-text {
    max-width: 58.5rem;
}

.slick-list {
    margin-bottom: 10rem;
}
</style>