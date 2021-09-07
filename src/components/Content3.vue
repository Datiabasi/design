<template>
  <div class="container px-md-5 mt-md-5">
    <div class="content3 py-4 px-md-5 text-light">
      <div class="circle-con">
        <img
          src="../assets/desktop/bg-pattern-call-to-action.svg"
          alt=""
          class="circle"
        />
      </div>
      <div class="px-4 pt-4 oop">
        <h2>
          Let's talk about <br />
          your project
        </h2>
        <p>
          Ready to take it to the next level? Contact us today and find out how
          <br />
          our expertise can help your business grow.
        </p>
      </div>
      <div class="d-flex align-items-center px-md-4 oop">
        <button class="btn py-2 px-2">Get In Touch</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.container {
  position: relative;
}
.circle-con {
  position: absolute;
  top: -43%;
  right: -220px;
}
.circle {
  width: 75%;
}
.content3 {
  display: flex;
  justify-content: space-between;
  background-color: #e7816b;
  border-radius: 1rem;
  position: relative;
  bottom: -50px;
  overflow: hidden;
}
h2 {
  font-size: 37px;
}
.btn {
  background-color: #fff;
  text-transform: uppercase;
  font-size: 15px !important;
  font-weight: 500;
}
.oop {
  z-index: 10;
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .circle {
    width: 50rem;
  }
  .circle-con {
    position: absolute;
    top: 0 !important;
    right: -220px;
  }

  .content3 {
    padding: 5rem 0rem !important;
    display: block;
    text-align: center !important;
    background-color: #e7816b;
    border-radius: 1rem;
    position: relative;
    bottom: -120px;
    overflow: hidden;
  }
  .btn {
    margin-left: auto !important;
    margin-right: auto !important;
  }
  h2 {
    font-size: 27px;
  }
  br {
    display: none;
  }
  p {
    font-size: 13.5px;
  }
}
@media (min-width: 375px) and (max-width: 424.98px) {
}
@media (min-width: 0px) and (max-width: 374.98px) {
}
</style>