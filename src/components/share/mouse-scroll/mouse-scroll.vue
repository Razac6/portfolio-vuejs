<template>
             <div class="center-it">
  <div class="mouse"></div>
  <div class="caption">Show more</div>
</div>
</template>

<script>
export default {
  name: "share-mouse-scroll"
};
</script>
<style lang="scss" scoped>
@-webkit-keyframes scroll {
  0% {
    -webkit-transform: translateY(0);
  }
  50% {
    -webkit-transform: translateY(10px);
  }
  100% {
    -webkit-transform: translateY(0);
  }
}
@-moz-keyframes scroll {
  0% {
    -moz-transform: translateY(0);
  }
  50% {
    -moz-transform: translateY(10px);
  }
  100% {
    -moz-transform: translateY(0);
  }
}
@keyframes scroll {
  0% {
    -webkit-transform: translateY(0);
    -moz-transform: translateY(0);
    -ms-transform: translateY(0);
    -o-transform: translateY(0);
    transform: translateY(0);
  }
  50% {
    -webkit-transform: translateY(10px);
    -moz-transform: translateY(10px);
    -ms-transform: translateY(10px);
    -o-transform: translateY(10px);
    transform: translateY(10px);
  }
  100% {
    -webkit-transform: translateY(0);
    -moz-transform: translateY(0);
    -ms-transform: translateY(0);
    -o-transform: translateY(0);
    transform: translateY(0);
  }
}

.center-it {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  top: 90%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -moz-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  -o-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}

.caption {
  margin-top: 10px;
  color: #ffffff;
}

.mouse {
  display: inline-block;
  height: 44px;
  width: 28px;
  border-radius: 12px;
  border: 2px solid #ffffff;
  text-align: center;
}
.mouse:after {
  display: inline-block;
  height: 8px;
  width: 8px;
  background-color: #ffffff;
  border-radius: 50%;
  content: "";
  -webkit-animation: scroll 1.3s ease-out infinite forwards;
  -moz-animation: scroll 1.3s ease-out infinite forwards;
  animation: scroll 1.3s ease-out infinite forwards;
}
</style>
