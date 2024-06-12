<script setup lang="ts">
import ButtonComponent from '../../components/ButtonComponent/ButtonComponent.vue'
import ListComponent from '../../components/ListComponent/ListComponent.vue'
import './Home.scss'
</script>

<template>
  <section class="contentPrimary">
    <div class="contentHome">
      <div class="titleContent">
        <img src="../../assets/img/Plumbers.svg" />
        <div class="textHome">
          <h2 class="text1">Round Rock</h2>
          <h4 class="text0">Plumbing</h4>
        </div>
      </div>
      <div>
        <p class="text3">What is Lorem Ipsum</p>
      </div>
      <div class="contentText2">
        <p class="text2">
          Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
          been the industry's standard dummy text ever since the 1500s, when an unknown printer took
          a galley of type and scrambled
        </p>
      </div>
      <div class="contentCards">
        <div class="cardContent"></div>
        <div class="cardContent"></div>
        <div class="cardContent"></div>
      </div>
      <div class="contentButtonPrimary">
        <ButtonComponent class="buttonContentPrimary"> Help Me </ButtonComponent>
      </div>
    </div>
  </section>
  <section class="contentSecondaryService">
    <div class="contentWhite">
      <div class="contentWork1">
        <p class="text1">what is Lorem Ipsum</p>
        <p class="textWork">
          Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
          been the industry's standard dummy text ever since the 1500s, when an unknown printer took
          a galley of type and scrambled it to make a type specimen book. It has survived not only
          five centuries
        </p>
        <ListComponent class="textCheck1"
          >Lorem Ipsum is simply dummy text of the printing</ListComponent
        >
        <ListComponent class="textCheck1"
          >Lorem Ipsum is simply dummy text of the printing</ListComponent
        >
        <ListComponent class="textCheck1"
          >Lorem Ipsum is simply dummy text of the printing</ListComponent
        >
      </div>
    </div>
    <div class="contentPhotoWork">
      <div class="contentWork">
        <img src="../../assets/img/person.png" />
      </div>
    </div>
  </section>
</template>
