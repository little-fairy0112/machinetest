<template>
  <div class="hello">
    <div class="bg-lightbrown d-flex justify-content-end">
    </div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-brown">
      <div class="container">
        <a class="navbar-brand padding-none" href="#">
          <img src="@/assets/pic/鴻海logo.png" width="180">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
    </nav>

    <section class="bg-lightbrown py-5 text-brown">
      <div class="container">
        <div class="accordion" id="accordionExample">
          <div class="card">
            <div class="card-header" id="headingOne">
              <h2 class="mb-0">
                <button class="btn btn-link btn-block text-left text-brown" type="button" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                  機器名稱/編號：7361836
                </button>
              </h2>
            </div>

            <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordionExample">
              <div class="card-body">
                <table>
                  <tr class="title">
                    <td class="content">
                      ip位址
                    </td>
                    <td class="content">
                      狀態
                    </td>
                  </tr>
                  <tr class="title">
                    <td class="content">
                      10.134.98.XX
                    </td>
                    <td class="content">
                      停用
                    </td>
                  </tr>
                </table>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="card-header" id="headingTwo">
              <h2 class="mb-0">
                <button class="btn btn-link btn-block text-left collapsed text-brown" type="button" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                  機器名稱/編號：7361553
                </button>
              </h2>
            </div>
            <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordionExample">
              <div class="card-body">
                <table>
                  <tr class="title">
                    <td class="content">
                      ip位址
                    </td>
                    <td class="content">
                      狀態
                    </td>
                  </tr>
                  <tr class="title">
                    <td class="content">
                      10.134.98.XX
                    </td>
                    <td class="content">
                      使用中
                    </td>
                  </tr>
                </table>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="card-header" id="headingThree">
              <h2 class="mb-0">
                <button class="btn btn-link btn-block text-left collapsed text-brown" type="button" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                  機器名稱/編號：7366179
                </button>
              </h2>
            </div>
            <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordionExample">
              <div class="card-body">
                <table>
                  <tr class="title">
                    <td class="content">
                      ip位址
                    </td>
                    <td class="content">
                      狀態
                    </td>
                  </tr>
                  <tr class="title">
                    <td class="content">
                      10.134.98.XX
                    </td>
                    <td class="content">
                      停用
                    </td>
                  </tr>
                </table>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="card-header" id="headingFour">
              <h2 class="mb-0">
                <button class="btn btn-link btn-block text-left collapsed text-brown" type="button" data-toggle="collapse" data-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
                  機器名稱/編號：7361553
                </button>
              </h2>
            </div>
            <div id="collapseFour" class="collapse" aria-labelledby="headingFour" data-parent="#accordionExample">
              <div class="card-body">
                <table>
                  <tr class="title">
                    <td class="content">
                      ip位址
                    </td>
                    <td class="content">
                      狀態
                    </td>
                  </tr>
                  <tr class="title">
                    <td class="content">
                      10.134.98.XX
                    </td>
                    <td class="content">
                      使用中
                    </td>
                  </tr>
                </table>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="card-header" id="headingTwo">
              <h2 class="mb-0">
                <button class="btn btn-link btn-block text-left collapsed text-brown" type="button" data-toggle="collapse" data-target="#collapseFive" aria-expanded="false" aria-controls="collapseFive">
                  機器名稱/編號：7361722
                </button>
              </h2>
            </div>
            <div id="collapseFive" class="collapse" aria-labelledby="headingFive" data-parent="#accordionExample">
              <div class="card-body">
                <table>
                  <tr class="title">
                    <td class="content">
                      ip位址
                    </td>
                    <td class="content">
                      狀態
                    </td>
                  </tr>
                  <tr class="title">
                    <td class="content">
                      10.134.98.XX
                    </td>
                    <td class="content">
                      停中
                    </td>
                  </tr>
                </table>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer class="bg-brown text-lightbrown py-3">
      <div class="text-center px-3 " style="list-style: none;">
        <ul class="nondot">
          <li>Copyright © 2022 鴻海科技集團中央資訊 All rights reserved.</li>
        </ul>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<style lang="scss">
@import "@/assets/all";
@import "~bootstrap/scss/bootstrap";
@import "~bootstrap/dist/css/bootstrap.css";
@import "~bootstrap-vue/dist/bootstrap-vue.css";


.btn{
  border: 2px solid #e1dbd1;
}

.form-control{
  border-width: 2px;
}


.header-carousel-item{
  height: 450px;
}

.bg-cover{
  background-size: cover;
  background-position: center center;
}

.bg-brown{
  background-color: #42302d;
}
      
.bg-lightbrown{
  background-color: #e1dbd1;
}

.text-brown{
  color: #42302d;
}

.text-lightbrown{
  color: #e1dbd1;
}

.text-md-brown{
  color: #42302d;
}

.btn-outline-style{
  color: #e1dbd1;
  background-color: #42302d;
}

.btn-outline-style:hover{
  color: #42302d;
  background-color: #e1dbd1;
  border-color: #42302d;
}
      
.position-relative{
  position:relative;
}

.position-absolute{
  position:absolute;
  top:0; 
  bottom: 0;
}

.nopadding {
  padding: 0 !important;
  margin: 0 !important;
}

.nondot {
  list-style-type: none;
  padding-top: 10px;
}

.LeftSize{
  height:400px;
}

.FBsize{
  height:130px;
}

.QRcodeSize{
  height:250px;
}

.font-20{
  font-size:20px;
}

.font-size-small{
  font-size: 8px;
}

.padding-none{
  padding-top: 0px;
  padding-bottom: 0px;
}

.title{
  border:1px solid #42302d;
  padding:10px;
}

.content{
  border:1px solid #42302d;
  padding:10px;
}

@media (min-width: 768px) {
  .text-md-dark{
  color: #42302d;
  }
}

</style>