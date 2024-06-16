<script setup lang="ts">
import ButtonComponent from '../../components/ButtonComponent/ButtonComponent.vue'
import ListComponent from '../../components/ListComponent/ListComponent.vue'
import CardComponent from '@/components/cardComponent/CardComponent.vue'
import './Home.scss'
</script>

<template>
  <section class="contentRoundRock">
    <div class="contentHomeRoundRock">
      <div class="titleContentRoundRock">
        <img class="imagePlumbers" src="../../assets/img/Plumbers.svg" />
        <div class="contentTextHome">
          <h2 class="textRoundRock">Round Rock</h2>
          <h4 class="subtitleRoundRock">Plumbing</h4>
        </div>
      </div>
      <div>
        <p class="textTitleRoundRock">What is Lorem Ipsum</p>
      </div>
      <div class="contentParagraphRound">
        <p class="textParagraphRound">
          Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
          been the industry's standard dummy text ever since the 1500s, when an unknown printer took
          a galley of type and scrambled
        </p>
      </div>
      <div class="contentCardsServices">
        <div class="cardService">
          <img class="imageWrench" src="../../assets/img/wrench.svg" />
        </div>
        <div class="cardService">
          <img class="imageWrench" src="../../assets/img/wrench.svg" />
        </div>
        <div class="cardService">
          <img class="imageWrench" src="../../assets/img/wrench.svg" />
        </div>
      </div>
      <div class="contentButtonHelpMe">
        <ButtonComponent class="buttonHelpMe"> Help Me </ButtonComponent>
      </div>
    </div>
  </section>
  <section class="contentWorkService">
    <div class="contentCardWhiteWork">
      <div class="contentWork">
        <p class="textTitleRoundRock">what is Lorem Ipsum</p>
        <p class="textWork">
          Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
          been the industry's standard dummy text ever since the 1500s, when an unknown printer took
          a galley of type and scrambled it to make a type specimen book. It has survived not only
          five centuries
        </p>
        <ListComponent class="textCheck"
          >Lorem Ipsum is simply dummy text of the printing</ListComponent
        >
        <ListComponent class="textCheck"
          >Lorem Ipsum is simply dummy text of the printing</ListComponent
        >
        <ListComponent class="textCheck"
          >Lorem Ipsum is simply dummy text of the printing</ListComponent
        >
      </div>
    </div>
    <div class="contentPersonWork">
      <div class="contentPerson">
        <img class="imagePerson" src="../../assets/img/person.png" />
      </div>
    </div>
  </section>
  <section class="sectionService">
    <div class="contentService">
      <p class="serviceText">Services</p>
      <div class="contentCardsServicesWork">
        <div class="cardService1">
          <img class="imageWrench" src="../../assets/img/wrench.svg" />
        </div>
        <div class="cardService1">
          <img class="imageWrench" src="../../assets/img/wrench.svg" />
        </div>
        <div class="cardService1">
          <img class="imageWrench" src="../../assets/img/wrench.svg" />
        </div>
        <div class="cardService1">
          <img class="imageWrench" src="../../assets/img/wrench.svg" />
        </div>
      </div>
    </div>
    <div class="contentServiceText">
      <div class="cardTextService">
        <p class="titleService">Lorem Ipsum</p>
        <p class="subtitleService">
          Lorem Ipsum is simply dummy text of the printing and typesetting
        </p>
      </div>
      <div class="cardTextService">
        <p class="titleService">Lorem Ipsum</p>
        <p class="subtitleService">
          Lorem Ipsum is simply dummy text of the printing and typesetting
        </p>
      </div>
      <div class="cardTextService">
        <p class="titleService">Lorem Ipsum</p>
        <p class="subtitleService">
          Lorem Ipsum is simply dummy text of the printing and typesetting
        </p>
      </div>
      <div class="cardTextService">
        <p class="titleService">Lorem Ipsum</p>
        <p class="subtitleService">
          Lorem Ipsum is simply dummy text of the printing and typesetting
        </p>
      </div>
    </div>
    <ButtonComponent class="buttonHelpMe"> Help Me</ButtonComponent>
  </section>
  <section class="sectionTestymonials">
    <div class="contentCardsTestymonials">
      <CardComponent></CardComponent>
      <CardComponent></CardComponent>
      <CardComponent></CardComponent>
      <CardComponent></CardComponent>
    </div>
  </section>
</template>
