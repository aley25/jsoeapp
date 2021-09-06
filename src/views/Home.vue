<template>
  <div class="home h-100">
    <div class="mainback d-flex col-12 mx-0 px-0">
      <div id="deskimage" class="col-6 d-flex justify-content-center align-items-center">
          <!--<img alt="Vue logo" src="../assets/logo.png" />-->
          <button type="button" class="h-25 w-50 btn btn-outline-info">Contactame</button>
      </div>
      
      <div id="information" class="col-6 d-flex flex-column justify-content-center align-items-center p-5">
        <h1 class="names text-light">Jose Daniel Aley Jiménez</h1>
        <p class="text-light text-center">
          Ingeniero en Informática nacido en Colombia, actualmente viviendo en
          Costa Rica. Amante de la tecnología, el deporte, el anime y la música.
        </p>
      </div>
      
    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>

<style scoped>
.mainback {
  height: 25em;
  background: rgb(52,58,64);
  background: linear-gradient(180deg, rgba(52,58,64,1) 0%, rgba(85,95,129,1) 64%, rgba(48,122,170,1) 89%);
}

#information{

}

#deskimage{
  background-image: url("../assets/desk_image.jpg");
  background-size: cover;

}
</style>