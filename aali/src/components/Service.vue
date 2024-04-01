<template>
  <div class="aali_tm_section" id="service">
    <div class="aali_tm_service">
      <div class="container">
        <div class="service_list">
          <ul>
            <li class="simple wow fadeInLeft" data-wow-duration="1s">
              <div class="list_inner">
                <div
                  class="aali_tm_main_title"
                  data-text-align="left"
                  data-color="dark"
                >
                  <span>What I Do</span>
                  <h3>My Services</h3>
                  <p>
                    We offer high quality products for competitive prices. Our
                    main goal is customer satisfaction, which we obtain through
                    market orientation of ongoing service and support.
                  </p>
                </div>
              </div>
            </li>

            <li
              class="wow fadeInRight"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner tilt-effect">
                <span class="icon" v-if="dark">
                  <img class="svg" src="img/svg/camera-dark.svg" alt="" />
                  <img class="back" src="img/svg/service-dark.png" alt="" />
                </span>

                <span class="icon" v-if="!dark">
                  <img class="svg" src="img/svg/camera.svg" alt="" />
                  <img class="back" src="img/svg/service.png" alt="" />
                </span>

                <div class="title">
                  <h3>Video Production</h3>
                  <span class="price">Starts from <span>$49</span></span>
                </div>
                <div class="text">
                  <p>
                    Aali is a leading web design agency with an award-winning
                    design team that creates innovative, effective websites
                  </p>
                </div>
                <a
                  class="aali_tm_full_link"
                  href="#"
                  @click.prevent="active = 1"
                ></a>
                <img
                  class="popup_service_image"
                  src="img/service/1.jpg"
                  alt=""
                />
                <div class="service_hidden_details">
                  <div class="service_popup_informations">
                    <div class="descriptions">
                      <p>
                        Aali is a leading web design agency with an
                        award-winning design team that creates innovative,
                        effective websites that capture your brand, improve your
                        conversion rates, and maximize your revenue to help grow
                        your business and achieve your goals.
                      </p>
                      <p>
                        In today’s digital world, your website is the first
                        interaction consumers have with your business. That's
                        why almost 95 percent of a user’s first impression
                        relates to web design. It’s also why web design services
                        can have an immense impact on your company’s bottom
                        line.
                      </p>
                      <p>
                        That’s why more companies are not only reevaluating
                        their website’s design but also partnering with Kura,
                        the web design agency that’s driven more than $2.4
                        billion in revenue for its clients. With over 50 web
                        design awards under our belt, we're confident we can
                        design a custom website that drives sales for your
                        unique business.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <div :class="`${active === 1 ? '' : 'service_hidden_details'}`">
              <ModalBox :close="close">
                <div class="service_popup_informations">
                  <div class="image">
                    <img src="img/thumbs/4-2.jpg" alt="" />
                    <div
                      class="main"
                      data-img-url="img/service/1.jpg"
                      style="background-image: url('img/service/1.jpg')"
                    ></div>
                  </div>
                  <div class="main_title">
                    <h3>Video Production</h3>
                    <span class="price">Starts from <span>$49</span></span>
                  </div>
                  <div class="descriptions">
                    <p>
                      Aali is a leading web design agency with an award-winning
                      design team that creates innovative, effective websites
                      that capture your brand, improve your conversion rates,
                      and maximize your revenue to help grow your business and
                      achieve your goals.
                    </p>
                    <p>
                      In today’s digital world, your website is the first
                      interaction consumers have with your business. That's why
                      almost 95 percent of a user’s first impression relates to
                      web design. It’s also why web design services can have an
                      immense impact on your company’s bottom line.
                    </p>
                    <p>
                      That’s why more companies are not only reevaluating their
                      website’s design but also partnering with Kura, the web
                      design agency that’s driven more than $2.4 billion in
                      revenue for its clients. With over 50 web design awards
                      under our belt, we're confident we can design a custom
                      website that drives sales for your unique business.
                    </p>
                  </div>
                </div>
              </ModalBox>
            </div>
            <li class="wow fadeInLeft" data-wow-duration="1s">
              <div class="list_inner tilt-effect">
                <span class="icon" v-if="dark">
                  <img class="svg" src="img/svg/web-dark.svg" alt="" />
                  <img class="back" src="img/svg/service-dark.png" alt="" />
                </span>
                <span class="icon" v-if="!dark">
                  <img class="svg" src="img/svg/web.svg" alt="" />
                  <img class="back" src="img/svg/service.png" alt="" />
                </span>
                <div class="title">
                  <h3>Brand Identity</h3>
                  <span class="price">Starts from <span>$59</span></span>
                </div>
                <div class="text">
                  <p>
                    Aali is a leading web design agency with an award-winning
                    design team that creates innovative, effective websites
                  </p>
                </div>
                <a
                  class="aali_tm_full_link"
                  href="#"
                  @click.prevent="active = 2"
                ></a>
                <img
                  class="popup_service_image"
                  src="img/service/3.jpg"
                  alt=""
                />
                <div class="service_hidden_details">
                  <div class="service_popup_informations">
                    <div class="descriptions">
                      <p>
                        Aali is a leading web design agency with an
                        award-winning design team that creates innovative,
                        effective websites that capture your brand, improve your
                        conversion rates, and maximize your revenue to help grow
                        your business and achieve your goals.
                      </p>
                      <p>
                        In today’s digital world, your website is the first
                        interaction consumers have with your business. That's
                        why almost 95 percent of a user’s first impression
                        relates to web design. It’s also why web design services
                        can have an immense impact on your company’s bottom
                        line.
                      </p>
                      <p>
                        That’s why more companies are not only reevaluating
                        their website’s design but also partnering with Kura,
                        the web design agency that’s driven more than $2.4
                        billion in revenue for its clients. With over 50 web
                        design awards under our belt, we're confident we can
                        design a custom website that drives sales for your
                        unique business.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <div :class="`${active === 2 ? '' : 'service_hidden_details'}`">
              <ModalBox :close="close">
                <div class="service_popup_informations">
                  <div class="image">
                    <img src="img/thumbs/4-2.jpg" alt="" />
                    <div
                      class="main"
                      data-img-url="img/service/3.jpg"
                      style="background-image: url('img/service/3.jpg')"
                    ></div>
                  </div>
                  <div class="main_title">
                    <h3>Brand Identity</h3>
                    <span class="price">Starts from <span>$59</span></span>
                  </div>
                  <div class="descriptions">
                    <p>
                      Aali is a leading web design agency with an award-winning
                      design team that creates innovative, effective websites
                      that capture your brand, improve your conversion rates,
                      and maximize your revenue to help grow your business and
                      achieve your goals.
                    </p>
                    <p>
                      In today’s digital world, your website is the first
                      interaction consumers have with your business. That's why
                      almost 95 percent of a user’s first impression relates to
                      web design. It’s also why web design services can have an
                      immense impact on your company’s bottom line.
                    </p>
                    <p>
                      That’s why more companies are not only reevaluating their
                      website’s design but also partnering with Kura, the web
                      design agency that’s driven more than $2.4 billion in
                      revenue for its clients. With over 50 web design awards
                      under our belt, we're confident we can design a custom
                      website that drives sales for your unique business.
                    </p>
                  </div>
                </div>
              </ModalBox>
            </div>
            <li
              class="wow fadeInRight"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner tilt-effect">
                <span class="icon" v-if="dark">
                  <img class="svg" src="img/svg/pen-dark.svg" alt="" />
                  <img class="back" src="img/svg/service-dark.png" alt="" />
                </span>
                <span class="icon" v-else>
                  <img class="svg" src="img/svg/pen.svg" alt="" />
                  <img class="back" src="img/svg/service.png" alt="" />
                </span>
                <div class="title">
                  <h3>Creative Writing</h3>
                  <span class="price">Starts from <span>$69</span></span>
                </div>
                <div class="text">
                  <p>
                    Aali is a leading web design agency with an award-winning
                    design team that creates innovative, effective websites
                  </p>
                </div>
                <a
                  class="aali_tm_full_link"
                  href="#"
                  @click.prevent="active = 3"
                ></a>
                <img
                  class="popup_service_image"
                  src="img/service/2.jpg"
                  alt=""
                />
                <div class="service_hidden_details">
                  <div class="service_popup_informations">
                    <div class="descriptions">
                      <p>
                        Aali is a leading web design agency with an
                        award-winning design team that creates innovative,
                        effective websites that capture your brand, improve your
                        conversion rates, and maximize your revenue to help grow
                        your business and achieve your goals.
                      </p>
                      <p>
                        In today’s digital world, your website is the first
                        interaction consumers have with your business. That's
                        why almost 95 percent of a user’s first impression
                        relates to web design. It’s also why web design services
                        can have an immense impact on your company’s bottom
                        line.
                      </p>
                      <p>
                        That’s why more companies are not only reevaluating
                        their website’s design but also partnering with Kura,
                        the web design agency that’s driven more than $2.4
                        billion in revenue for its clients. With over 50 web
                        design awards under our belt, we're confident we can
                        design a custom website that drives sales for your
                        unique business.
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <div :class="`${active === 3 ? '' : 'service_hidden_details'}`">
              <ModalBox :close="close">
                <div class="service_popup_informations">
                  <div class="image">
                    <img src="img/thumbs/4-2.jpg" alt="" />
                    <div
                      class="main"
                      data-img-url="img/service/2.jpg"
                      style="background-image: url('img/service/2.jpg')"
                    ></div>
                  </div>
                  <div class="main_title">
                    <h3>Creative Writing</h3>
                    <span class="price">Starts from <span>$69</span></span>
                  </div>
                  <div class="descriptions">
                    <p>
                      Aali is a leading web design agency with an award-winning
                      design team that creates innovative, effective websites
                      that capture your brand, improve your conversion rates,
                      and maximize your revenue to help grow your business and
                      achieve your goals.
                    </p>
                    <p>
                      In today’s digital world, your website is the first
                      interaction consumers have with your business. That's why
                      almost 95 percent of a user’s first impression relates to
                      web design. It’s also why web design services can have an
                      immense impact on your company’s bottom line.
                    </p>
                    <p>
                      That’s why more companies are not only reevaluating their
                      website’s design but also partnering with Kura, the web
                      design agency that’s driven more than $2.4 billion in
                      revenue for its clients. With over 50 web design awards
                      under our belt, we're confident we can design a custom
                      website that drives sales for your unique business.
                    </p>
                  </div>
                </div>
              </ModalBox>
            </div>
            <li class="wow fadeInLeft" data-wow-duration="1s">
              <div class="list_inner tilt-effect">
                <span class="icon" v-if="dark">
                  <img class="svg" src="img/svg/user-dark.svg" alt="" />
                  <img class="back" src="img/svg/service-dark.png" alt="" />
                </span>
                <span class="icon" v-else>
                  <img class="svg" src="img/svg/user.svg" alt="" />
                  <img class="back" src="img/svg/service.png" alt="" />
                </span>
                <div class="title">
                  <h3>Digital Marketing</h3>
                  <span class="price">Starts from <span>$79</span></span>
                </div>
                <div class="text">
                  <p>
                    Aali is a leading web design agency with an award-winning
                    design team that creates innovative, effective websites
                  </p>
                </div>
                <a
                  class="aali_tm_full_link"
                  href="#"
                  @click.prevent="active = 4"
                ></a>
                <img
                  class="popup_service_image"
                  src="img/service/4.jpg"
                  alt=""
                />
              </div>
            </li>
            <div :class="`${active === 4 ? '' : 'service_hidden_details'}`">
              <ModalBox :close="close">
                <div class="service_popup_informations">
                  <div class="image">
                    <img src="img/thumbs/4-2.jpg" alt="" />
                    <div
                      class="main"
                      data-img-url="img/service/4.jpg"
                      style="background-image: url('img/service/4.jpg')"
                    ></div>
                  </div>
                  <div class="main_title">
                    <h3>Digital Marketing</h3>
                    <span class="price">Starts from <span>$79</span></span>
                  </div>
                  <div class="descriptions">
                    <p>
                      Aali is a leading web design agency with an award-winning
                      design team that creates innovative, effective websites
                      that capture your brand, improve your conversion rates,
                      and maximize your revenue to help grow your business and
                      achieve your goals.
                    </p>
                    <p>
                      In today’s digital world, your website is the first
                      interaction consumers have with your business. That's why
                      almost 95 percent of a user’s first impression relates to
                      web design. It’s also why web design services can have an
                      immense impact on your company’s bottom line.
                    </p>
                    <p>
                      That’s why more companies are not only reevaluating their
                      website’s design but also partnering with Kura, the web
                      design agency that’s driven more than $2.4 billion in
                      revenue for its clients. With over 50 web design awards
                      under our belt, we're confident we can design a custom
                      website that drives sales for your unique business.
                    </p>
                  </div>
                </div>
              </ModalBox>
            </div>
            <li
              class="simple text wow fadeInRight"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner">
                <div class="wrapper">
                  <div class="inner_text">
                    <h3>Do You Want Something Different?</h3>
                  </div>
                  <div class="aali_tm_button border">
                    <a class="anchor" href="#contact"
                      ><span v-html="`Knock Me ` + msg"></span
                    ></a>
                  </div>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <span
        class="square_left moving_effect"
        data-direction="y"
        data-reverse="yes"
      ></span>
      <span
        class="square_right moving_effect"
        data-direction="y"
        data-reverse="yes"
      ></span>
    </div>
  </div>
</template>

<script>
import ModalBox from "./ModalBox.vue";
import { msg } from "./svgImage";
export default {
  name: "Service",
  data() {
    return {
      msg,
      active: 0,
    };
  },
  props: {
    dark: Boolean,
  },
  mounted() {
    let VanillaTilt = require("vanilla-tilt");
    VanillaTilt.init(document.querySelectorAll(".tilt-effect"), {
      maxTilt: 6,
      easing: "cubic-bezier(.03,.98,.52,.99)",
      speed: 500,
      transition: true,
    });
  },
  methods: {
    close() {
      this.active = 0;
    },
  },
  components: { ModalBox },
};
</script>
