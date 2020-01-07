<template>
  <div class="timelineContent">
    <div class="title">
      <p>Design process</p>
    </div>
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
  margin-left: 50px;
  margin-bottom: 30px;
  color: #1c2833;

  font-size: 24px;
}

.timelineTextOrder {
  display: flex;
  flex-direction: column;
}
.timelineText {
  margin-left: 50px;
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

.timelineSubtitle {
  margin-top: 5px;
  margin-bottom: 5px;
  padding: 5px;
  color: #1c2833;
  font-size: 18px;
  font-weight: lighter;
}

.timelineContent {
  display: flex;
  flex-direction: column;
}

.timeWall {
  border-radius: 5px;
  width: 100%;
}

.colorWall {
  min-width: 2%;
  height: 100px;
  background-color: #351655;
  border-top-left-radius: 5px;
  border-bottom-left-radius: 5px;
  margin-right: 50px;
}

@media (max-width: 860px) {
  .timelineText{
    margin-left: 0px;
  }
 
}
</style>