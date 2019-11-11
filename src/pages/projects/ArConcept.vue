<template>
  <Layout>
    <div class="content">
      <div class="container1">
        <div id="title">
          <h2>AR learning & teaching tool</h2>
          <p class="subtext">A concept that could improve a learning environment.</p>
        </div>
      <div class="container2">
        <g-image src="~/assets/images/armodel.png" alt="icon" style="max-height: calc(100vh - 100px);" />
      </div>

        <div class="spalt">
          
             <p
            class="text">
          This application creates an access for teachers to add 3D-objects on top of the PowerPoint presentation, which can be shown during a presentation on a certain time. There is a bar with information such as time and settings. There is recording possibilities to replay information from lectures. To interact with the application the users will use gestures. As an example, the 3D object can be moved and rotated with help from gestures and on the timeline the users can with their finger play the lectures forward or back.</p>

         
          <p
            class="text"
          >This project was a group assignment with four other students. The assignment was to improve education with AR technology. We created two concepts. Above shows one concepts that was created together with students as one of our main users.</p>
         
          <p
            class="text"
          >We used two types of workshops for defining problem area and solution. The users from the study expressed that they wanted to change the situation with guest lectures, they wanted more guest lectures and they came with suggestions on how augmented reality could support this problem area. The application will improve teaching and learning experience for both students and teachers. We also think it will enhance the users learning experience and their interest of subject.</p>
        </div>
      </div>
    </div>
  </Layout>
</template>

<style scoped>
#title {

  color: rgba(13, 13, 13, 0.89);
  margin-bottom: 20px;
}
.spalt {
  display: flex;
  flex-direction: column;
  margin-bottom: 20px;
}
.text {
  margin: auto;
  padding-right: 10px;
  padding-bottom: 20px;
  max-width: 50%;
  font-size: 16px;
  font-style: normal;
  line-height: 28px;
}
h2 {
  margin: 0px;
  padding: 5px;
  text-align:center;
}

h3 {
  padding-left: 15px;
  margin-top: 0px;
  font-size: 18px;
  
}
.subtext{
text-align: center;
}
p {
  
  margin: 0px;
    padding-top: 15px;
  font-size: 18px;
   align-content: center;
   justify-content: left;
}

.container1 {
  
  color: rgba(13, 13, 13, 0.856);
  padding-top: 30px;
  padding-bottom: 30px;
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 30px;
  font-size: 18px;
  
  max-height: calc(100vh - 100px);

  display: flex;
  flex-direction: column;
  align-content: center;
  max-width: 100%;
}
.container2 {
  
  display: flex;
  flex-direction: column;
  align-items: center;
}

.content {
   
  display: flex;
  flex-direction: column;
  margin-left:auto;
  margin-right: auto;
}
.textCon {
  display: flex;
  margin: auto;
  max-width: 50%;
}


@media (max-width: 860px) {
  .container2 {
    display: flex;
    flex-direction: column;
    box-shadow: 0 50px 1px 3px rgba(168, 168, 168, 0.911);
    min-width: 100%;
  }
  .container1 {
    padding-left: 0px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 30px;
    padding-bottom: 30px;
    padding-bottom: 30px;
    font-size: 18px;
    min-width: 100%;

  }

  #title {
    padding-left: 10px;
  }

  h3 {
    padding-left: 10px;
  }


  .textCon {
    display: flex;
    margin: auto;
    max-width: 50%;
  }

  .text {
    padding-left: 10px;
    padding-right: 10px;
    max-width: 100%;
    font-size: 16px;
    line-height: 28px;
  }
}
</style>