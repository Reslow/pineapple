<template>
  <div class="timelineContent">
   
    <div class="timeWall">
      <div class="timelineText" v-for="(item, index) in timelineData" v-bind:key="index">
        <div class="colorWall"></div>
        <div class="timelineTextOrder">
          <p class="timelineHeadline">{{ item.headline }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["timelineData"]
};
</script>

<style>
.title {

  margin-bottom: 30px;
  color: #1c2833;
 margin-left: auto;
  margin-right: auto;
  font-size: 24px;
}

.timelineTextOrder {
  display: flex;
  flex-direction: column;
}
.timelineText {

  padding-left: 0px;
  margin-bottom: 10px;
  display: flex;
  flex-direction: row;
  border-radius: 5px;
  height: 80%;
  background-image: linear-gradient(to right, #ccd8fa, #c3d2fc);
  
}
.timelineHeadline {
  margin: 5px;
  padding: 5px;
  color: #1c2833;
  font-size: 18px;
  font-variant-caps: initial;
  align-items: center;
  margin-top: auto;
  margin-bottom: auto;
  font-weight: normal;

}


.timelineContent {
  display: flex;
  flex-direction: column;
  margin-left:auto;
  
}

.timeWall {
  border-radius: 5px;
}

.colorWall {
  min-width: 2%;
  height: 100px;
  background-color: #351655;
  border-top-left-radius: 5px;
  border-bottom-left-radius: 5px;

}

@media (max-width: 860px) {
  .timelineText{
    margin-left: 0px;
  }
 
}
</style>