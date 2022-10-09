<template>
    <nav class="navbar navbar-expand-lg navbar-light o_colored_level o_cc shadow-sm">
        <div id="top_menu_container" class="container justify-content-start justify-content-lg-between">                    
            <a href="/" class="navbar-brand logo mr-4">
                <span role="img" aria-label="Logo of casalayola" title="casalayola">
                    <img v-bind:src="require('static/Logo-02.jpg')" alt="casalayola" class="img-logo" />
                </span>
            </a>                
          <div id="top_menu_collapse" class="collapse navbar-collapse order-last order-lg-0" aria-expanded="false">
            <ul id="top_menu" class="nav navbar-nav flex-grow-1">
                <li class="nav-item">
                    <a role="menuitem" href="/" class="nav-link active">
                        <span>Inicio</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a role="menuitem" href="/servicios" class="nav-link ">
                        <span>Servicios</span>
                    </a>
                </li>                            
            </ul>                       
          </div>                    
          <div class="oe_structure oe_structure_solo ml-lg-4">
             <section class="s_text_block o_colored_level" style="background-image: none;">
                <div class="container">
                <a href="/contactus" class="btn btn-primary btn-contact-nav" title="">Contáctenos</a>
                </div>
             </section>
          </div>                    
          <button type="button" class="navbar-toggler ml-auto">
            <span class="navbar-toggler-icon o_not_editable"></span>
          </button>
        </div>
    </nav>
 </template>
 
 <style scoped>
  .img-logo {
    object-fit: contain;
    display: block;
    width: auto;
    height: 5.5rem;
  }
  .btn-contact-nav {
    color: #FFFFFF;
    background-color: #8B1E3F;
    border-color: #8B1E3F;
  }
</style>