<template>
    <div class="container">
        <div class="row">
            <div class="col-6">
                <p></p>
                <p></p>
                <h1>Si te preguntas precios?</h1>
                <p></p>
                <p></p>
                <span>El precio de la renta puede variar dependiendo la fecha, pues lo dias festivos como semana santa y fin año es temporada alta.</span>
                <p></p>
                <p></p>     
                <span>Nuestra casa esta registrada en Airbnb y  todas las reservaciones incluyen protección gratuita en caso de que el anfitrión cancele, de que haya imprecisiones en el anuncio o de que surjan otros inconvenientes, como problemas al momento de hacer el check-in. </span>
                <p></p>
                <p></p>    
                <span>El precio normal por noche es de USD $325.00</span>
                <p></p>
                <p></p>
                <a class="btn btn-primary btn-contact" href="http://bit.ly/3ePHAA5" title="">Reserva en Airbnb</a>                                         
                <p></p>
                <p></p>   
            </div>
            <div class="col"></div>
            <div class="col">
                <img v-bind:src="require('static/photo-servicios.jpg')" alt="house_image1" class="house_image" />
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
</style>