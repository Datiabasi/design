<template>
  <div class="container px-md-5 pt-md-5 mb-md-5">
    <div class="content-con">
      <div class="grid-item1 item text-white">
        <div class="name pb-1">Web Design</div>
        <div class="view">
          View Projects
          <span class="arrow pl-2"> <i class="far fa-chevron-right"></i></span>
        </div>
      </div>
      <div class="grid-item2 item text-white">
        <div class="name pb-1">App Design</div>
        <div class="view">
          View Projects
          <span class="arrow pl-2"> <i class="far fa-chevron-right"></i></span>
        </div>
      </div>
      <div class="grid-item3 item text-white">
        <div class="name pb-1">Graphic Design</div>
        <div class="view">
          View Projects
          <span class="arrow pl-2"> <i class="far fa-chevron-right"></i></span>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.content-con {
  position: relative;
  z-index: 3;
  display: grid;
  grid-template-columns: auto auto;
  grid-gap: 25px;
}
.grid-item1 {
  border-radius: 1rem;
  height: 591px;
  grid-row: 1/3;
  background-blend-mode: overlay;
  background-color: rgba(0, 0, 0, 0.342);
  background-image: url(../assets/desktop/image-web-design-large.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.grid-item2 {
  border-radius: 1rem;
  background-blend-mode: overlay;
  background-color: rgba(0, 0, 0, 0.342);
  background-image: url(../assets/desktop/image-app-design.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.grid-item3 {
  border-radius: 1rem;
  background-blend-mode: overlay;
  background-color: rgba(0, 0, 0, 0.342);
  background-image: url(../assets/desktop/image-graphic-design.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-transform: uppercase;
}
.name {
  font-size: 35px;
  letter-spacing: 2px;
}
.view {
  font-size: 14px;
  letter-spacing: 3px;
}
.arrow {
  font-size: 10px;
  color: #e7816b;
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .container {
    padding: 0;
  }
  .content-con {
    display: grid;
    grid-template-columns: auto;
    grid-gap: 1.2rem;
    padding: 0rem 1.2rem;
  }
  .grid-item1 {
    height: auto;
    background-image: url(../assets/mobile/image-web-design.jpg);
  }
  .grid-item2 {
    background-image: url(../assets/mobile/image-app-design.jpg);
  }
  .grid-item3 {
    background-image: url(../assets/mobile/image-graphic-design.jpg);
  }
  .item {
    padding: 7rem 0rem;
  }
  .name {
    font-size: 27px;
  }
}
</style>