<template>
  <div class="career-wrapper">
    <section>
      <div class="hiring-header">
        <h1>WE ARE HIRING</h1>
      </div>
    </section>
    <section class="job-posts">
      <div class="job-post-wrapper">
        <div class="job-post">
          <div>
            <h3>Customer Service Representative</h3>
            <p>
              Customer Service Representative for our livery/outfitter in
              Indianapolis. The successful candidate will be responsible for
              providing exceptional customer service to our guests, renting out
              watercraft and equipment, and promoting river safety as well as
              environmental sustainability
            </p>
          </div>
        </div>
        <div class="button-wrapper">
          <a
            href="/assets/images/franks-employment-application.pdf"
            download
            class="frank-btn"
          >
            Application
          </a>
          <a
            href="/assets/images/franks-customer-job-post.pdf"
            download
            class="frank-btn-two"
          >
            Job Posting
          </a>
        </div>
      </div>

      <div class="job-post-wrapper">
        <div class="job-post">
          <div>
            <h3>Operations Associate</h3>
            <p>
              Operations Associate for our livery/outfitter in Indianapolis. The
              successful candidate will be responsible for providing exceptional
              customer service to our guests, renting out canoes, kayaks, and
              stand-up paddle boards, leading educational tours and providing
              tailored experiences to our clientele.
            </p>
          </div>
        </div>
        <div class="button-wrapper">
          <a
            href="/assets/images/franks-employment-application.pdf"
            download
            class="frank-btn"
          >
            Application
          </a>
          <a
            href="/assets/images/franks-operations-job-post.pdf"
            download
            class="frank-btn-two"
          >
            Job Posting
          </a>
        </div>
        <div class="instructions">
          <h4>
            To apply, please send your completed application to
            <span
              ><a href="mailto:admin@frankslivery.com"
                >Admin@FranksLivery.com</a
              ></span
            >
            <br />
            We look forward to hearing from you!
          </h4>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Frank's Paddlesports Livery - Now Hiring"
    };
  }
};
</script>

<style lang="css" scoped>
.career-wrapper {
  background-color: #fffbce;
  padding-left: 25px;
  padding-right: 25px;
}
.hiring-header {
  padding-top: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}
.hiring-header h1 {
  font-family: "CocoGoose-Pro";
  font-size: 4.5rem;
  font-weight: 700;
  color: #3b4a25;
  text-align: center;
}
.job-posts {
  padding-top: 50px;
}
.job-post h3 {
  color: var(--thm-black);
  font-family: "CocoGoose-Pro";
}
.job-post p {
  color: black;
}
.job-post-wrapper {
  padding-bottom: 45px;
  max-width: 80%;
  margin-left: auto;
  margin-right: auto;
}
@media screen and (max-width: 768px) {
  .job-post-wrapper {
    max-width: 100%;
  }
}
.job-post {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  max-width: 80vw;
  margin-left: auto;
  margin-right: auto;
}
.button-wrapper {
  max-width: 80vw;
  margin-left: auto;
  margin-right: auto;
}
.frank-btn {
  display: inline-block;
  vertical-align: middle;
  border: none;
  outline: none;
  background-color: var(--thm-base);
  font-size: 20px;
  color: white !important;
  font-weight: 600;
  padding: 14px 25px;
  border-radius: 5px;
  -webkit-transition: all 0.4s ease;
  transition: all 0.4s ease;
}
.frank-btn-two {
  display: inline-block;
  vertical-align: middle;
  border: none;
  outline: none;
  background-color: var(--thm-black);
  font-size: 20px;
  color: white !important;
  font-weight: 600;
  padding: 14px 25px;
  border-radius: 5px;
  -webkit-transition: all 0.4s ease;
  transition: all 0.4s ease;
}

.frank-btn:hover {
  color: var(--thm-black) !important;
}
.frank-btn-two:hover {
  color: var(--thm-base) !important;
}
.instructions {
  padding-top: 25px;
}
.instructions h4 {
  color: var(--thm-black);
  font-weight: 600;
}
.instructions span {
  color: var(--thm-base);
}
.instructions a {
  color: var(--thm-base);
}
</style>
