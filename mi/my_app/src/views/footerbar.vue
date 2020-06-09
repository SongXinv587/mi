<template>
  <footer>
    <ul>
      <li>
        <a href>
          <div></div>
        </a>
      </li>
      <li>
        <a href>
          <img src alt />
        </a>
      </li>
      <li>
        <a href>
          <img src alt />
        </a>
      </li>
      <li>
        <a href>
          <img src alt />
        </a>
      </li>
      <li>
        <a href>
          <img src alt />
        </a>
      </li>
    </ul>
  </footer>
</template>

<style lang="less">
footer {
  height: 52px;
  background: #fff;
  border: 0.5px solid #999;
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  box-sizing: border-box;
  //   padding: 10px 0;
  box-sizing: border-box;
  z-index: 999;
  ul {
    display: flex;
    // margin: 15px 0;
    justify-content: space-around;
    text-align: center;
    li {
    //   height: 20px;
    //   width: 20px;
      flex: 1;
      &:nth-child(1) {
        background: url(.././assets/imgs/houselogo.png) no-repeat;
        background-size: cover;
      }
    }
  }
}
</style>
<script>
// import navbox from "./components/navbox.vue"
// export default {
//     components:{
//         // navbox
//     }
// }
</script>
