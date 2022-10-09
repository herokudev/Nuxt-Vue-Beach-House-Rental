<template>
    <div class="container s_allow_columns">
          <div class="row">
            <div class="col-lg-8 mt-4 mt-lg-0 o_colored_level">
              <p>
                                    Quieres venir a descansar a nuestra casa ??<br>Dejanos tus datos y pronto te contactaremos.<br></p>
              <section class="s_website_form" data-vcss="001" data-snippet="s_website_form" data-name="Form">
                <div class="container">
                  <form id="contactus_form" action="/website/form/" method="post" enctype="multipart/form-data" class="o_mark_required" data-mark="*" data-model_name="mail.mail" data-success-mode="redirect" data-success-page="/contactus-thank-you" data-pre-fill="true">
                    <div class="s_website_form_rows row s_col_no_bgcolor">
                      <div class="form-group col-12 s_website_form_field s_website_form_custom s_website_form_required" data-type="char" data-name="Field" data-visibility-condition="" data-visibility-between="">
                        <div class="row s_col_no_resize s_col_no_bgcolor">
                          <label class="col-form-label col-sm-auto s_website_form_label" style="width: 200px" for="contact1">
                            <span class="s_website_form_label_content">Nombre:</span>
                            <span class="s_website_form_mark"> *</span>
                          </label>
                          <div class="col-sm">
                            <input id="contact1" type="text" class="form-control s_website_form_input" name="Nombre:" data-fill-with="name">
                          </div>
                        </div>
                      </div>
                      <div data-visibility-condition="" data-visibility-between="" class="form-group s_website_form_field col-12 s_website_form_custom" data-type="char" data-name="Field">
                        <div class="row s_col_no_resize s_col_no_bgcolor">
                          <label class="col-form-label col-sm-auto s_website_form_label " style="width: 200px" for="omidtds8a7ko">
                            <span class="s_website_form_label_content">Numero telefonico:</span>
                          </label>
                          <div class="col-sm">
                            <input type="text" class="form-control s_website_form_input" name="Numero telefonico:" value="" placeholder="" id="omidtds8a7ko" data-fill-with="phone">
                          </div>
                        </div>
                      </div>
                      <div class="form-group col-12 s_website_form_field s_website_form_required" data-type="email" data-name="Field" data-visibility-condition="" data-visibility-between="">
                        <div class="row s_col_no_resize s_col_no_bgcolor">
                          <label class="col-form-label col-sm-auto s_website_form_label" style="width: 200px" for="contact3">
                            <span class="s_website_form_label_content">Email</span>
                            <span class="s_website_form_mark"> *</span>
                          </label>
                          <div class="col-sm">
                            <input id="contact3" type="email" class="form-control s_website_form_input" name="email_from" data-fill-with="email">
                          </div>
                        </div>
                      </div>
                      <div class="form-group col-12 s_website_form_field s_website_form_custom" data-type="char" data-name="Field" data-visibility-condition="" data-visibility-between="">
                        <div class="row s_col_no_resize s_col_no_bgcolor">
                          <label class="col-form-label col-sm-auto s_website_form_label" style="width: 200px" for="contact4">
                            <span class="s_website_form_label_content">Compañia</span>
                          </label>
                          <div class="col-sm">
                            <input id="contact4" type="text" class="form-control s_website_form_input" name="Compañia" data-fill-with="commercial_company_name">
                          </div>
                        </div>
                      </div>
                      <div data-visibility-condition="" data-visibility-between="" class="form-group s_website_form_field col-12 s_website_form_required" data-type="char" data-name="Field">
                        <div class="row s_col_no_resize s_col_no_bgcolor">
                          <label class="col-form-label col-sm-auto s_website_form_label " style="width: 200px" for="o63r9ollb33m">
                            <span class="s_website_form_label_content">Propone Fechas</span>
                            <span class="s_website_form_mark">     *</span>
                          </label>
                          <div class="col-sm">
                            <input type="text" class="form-control s_website_form_input" name="subject" value="" placeholder="" id="o63r9ollb33m" data-fill-with="undefined">
                          </div>
                        </div>
                      </div>
                      <div class="form-group col-12 s_website_form_field s_website_form_custom s_website_form_required" data-type="text" data-name="Field" data-visibility-condition="" data-visibility-between="">
                        <div class="row s_col_no_resize s_col_no_bgcolor">
                          <label class="col-form-label col-sm-auto s_website_form_label" style="width: 200px" for="contact6">
                            <span class="s_website_form_label_content">Tienes preguntas??</span>
                          </label>
                          <div class="col-sm">
                            <textarea id="contact6" class="form-control s_website_form_input" name="Tienes preguntas??" ></textarea>
                          </div>
                        </div>
                      </div>
                      <div class="form-group s_website_form_field col-12    s_website_form_dnone" data-name="Field">
                        <div class="row s_col_no_resize s_col_no_bgcolor">
                          <label class="col-form-label col-sm-auto s_website_form_label " style="width: 200px">
                            <span class="s_website_form_label_content"></span>
                          </label>
                          <div class="col-sm">
                            <input type="hidden" class="form-control s_website_form_input" name="email_to" value="casalayola@gmail.com">
                            <div class="s_website_form_field_description small form-text text-muted">
            Separate email addresses with a comma.
        </div>
                          </div>
                        </div>
                      </div>
                      <div class="form-group col-12 s_website_form_submit" data-name="Submit Button" data-original-title="" title="" aria-describedby="tooltip940178">
                        <div style="width: 200px;" class="s_website_form_label "></div>
                        <a href="#" role="button" class="s_website_form_send btn btn-primary btn-lg" data-original-title="" title="">Enviar Datos</a>
                        <span id="s_website_form_result"></span>
                        <br>
                      </div>
                    </div>
                  </form>
                </div>
              </section>
            </div>
            <div class="col-lg-4 mt-4 mt-lg-0 o_colored_level">
              <ul class="list-unstyled mb-0 pl-2">
                <li>Casa La Yola<br></li>
                <li>
                  <i class="fa fa-map-marker fa-fw mr-2"></i>
                  <span class="o_force_ltr">Km 136 camino a Monterico</span>
                </li>
                <li>
                  <i class="fa fa-phone fa-fw mr-2"></i>
                  <span class="o_force_ltr">+502 5978-1074</span>
                </li>
                <li>
                  <i class="fa fa-1x fa-fw fa-envelope mr-2"></i>
                  <span>casalayola@gmail.com</span>
                </li>
              </ul>
            </div>
          </div>
    </div>      
</template>

<style>
    .container {
        padding: 5px;
        margin-top: 25px;
        margin-bottom: 25px;
    }    

    .form-button {
        color: #FFFFFF;
        background-color: #8B1E3F;
        border-color: #8B1E3F;        
    }
</style>
