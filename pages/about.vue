<script setup>
import { useDayjs } from '#dayjs';
const dayjs = useDayjs();
</script>


<template>
  <main>
    <div>
      <h2>
        About me:
      </h2>
      <div>
        <p>
          DJ 紫の時間 (Purple Time), an electrifying and dynamic force in the world of EDM, began their musical journey on {{ dayjs(new Date('2012-04-03' + 'T09:00:00.000Z')).format('dddd, DD MMMM YYYY') }}. That is like {{ dayjs(new Date('2012-04-03' + 'T09:00:00.000Z')).fromNow() }}. 
          <br>Known for their unique ability to blend diverse genres and create immersive soundscapes, 
          <br>DJ 紫の時間 (Purple Time) has captivated audiences worldwide with their innovative beats, infectious energy and personality.
          <br>
          <br>With a deep passion for music and a knack for reading the crowd, DJ 紫の時間 (Purple Time) rose to prominence in the vibrant VR club scenes. 
          <br>Their sets are a seamless fusion of Breakcore, Techno, Hard Trance, Dubstep, EDM and Memes, punctuated by surprising elements that keep the dance floor alive and buzzing.
          <br>
          <br>From intimate underground clubs to massive festival stages, DJ 紫の時間 (Purple Time) performances are a testament to their versatility and creativity. 
          <br>Their dedication to their craft and relentless pursuit of excellence have earned them a loyal fan base and critical acclaim in the music industry.
          <br>
          <br>Join DJ 紫の時間 (Purple Time) on this exhilarating musical adventure, and experience the magic that started on that fateful day in April 2012. 
          <br>Whether you're a longtime fan or a newcomer to their sound, DJ 紫の時間 (Purple Time) promises an unforgettable journey through the world of EDM.
        </p>
      </div>
    </div>
    <div><h2>I have made music for the following genres: </h2></div>
      <div>
        <p>click this link to see all <router-link :to="{ name: 'genres' }">genres</router-link> that I have played</p>
      </div>
  </main>
</template>