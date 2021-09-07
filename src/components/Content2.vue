<template>
  <div class="container px-md-5 py-md-5">
    <div class="content-con d-flex justify-content-between mb-md-5">
      <div class="item text-center">
        <div class="item-image py-4">
          <div class="circle">
            <img
              src="../assets/desktop/bg-pattern-hero-home.svg"
              alt=""
              width="160rem"
            />
            <div class="image">
              <img
                src="../assets/desktop/illustration-passionate.svg"
                alt=""
                width="150rem"
              />
            </div>
          </div>
        </div>
        <div class="item-name pb-4">Passionate</div>
        <div class="item-details">
          Each Project starts with an in-depth brand research <br />
          to ensure we only create products that serve a <br />
          purpose. We merge art, design, and technology <br />
          into exciting new solutions.
        </div>
      </div>
      <div class="item text-center">
        <div class="item-image py-4">
          <div class="circle">
            <img
              src="../assets/desktop/bg-pattern-hero-desktop.svg"
              alt=""
              width="160rem"
            />
            <div class="image">
              <img
                src="../assets/desktop/illustration-resourceful.svg"
                alt=""
                width="150rem"
              />
            </div>
          </div>
        </div>
        <div class="item-name pb-4">resourceful</div>
        <div class="item-details">
          Everything that we do has a stategic purpose. We <br />
          use an agile approach in all of our projects and <br />
          value customer collaboration. It guarantees <br />
          superior results that fulfill our clients' needs.
        </div>
      </div>
      <div class="item text-center">
        <div class="item-image py-4">
          <div class="circle">
            <img
              src="../assets/desktop/bg-pattern-hero-home.svg"
              alt=""
              width="160rem"
            />
            <div class="image">
              <img
                src="../assets/desktop/illustration-friendly.svg"
                alt=""
                width="150rem"
              />
            </div>
          </div>
        </div>
        <div class="item-name pb-4">friendly</div>
        <div class="item-details">
          We are a group of enthusiastic folks who know <br />
          how to put people first. Our success depends on <br />
          our customers, and we strive to give them the best <br />
          experience a company can provide.
        </div>
      </div>
    </div>
    <div class="leaf-con">
      <img src="../assets/desktop/bg-pattern-leaf.svg" alt="" class="leaf" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.leaf-con {
  width: fit-content !important;
  position: absolute;
  right: -6.5rem;
  bottom: -14rem;
}
.leaf {
  -webkit-transform: scale(-1, -1);
  transform: scale(-1, -1);
  width: 50rem;
}
.container {
  position: relative;
}
.item-name {
  text-transform: uppercase;
  font-size: 18px;
  font-weight: 500;
  letter-spacing: 4px;
}
.circle {
  position: relative;
  z-index: 1;
}
.image {
  z-index: 50;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
}
.item-details {
  font-size: 15px;
}
.content-con {
  position: relative;
  z-index: 3;
}
@media (min-width: 768px) and (max-width: 1139.98px) {
  .leaf-con {
    display: none;
  }
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .leaf-con {
    display: none;
  }
  .container {
    padding: 0;
    overflow: hidden;
  }
  .content-con {
    display: block !important;
    padding: 0rem 1.2rem;
  }
  br {
    display: none;
  }
  .item-details {
    text-align: center;
    font-size: 14px;
  }
}
</style>
