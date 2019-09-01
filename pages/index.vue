<template>
  <div id="home-section" class="home-head">
    <div class="row">
      <div class="col-md-3 col-lg-2"></div>
      <div class="col-md-9 col-lg-10">
        <div class="head-slider">
          <div class="intro-form">
            <div>
              <div class="home-slider-img">
                <div class="slider-overlay">
                  <div class="home-slider-social-overlay animated zoomInLeft slow delay-3s">
                    <a rel="nofollow" target="_blank" href="#" class="no-line">
                      <font-awesome-icon :icon="['fab', 'facebook-f']" />
                    </a>

                    <a rel="nofollow" target="_blank" href="#" class="no-line">
                      <font-awesome-icon :icon="['fab', 'twitter']" />
                    </a>

                    <a rel="nofollow" target="_blank" href="#" class="no-line">
                      <font-awesome-icon :icon="['fab', 'instagram']" />
                    </a>

                    <a rel="nofollow" target="_blank" href="#" class="no-line">
                      <font-awesome-icon :icon="['fab', 'youtube']" />
                    </a>
                  </div>

                  <div class="slider-caption">
                    <h1 class="slider-title animated fadeInUp delay-1s slow">نحن نبني حلمك</h1>
                    <p class="slider-desc">
                      لوريم ايبسوم دولار سيت أميت ,كونسيكتيتور أدايبا يسكينج
                      أليايت,سيت دو أيوسمود تيمبور أنكايديديونتيوت لابوري ات
                      دولار ماجنا أليكيوا يوت انيم أد مينيم فينايم,كيواس
                      نوستريد أكسير سيتاشن يللأمكو لابورأس نيسي يت أليكيوب أكس
                      أيا كوممودو كونسيكيوات
                    </p>
                    <div class="btn-links animated fadeInDown delay-2s slow">
                      <a href="about.html" class="no-line">
                        <font-awesome-icon icon="angle-double-right" />المزيد عنا
                      </a>
                      <a href="contact.html" class="no-line">
                        <font-awesome-icon icon="paper-plane" />تواصل معنا
                      </a>
                    </div>
                  </div>
                  <div class="intro-contact-form">
                    <div class="container">
                      <form method="post" action="#">
                        <div class="messages"></div>
                        <div class="row">
                          <div class="form-group col-md-6">
                            <input
                              id="form_name"
                              type="text"
                              name="name"
                              class="form-control"
                              placeholder="الأسم"
                              required="required"
                              data-error="Name is required."
                            />
                          </div>
                          <div class="form-group col-md-6">
                            <input
                              id="form_email"
                              type="email"
                              name="email"
                              class="form-control"
                              placeholder="البريد الألكتروني"
                              required="required"
                              data-error="Valid email is required."
                            />
                          </div>
                          <div class="form-group col-md-6">
                            <input
                              id="form_phone"
                              type="tel"
                              name="phone"
                              class="form-control"
                              placeholder="رقم الهاتف"
                              required="required"
                              data-error="Phone is required"
                            />
                          </div>

                          <div class="form-group col-md-6">
                            <select name="select" required class="custom-select form-control">
                              <option selected>اختيار الخدمة</option>
                              <option value="1">جراحات السمنة و المناظير</option>
                              <option value="2">الحلول الغير جراحية للسمنة</option>
                              <option value="3">التجميل النسائي</option>
                              <option value="4">الجراحات التجميلية</option>
                              <option value="5">اخري</option>
                            </select>
                          </div>
                          <div class="form-group col-md-12">
                            <textarea
                              id="form_message"
                              name="message"
                              class="form-control"
                              placeholder="الرسالة"
                              rows="4"
                              required="required"
                              data-error="Please,leave us a message."
                            ></textarea>
                          </div>
                          <div class="col-md-12 m-auto text-center">
                            <button class="btn btn-theme btn-radius">
                              <span>
                                <font-awesome-icon icon="paper-plane" />إرسال
                              </span>
                            </button>
                          </div>
                        </div>
                      </form>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

