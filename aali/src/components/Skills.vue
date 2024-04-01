<template>
  <div class="aali_tm_section">
    <div class="aali_tm_skills">
      <div class="container">
        <div class="skills_inner">
          <div class="left wow fadeInLeft" data-wow-duration="1s">
            <div
              class="aali_tm_main_title"
              data-text-align="left"
              data-color="light"
            >
              <span>My Skills</span>
              <h3>
                You Can Imagine<br />
                I Can Do
              </h3>
              <p>
                I am working on a professional, visually sophisticated and
                technologically proficient, responsive and multi-functional
                creative personal resume portfolio template Aali
              </p>
            </div>
          </div>
          <div class="right wow fadeInRight" data-wow-duration="1s">
            <div class="dodo_progress">
              <div class="progress_inner skillsInner___" data-value="86">
                <span
                  ><span class="label">Website Design</span
                  ><span class="number">86%</span></span
                >
                <div class="background">
                  <div class="bar">
                    <div class="bar_in"></div>
                  </div>
                </div>
              </div>
              <div class="progress_inner skillsInner___" data-value="90">
                <span
                  ><span class="label">Mobile Application</span
                  ><span class="number">90%</span></span
                >
                <div class="background">
                  <div class="bar"><div class="bar_in"></div></div>
                </div>
              </div>
              <div class="progress_inner skillsInner___" data-value="66">
                <span
                  ><span class="label">Game Programming</span
                  ><span class="number">66%</span></span
                >
                <div class="background">
                  <div class="bar"><div class="bar_in"></div></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <span
        class="border moving_effect"
        data-direction="x"
        data-reverse="yes"
      ></span>
    </div>
  </div>
</template>

<script>
import { activeSkillProgress } from "../utils/utils";

export default {
  name: "Skills",
  mounted() {
    window.addEventListener("scroll", activeSkillProgress);
  },
};
</script>
