<template>
  <section class="recent-project our_projects">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single mrb-30">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-1.jpg" alt="Recent Project Img">
              <div class="project_content text-accent">
                <h4>The Parks Alliance<br>Of Indianapolis</h4>
              </div>
              <div class="hover_box">
                <nuxt-link to="/parks-alliance"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single mrb-30">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-2.jpg" alt="Recent Project Img">
              <div class="project_content text-accent">
                <h4>Indy Parks<br>Department</h4>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single mrb-30">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-3.jpg" alt="Recent Project Img">
              <div class="project_content text-accent">
                <h4>Friends<br>Of White River</h4>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single mrb-30">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-4.jpg" alt="Recent Project Img">
              <div class="project_content text-accent">
                <h4>Citizens<br>Energy Group</h4>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single mrb-30">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-5.jpg" alt="Recent Project Img">
              <div class="project_content text-accent">
                <h4>Friends of Fort Harrison<br>State Park</h4>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single mrb-30">
            <div class="project_img_box">
              <img src="/assets/images/project/recent-pro-img-6.jpg" alt="Recent Project Img">
              <div class="project_content text-accent">
                <h4>Indianapolis<br>Art Center</h4>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-12">
          <div class="our_projects_btn">
            <a href="#" class="thm-btn">Load More Projects</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ProjectPage"
    }
</script>

<style scoped>
.text-accent {
  color: var(--thm-accent)
}
</style>
