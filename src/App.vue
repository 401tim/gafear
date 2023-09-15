<script setup>
import { ref } from 'vue'

const nameInput = ref(''); 
const contactInput = ref(''); 
const dateTimeInput = ref('');
</script>

<template>
    <body>
      <center>
      <header class="d-flex flex-wrap justify-content-center py-3 mb-4 b" style="width:100%;background-color:rgb(106, 21, 21);" data-v-b1549e9f=""><a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto link-body-emphasis text-decoration-none" data-v-b1549e9f="">
        <svg class="bi me-2" width="50" height="70" data-v-b1549e9f="">
          <use xlink:href="#bootstrap" data-v-b1549e9f="">
          </use>
        </svg>
        <span class="fs-3" style="color:white;" data-v-b1549e9f="">
          <h2 data-v-b1549e9f="">จองโต๊ะร้านอาหาร</h2>
        </span>
      </a>
    </header>
      </center>
        <br>
      <div id="app" data-v-app="">
        <div class="container">
          <div class="col"><div class="card" style="width:100%;">
            <img src="/img/1.jpg" class="card-img-top" alt="/img/1.jpg">
    <div class="card-body">
      <h5 class="card-title">Lumpocha ลำโพชะ</h5>
      <p class="card-text">สามชั้นย่างชิ้นหนาๆ สันคอหมักเกลือ และหมูหมักสูตรพิเศษ เสิร์ฟพร้อมกับน้ำจิ้มน้ำมันงาและซอสเกาหลี แถมยังมาพร้อมกับเครื่องเคียงครบชุด และไข่ตุ๋นแบบฟูๆ เด้งๆ อีกด้วย ที่สำคัญร้านนี้ยังมีบิงซุให้ตบท้ายกินดับคาวอีกด้วยน้า
        <br>💸บุฟเฟ่ต์ราคา 299 บาท
      </p>
      <hr>
      <div class="input-group flex-nowrap">
        <span class="input-group-text" id="addon-wrapping">จองโต๊ะ</span>
        <input type="number" class="form-control" placeholder="โปรดระบุจำนวน" aria-label="number" aria-describedby="addon-wrapping" min="0">
      </div>
    </div>
  </div>
          </div>
          <div class="col"><div class="card" style="width:100%;">
            <img src="/img/2.jpg" class="card-img-top" alt="/img/2.jpg">
    <div class="card-body">
      <h5 class="card-title"> Tengoku + Yaki Nimman 5</h5>
      <p class="card-text">ร้านที่มีทั้งบุฟเฟ่ต์ปิ้งย่าง และบุฟเฟ่ต์อาหารญี่ปุ่น ร้านนี้จะพิเศษตรงที่ว่าบุฟเฟ่ต์จะแบ่งเป็นรอบๆ ไป หากใครอยากไปทานอาหารที่ร้านนี้ขอแนะนำให้สำรองที่นั่ง ไม่ว่าจะอาหารญี่ปุ่น หรือปิ้งย่าง
        <br> 💸 บุฟเฟ่ต์อาหารญี่ปุ่น 1000 บาท net 
        <br>💸 บุฟเฟ่ต์ปิ้งย่าง 555 บาท net
      </p>
      <hr>
     <div class="input-group flex-nowrap">
        <span class="input-group-text" id="addon-wrapping">จองโต๊ะ</span>
        <input type="number" class="form-control" placeholder="โปรดระบุจำนวน" aria-label="number" aria-describedby="addon-wrapping" min="0">
      </div>
    </div>
    </div>
          </div>
          <div class="col"><div class="card" style="width:100%;">
            <img src="/img/3.jpg" class="card-img-top" alt="/img/3.jpg">
    <div class="card-body">
      <h5 class="card-title">Kobe King Japanese BBQ Restaurant </h5>
      <p class="card-text">ร้านปิ้งย่างสไตล์ญี่ปุ่นที่บอกได้เลยว่าเนื้อของร้านนี้เกรดพรีเมียมสุดๆ  ใบพายพรีเมี่ยม,เนื้อเต๋าพรีเมี่ยม, คารุบิพรีเมี่ยม, ร่องซี่โครงพรีเมี่ยม ฟินสุดๆ ใครเป็นสายรักเนื้อมาเชียงใหม่ต้องไม่พลาดร้านนี้ กินบุฟเฟ่ต์เนื้อแบบจุกๆ กันไปเลย
        <br>💸 บุฟเฟ่ต์ราคา 599 บาท / 799 บาท  / 999 บาท
      </p>
      <hr>
      <div class="input-group flex-nowrap">
        <span class="input-group-text" id="addon-wrapping">จองโต๊ะ</span>
        <input type="number" class="form-control" placeholder="โปรดระบุจำนวน" aria-label="number" aria-describedby="addon-wrapping" min="0">
      </div>
    </div>
    </div>
          </div>
          <div class="col"><div class="card" style="width:100%;">
            <img src="/img/4.jpg" class="card-img-top" alt="/img/4.jpg">
    <div class="card-body">
      <h5 class="card-title">Booboosikdang</h5>
      <p class="card-text">ร้านปิ้งย่างเกาหลีสูตรต้นตำรับแท้จากฝีมือของสองสามีภรรยาชาวเกาหลี แถมราคายังเป็นมิตรอีกด้วย บุฟเฟ่ต์มาเสิร์ฟพร้อมชุดผักและเครื่องเคียงทุกอย่าง ที่สำคัญเติมได้ไม่จำกัด ใครที่ชอบทานอาหารเกาหลีต้องร้านนี้เลย
        <br>💸 บุฟเฟ่ต์ราคา 299 บาท 
      </p>
      <hr>
      <div class="input-group flex-nowrap">
        <span class="input-group-text" id="addon-wrapping">จองโต๊ะ</span>
        <input type="number" class="form-control" placeholder="โปรดระบุจำนวน" aria-label="number" aria-describedby="addon-wrapping" min="0">
      </div>
          </div>
        </div>
        </div>
      </div>
    </div>
    <br>
      <center>
      <button id="submitbooking" type="button" class="btn btn-warning" style="color: rgb(0, 0, 0); font-size: 20px;" data-bs-toggle="modal" data-bs-target="#exampleModal">
        ตรวจสอบรายการ</button>
    </center>
   
    <br>
    <div class="formconcon">
      <center>
      <div class="formcon">
        <form action=""><h4>รายละเอียดผู้จอง</h4>
          <div class="input-group mb-3">
            <span class="input-group-text" id="basic-addon1">ชื่อผู้จอง</span>
            <input id="name" type="text" class="form-control" placeholder="ชื่อผู้จอง" aria-label="Username" aria-describedby="basic-addon1" required="" v-model="nameInput">
          </div>
          <div class="row">
            <div class="col">
              <div class="input-group mb-3">
                <span class="input-group-text" id="basic-addon1">เบอร์โทรศัพท์</span>
                <input id="num" class="form-control" type="text" pattern="[0-9]{10}" maxlength="10" placeholder="กรอกเบอร์โทรศัพท์(10หลัก)" aria-label="tel" aria-describedby="basic-addon1" required="" v-model="contactInput">
              </div>
            </div>
            <div class="col">
              <div class="input-group mb-3">
                <span class="input-group-text" id="basic-addon1">วันที่และเวลา
                </span>
                <input id="datetime" min="2023-09-15T20:16" type="datetime-local" class="form-control" aria-label="Datetime" aria-describedby="basic-addon1" required="" v-model="dateTimeInput">
              </div>
            </div>
          </div>
        </form>
        <button type="submit" class="btn btn-warning" style="color: rgb(0, 0, 0); font-size: 20px;">
          ยืนยันการจองโต๊ะ
        </button>
        </div>

        <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h1 class="modal-title fs-5" id="exampleModalLabel">ตรวจสอบรายการ</h1>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <p>ชื่อผู้จอง : {{nameInput}}</p>
                <p>เบอร์โทรศัพท์ : {{contactInput}}</p>
                <p>วันที่และเวลา : {{dateTimeInput}}</p>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary">Save changes</button>
              </div>
            </div>
          </div>
        </div>
      </center>
  </div>
    
    </body>
</template>

<style scoped>
.centered-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* Center vertically within the viewport */
  background-color: rgb(179, 138, 138); /* เพิ่มสีพื้นหลังขาวที่นี่ */
}

.container {
  display: grid;
  grid-template-columns: repeat(2, 2fr);
  gap: 50px;
}

.card {
  width: 100%;
}

.modal-body{
  text-align: left;
}
</style>
