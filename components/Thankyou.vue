<template>
    <div class="container s_allow_columns">
        <div class="container s_allow_columns">
          <div class="row">
            <div class="col-lg-7 col-xl-6 mr-lg-auto o_colored_level">
              <span class="d-block fa fa-4x fa-thumbs-up mx-auto rounded-circle bg-primary"></span>
              <img v-bind:src="require('static/Thanks.jpg')" alt="house_image1" class="house_image" />
              <br>
              <h1 class="text-center">Gracias!</h1>
              <div class="pb16 pt16 s_hr" data-snippet="s_hr" data-name="Separator">
                <hr class="mx-auto border-top w-50 border-dark text-center">
              </div>
              <h5 class="text-center">                
                <strong>Su mensaje ha sido enviado exitosamente.</strong>
              </h5>
              <p class="text-center">Nos comunicaremos pronto.</p>
            </div>
            <div class="col-lg-4 o_colored_level">
              <ul class="list-unstyled mb-0 pl-2">
                <li>Casa La Yola<br></li>
                <li>
                  <i class="fa fa-map-marker fa-fw mr-2"></i>
                  <span class="o_force_ltr">Km 136 camino a Monterico</span>
                </li>
                <li>
                  <i class="fa fa-phone fa-fw mr-2"></i>
                  <span class="o_force_ltr">+502 5978-1074<br></span>
                </li>
                <li>
                  <i class="fa fa-1x fa-fw fa-envelope mr-2"></i>
                  <span>casalayola@gmail.com</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
    </div>      
</template>

<style scoped>
    .container {
        padding: 5px;
        margin-top: 25px;
        margin-bottom: 25px;
    }    
    .house_image{
        padding-left: 35%;
    }
</style>
