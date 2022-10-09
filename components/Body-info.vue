<template>
    <div>
        <section class="text_block">
            <p></p>
            <p></p>
            <span>Estamos en Madre Vieja, Taxisco, Santa Rosa.</span>
            <p></p>
            <p></p>
            <h1>El espacio</h1>
            <p></p>
            <p></p>
            <span>Hermosa casa de playa, piscina y una zona de descanso con parrilla. Hay un gran espacio para jugar fútbol o voleibol de playa.</span>
            <p></p>
            <p></p>
        </section>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <p></p>
                    <p></p>
                    <h1>Detalles</h1>
                    <p></p>
                    <p></p>
                    <span>Toda la casa está disponible excepto el dormitorio principal. Aún así, 18 personas encajan cómodamente, cada habitación con su unidad de aire acondicionado.</span>
                    <p></p>
                    <p></p>     
                    <span>Se pretende que sea un ambiente familiar para disfrutar y no un lugar para fiestas con exceso de licor.</span>
                    <p></p>
                    <p></p>    
                    <a class="btn btn-primary btn-contact" href="/contactus" title="">Contáctenos</a>                                         
                    <p></p>
                    <p></p>   
                </div>
                <div class="col"></div>
                <div class="col">
                    <img v-bind:src="require('static/beach_00.jpg')" alt="house_image1" class="house_image" />
                </div>               
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col">
                    <img v-bind:src="require('static/beach_01.jpg')" alt="house_image2" class="house_image" />
                </div>
                <div class="col"></div>
                <div class="col-6">
                    <p></p>
                    <p></p>
                    <h1>Ubicacion fantastica</h1>                    
                    <p></p>
                    <p></p>     
                    <span>Hermosa, confortable, casa de playa totalmente equipada! Perfecto para un fin de semana familiar. Playa a poca distancia (300 MTS).</span>
                    <p></p>
                    <p></p>    
                    <a class="btn btn-primary btn-contact" href="/contactus" title="">Contáctenos</a>                                         
                    <p></p>
                    <p></p>   
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
    .text_block {
        background-color: #8B1E3F;
        color: #f5f0f2;        
        padding: 50px;    }
    .container {
        padding: 5px;
        margin-top: 25px;
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