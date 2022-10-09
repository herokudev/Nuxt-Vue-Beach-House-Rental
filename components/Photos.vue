<template>
    <div>
        <section class="s_title pb40 pt72 o_colored_level" data-vcss="001" data-snippet="s_title" data-name="Title" style="background-image: none;" data-original-title="" title="" aria-describedby="tooltip636721">
        <div class="container s_allow_columns">
          <h1 style="text-align: center;">
            <font style="font-size: 62px;">Nuestros ambientes</font>
            <br>
          </h1>
        </div>
      </section>   
      <section class="photos_grid s_three_columns o_cc o_cc3 pt0 pb72 o_colored_level" data-vcss="001" data-snippet="s_three_columns" data-name="Columns" style="background-image: none;" data-original-title="" title="" aria-describedby="tooltip176029">
        <div class="container">
          <div class="row d-flex align-items-stretch">
            <div class="photo-item col-lg-4 s_col_no_bgcolor pt16 pb16">
              <div class="card bg-white h-100">
                <img v-bind:src="require('static/beach07.jpg')" alt="house_image2" class="house_image" />
                <div class="card-body" data-original-title="" title="" aria-describedby="tooltip632050">
                  <span class="text-600 font-weight-bold">​</span>
                  <h3 class="card-title">Dormitorios<br></h3>
                  <p class="card-text">
                    <br>
                  </p>
                  <a href="/dorms" class="btn btn-primary btn-contact" data-original-title="" title="">Ver mas fotos</a>
                </div>
              </div>
            </div>
            <div class="photo-item col-lg-4 s_col_no_bgcolor pt16 pb16">
              <div class="card bg-white h-100">
                <img v-bind:src="require('static/beach04.jpg')" alt="house_image2" class="house_image" />
                <div class="card-body" data-original-title="" title="" aria-describedby="tooltip838081">
                  <span class="text-600 font-weight-bold">​</span>
                  <h3 class="card-title">Interiores<br></h3>
                  <p class="card-text">
                    <br>
                  </p>
                  <a href="/interiores" class="btn btn-primary btn-contact" data-original-title="" title="">Ver mas fotos</a>
                </div>
              </div>
            </div>
            <div class="photo-item col-lg-4 s_col_no_bgcolor pt16 pb16">
              <div class="card bg-white h-100">
                <img v-bind:src="require('static/House21.jpg')" alt="house_image2" class="house_image" />
                <div class="card-body" data-original-title="" title="" aria-describedby="tooltip551133">
                  <span class="text-600 font-weight-bold">​</span>
                  <h3 class="card-title">Exteriores<br></h3>
                  <p class="card-text">
                    <br>
                  </p>
                  <a href="/exteriores" class="btn btn-primary btn-contact" data-original-title="" title="">Ver mas fotos</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>  
      <section class="comments s_numbers o_cc o_cc1 pt32 pb56 o_colored_level" data-snippet="s_numbers" data-name="Numbers" style="background-image: none;" data-original-title="" title="" aria-describedby="tooltip838565">
        <div class="container">
          <div class="row">
            <div class="col-lg-3 text-center pt24 pb24 o_colored_level">
              <span class="s_number display-4">
        77&nbsp;</span>
              <br>
              <h6>Comentarios positivos<br></h6>
            </div>
            <div class="col-lg-3 text-center pt24 pb24 o_colored_level">
              <span class="s_number display-4">
        4.8/5&nbsp;</span>
              <br>
              <h6>Limpieza<br></h6>
            </div>
            <div class="col-lg-3 text-center pt24 pb24 o_colored_level">
              <span class="s_number display-4">
        5.0/5&nbsp;</span>
              <br>
              <h6>Fiabilidad<br></h6>
            </div>
            <div class="col-lg-3 text-center pt24 pb24 o_colored_level">
              <span class="s_number display-4">
        4.9/5&nbsp;</span>
              <br>
              <h6>Precio<br></h6>
            </div>
          </div>
        </div>
      </section>

    </div>
</template>
<style scoped>
    .photos_grid {
        background-color: #23395B;
        padding-bottom: 35px;
    }
    .photo-item {
        padding-top: 15px;
    }
    .house_image {
        object-fit: contain;
        display: block;
        width: auto;
        height: 20rem;        
        }    
    .btn-contact {
        color: #FFFFFF;
        background-color: #8B1E3F;
        border-color: #8B1E3F;
    }      
    .comments {
        padding-bottom: 35px;
    }
</style>