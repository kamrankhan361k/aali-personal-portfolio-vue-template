<template>
  <div class="aali_tm_section" id="about">
    <div class="aali_tm_about">
      <div class="about_inner">
        <div class="left">
          <div class="image">
            <img src="img/thumbs/45-49.jpg" alt="" />
            <div class="main" data-img-url="img/about/1.jpg"></div>
            <span
              class="square moving_effect"
              data-direction="y"
              data-reverse="yes"
            ></span>
            <span class="border"
              ><span
                class="in moving_effect"
                data-direction="x"
                data-reverse="yes"
              ></span
            ></span>
          </div>
        </div>
        <div class="center">
          <div class="title wow fadeInUp" data-wow-duration="1s">
            <span class="small">About Me</span>
            <h3>I'm <span>Aali</span></h3>
            <h3>Web <span>Designer</span></h3>
            <span class="subtitle">Based in London,UK</span>
          </div>
          <div
            class="text wow fadeInUp"
            data-wow-duration="1s"
            data-wow-delay="0.2s"
          >
            <p>
              Hi! My name is Aali Walker. I am UI/UX designer, and I'm very
              passionate and dedicated to my work.
            </p>
            <p>
              With 20 years experience as a professional graphic designer and
              web developer, I have acquired the skills and knowledge necessary
              to make your project a success.
            </p>
          </div>
          <div
            class="aali_tm_button wow fadeInUp"
            data-wow-duration="1.5s"
            data-wow-delay="0.2s"
          >
            <a href="img/cv/1.jpg" download>
              <span v-html="download"> </span
            ></a>
          </div>
        </div>
        <div class="right">
          <div class="image">
            <img src="img/thumbs/41-61.jpg" alt="" />
            <div class="main" data-img-url="img/about/2.jpg"></div>
            <div
              class="square moving_effect"
              data-direction="x"
              data-reverse="no"
            ></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { download } from "./svgImage";
export default {
  name: "About",
  data() {
    return {
      download: `Download CV ${download}`,
    };
  },
};
</script>
