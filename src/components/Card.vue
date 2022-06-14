<template>
  <div class="cardContainer">
    <b-row class="h-100 p-2">
      <b-col cols="2" class="d-flex align-items-center justify-content-center"> 
      <img :src="img" style="width: 70px; height: 72px;border-radius: 12px;"/>
      </b-col>
      <b-col cols="8" class="d-flex align-items-center justify-content-start">
        <b-row>
          <b-col cols="12" class="pb-2 cardTitle">
            <span>{{name}}</span>
          </b-col>
          <b-col cols="12" class="pt-2">
            <span>{{description}}</span>
          </b-col>
        </b-row>
      </b-col>
      <b-col cols="2" class="d-flex align-items-center justify-content-end">
        <b-icon-chevron-right style="color: white; font-weight: bold; width: 28px; height: 17px;"></b-icon-chevron-right>
      </b-col>
    </b-row>
  </div>
</template>
<script>
import "../assets/Card.css";

export default {
  name: "CardComponent",
  props:{
    img: String,
    name: String,
    description: String
  }
};
</script>
<style>
</style>
