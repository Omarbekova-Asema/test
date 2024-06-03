<script setup lang="ts">
import { ref, onMounted } from "vue";


onMounted(() => {
  chartData.value = setChartData();
  chartOptions.value = setChartOptions();
});

const chartData = ref();
const chartOptions = ref(null);

const setChartData = () => {
  const documentStyle = getComputedStyle(document.body);

  return {
    labels: ['A', 'B', 'C'],
    datasets: [
      {
        data: [540, 325, 702],
        backgroundColor: [documentStyle.getPropertyValue('--cyan-500'), documentStyle.getPropertyValue('--orange-500'), documentStyle.getPropertyValue('--gray-500')],
        hoverBackgroundColor: [documentStyle.getPropertyValue('--cyan-400'), documentStyle.getPropertyValue('--orange-400'), documentStyle.getPropertyValue('--gray-400')]
      }
    ]
  };
};

const setChartOptions = () => {
  const documentStyle = getComputedStyle(document.documentElement);
  const textColor = documentStyle.getPropertyValue('--text-color');

  return {
    plugins: {
      legend: {
        labels: {
          cutout: '60%',
          color: textColor
        }
      }
    }
  };
};

const items = ref([
  {    label: 'Jan 20 - Feb 26',
    description: '67% Bonus67% Bonus $0.0000/Token'  },
  {    label: 'Jan 20 - Feb 26',
    description: '$0.0000/Token67% Bonus $0.0000/Token'  },
  {    label: 'Jan 20 - Feb 26',
    description: '67% Bonus $0.0000/Token'  },
  {    label: 'Jan 20 - Feb 26',
    description: '67% Bonus $0.0000/Token'  },
  {    label: 'Jan 20 - Feb 26',
    description: '67% Bonus $0.0000/Token'  }
])
</script>
<template>
<div class="aaa">
  <div class="container">
    <div class="big-text d-flex justify-content-between ">
      <div class="big1">
        <ul>
          <li>guido</li>
        </ul>
      </div>
      <div class="big2 ">
        <ul>home</ul>
        <ul>home</ul>
        <ul>home</ul>
        <ul>home</ul>
        <ul>home</ul>
        <ul>home</ul>
        <ul>home</ul>
      </div>
      <div class="big3 d-flex">
        <button style=" width:80px;height:35px ; background: #3772FF; border: 1px solid ; border-radius: 20px;">Sign up</button>
        <button style="margin-left:10px; width:80px;height:35px ; color: white ;background: none; ; border-radius: 20px ">Login</button>
      </div>
    </div>
  </div>
  <div style="width: 100%; border: 2px solid aliceblue; "></div>
  <div class="container">
    <h1 class="text1 mt-5">The World’s 1st ICO Platform That
      Offers Rewards Contributors</h1>
    <p class="text2">jkdbkfnlvnln slndlnkldnvjb Sdfnndlvlja bjlbjbldbvlblb lbvsbfbfbd fbbv bdvbd</p>
    <div class="raw">
      <div class="coll d-flex flex-column">
        <h3 style="color: white">Pre-sale is Live Now</h3>
        <div class="square mt-3">
          <div class="col-square ">
            <div class="col-square1" style="background: #888888;color: floralwhite; border-radius: 5px"><h6 class="col-square-text" style="color: floralwhite">32</h6></div>
            <div class="col-square2 " style="color: floralwhite">copy</div>
          </div>
          <div class="col-square ">
            <div class="col-square1" style="background: #888888;color: floralwhite; border-radius: 5px"><h6 class="col-square-text" style="color: floralwhite">16</h6></div>
            <div class="col-square2 " style="color: floralwhite">copy</div>
          </div>
          <div class="col-square ">
            <div class="col-square1" style="background: #888888;color: floralwhite; border-radius: 5px"><h6 class="col-square-text" style="color: floralwhite">48</h6></div>
            <div class="col-square2 " style="color: floralwhite">copy</div>
          </div>
          <div class="col-square ">
            <div class="col-square1" style="background: #888888;color: floralwhite; border-radius: 5px"><h6 class="col-square-text" style="color: floralwhite">05</h6></div>
            <div class="col-square2 " style="color: floralwhite">copy</div>
          </div>
        </div>
      </div>
      <div class="row-line"></div>
      <div class="bb">
        <h3 style="color: white">Pre-sale </h3>
        <div style="display:flex;" class="bb-line d-flex mt-4">
          <div class="line1" style="  background: floralwhite; height:45px; width: 1px; ">
            <p class="bb-line-text1"  style="margin-top: 43px; margin-left: -15px">Low</p>
          </div>
          <div class="line-2" style="background: floralwhite; height:45px; width: 1px;; ">
            <p class="bb-line-text1"  style="margin-top: 43px; margin-left: -29px">Medium</p>
          </div>
          <div class="line-3" style="background: floralwhite; height: 45px; width: 1px;">
            <p class="bb-line-text1"  style="margin-top: 43px; margin-left: -15px">High</p>
          </div></div>
      </div>
    </div>
    <button  style="margin-left: 35%;margin-top: 40px;border: none;border-radius: 50px; background: #224ACC;width: 200px;height: 50px">Purchase tokens</button>
  </div>
</div>
<section>
  <div class="section2" style="">
    <div class="container">
      <div class="row">
        <p style="padding-top:40px;color:white" class="row-text1">____WHAT IS ICO CRYPTO</p>
        <h2 class="row-text2" style="padding-top:10px; color:beige">We’ve built a platform to <br>
          buy and sell shares</h2>
        <div style="margin-top:120px" class="row-big-div">
          <div class="row-div1" style=";text-align: center ; justify-content: center; align-items: center">
            <div class="row-div1-radius" style="display:flex; justify-content: center; align-items: center; text-align: center; background: #224ACC; border-radius: 50px; width: 50px;height: 50px">
              <img src="/public/img/Vector%20(9).svg" alt="">
            </div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>

            <div class="row-div1-radius" style="display: flex;justify-content: center;align-items: center; background: #224ACC; border-radius: 50px; width: 50px;height: 50px">
              <img src="/public/img/Vector%20(10).svg" alt="">
            </div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>
            <div class="aa" style="padding: 1px; margin: 5px; margin-left: 23px "></div>

            <div class="row-div1-radius" style="display: flex; align-items: center; justify-content: center; background: #224ACC; border-radius: 50px; width: 50px;height: 50px">
              <img src="/public/img/Vector%20(11).svg" alt="">
            </div>
          </div>
          <div class="row-div2 " style="">
            <div class="row-div2_div1 " style=" margin-top:-47px;margin-left: 20px">
              <h5 class="row-big-div-text5 " style="color: white">Decentralized Platform</h5>
              <p style="color:white">The process of taking into account the
                collective option of group</p></div>

            <div class="row-div2_div1 mb-5 " style="margin-top: 55px;margin-left: 20px">
              <h5 class="row-big-div-text5 mb-3 m" style="color: white">Decentralized Platform</h5>
              <p style="color:white">The process of taking into account the
                collective option of group</p></div>

            <div class="row-div2_div1 "  style="margin-top: 70px; margin-left: 20px">
              <h5 class="row-big-div-text5" style="color: white">Decentralized Platform</h5>
              <p style="color:white">The process of taking into account the
                collective option of group</p></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<section>
  <div class="section3" style=" width: 100%;height: 500px;background: #050023;">
    <div class="container">
      <h6 style="color: white;font-size: 16px; padding-top:40px; margin-bottom:70px"> ________WHAT IS ICO CRYPTO</h6>
      <div style=" align-items: center; justify-content: space-between;display:flex" class="row">
        <div class="section3-col">
          <div class="card" style="background: #D9D9D905;">
            <div class="card-img-div" style=" margin-left:15px;align-items:center; justify-content: center; background: #3772FF; width: 60px; height: 60px; border-radius:5px">
              <img style=" margin-top:15px;  margin-left:5px;  width: 50px ;height: 30px;" src="/public/img/Vector%20(5).svg" class="card-img-top" alt="...">
            </div>
            <div class="card-body">
              <h5 style="color:white ;font-size: 24px;" class="card-title">Card title</h5>
              <p style="color:white " class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
            </div>
          </div>
        </div>
        <div class="section3-col">
          <div class="card" style="background: #D9D9D905;">
            <div class="card-img-div" style=" margin-left:15px;align-items: center;justify-content: center; background: #E031CA;width: 60px; height: 60px; border-radius:5px">
              <img style=" margin-top:15px; margin-left:5px; width: 50px; height: 30px;" src="/public/img/Vector%20(4).svg" class="card-img-top" alt="...">
            </div>
            <div class="card-body">
              <h5 style="color:white; font-size: 24px; " class="card-title">Card title</h5>
              <p style="color:white " class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
            </div>
          </div>
        </div>
        <div class="section3-col">
          <div class="card" style="background: #D9D9D905;">
            <div class="card-img-div" style=" margin-left:15px; align-items: center; justify-content: center; background: #E031CA;width: 60px; height: 60px; border-radius:5px">
              <img style=" margin-top:15px;  margin-left:4px; width: 50px ;height: 30px;color: white " src="/public/img/Vector%20(7).svg" class="card-img-top" alt="...">
            </div>
            <div class="card-body">
              <h5 style="color:white;font-size: 24px; " class="card-title">Card title</h5>
              <p style="color:white" class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
            </div>
          </div>
        </div>
        <div class="section3-col">
          <div class="card" style="background: #D9D9D905;">
            <div class="card-img-div" style="margin-left:15px;align-items: center; justify-content: center; background: #FFCB2F; width: 60px; height: 60px; border-radius:5px">
              <img style=" margin-top:15px; margin-left:5px;   width: 50px ;height: 30px;" src="/public/img/Vector%20(12).svg" class="card-img-top" alt="...">
            </div>
            <div class="card-body">
              <h5 style="color:white;font-size: 24px; " class="card-title">Card title</h5>
              <p style="color:white" class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<section>
  <div class="section5" style=" background: #050023;  width: 100%; height: 900px;">
    <div class="container">
      <div class="asfas p-5"></div>
      <div style="" class="section5-row">
        <div class="section4-div1 d-flex" style="">
          <h2 style="color:white">1 CNL = 0.0013 BTC</h2>
          <button style=" border-radius:20px; margin-left:50px ;width: 140px;height: 45px; background:#224ACC; color:#ffffff; ">Buy Now</button>
        </div>
      </div>
      <div class="steps1 flex align-items-center justify-content-center" style="height:550px; background: #201F3A; border-radius:30px">
        <div class="steps-big-div mr-6" style=" text-align:center;justify-content:center; display:flex; flex-direction: column;">
          <div class="steps1-div1" style="display:flex; ">
            <div class="steps1-div1-small" style="margin-top:22px; margin-right:20px; background:#888888; width:20px; height:20px; border-radius:50%"></div>
            <h4>Active Foun...     45,00%</h4>
          </div>
          <div class="steps1-div2" style="display:flex;">
            <div class="steps1-div1-small" style="margin-top:22px; margin-right:20px; background:#3772FF; width:20px; height:20px; border-radius:50%"></div>
            <h4>Active Foun...     38,00%</h4>
          </div>
          <div class="steps1-div3" style="display:flex ; ">
            <div class="steps1-div1-small" style="margin-top:22px; margin-right:20px;background:#FFCB2F; width:20px; height:20px; border-radius:50%"></div>
            <h4>Active Foun...     18,00%</h4>
          </div>
        </div>
        <Chart type="doughnut" :data="chartData" :options="chartOptions" class="w-full md:w-30rem" />
      </div>
    </div>
  </div>
</section>

</template>
<style scoped>

.section3-col{
  width:25%
}
.big-text{
  display:flex;
  justify-content: space-between;
}
.section2{
  background-image: url("public/img/Rectangle 65.svg");
  width: 100%;
  height: 800px;
  background-repeat: no-repeat;
  background-position: center;
}
.row-big-div{
  display:flex;
}
.aa{
  width: 3px;
  height: 10px;
  background: #224ACC;
}
.row-div1-radius{
  margin-top:-33px;
}
.bba{
  width: 10px;
  height: 1px;
  background: white;
}
.aaa{
  background: #050023;
  width: 100%;
  height: 800px;
}
.container{
  width: 1140px !important;
  margin: 0 auto;
}
ul{
  color:beige;
}
.big2{
  justify-content: center;
  align-items: center;
  display:flex;
  margin-left: 150px;
}
.big1{
  display:flex;
  justify-content: center;
  align-items: center;
  padding: 15px;
}
.big3{
  display:flex;
  justify-content: center;
  align-items: center;
}
.text1{
  font-family: Inter;
  font-size: 52px;
  font-weight: 600;
  line-height: 87.14px;
  text-align: center;
}
.text2{
  font-family: Inter;
  font-size: 24px;
  font-weight: 600;
  line-height: 29.05px;
  text-align: center;
}
h1{
  color: white;
}
h5{
  color: white;
}

.raw{
  display: flex;
  justify-content: space-around;
  margin-top: 80px;
}
.square{
  display: flex;
  align-items: center;
}
.col-square{
  margin-left: 10px;
  text-align: center;
  justify-content: center;
  align-items: center; ;
}
.row-line{
  height: 200px;
  width: 1px;
  background: #C6C6C6;
}
.bb-line{
  width: 420px;
  height: 20px;
  border-radius: 10px;
  justify-content: space-around;
  background: #D9D9D94D;
  background: #224ACC;
}
.col-square-text{
  padding: 15px;
}

.footer{  background-color: #050023;
  background-repeat: no-repeat;
  height: auto;
  display: flex;
  align-items: center;
}

.p-steps .p-steps-item:before{  top: 17%;
  border-top: 3px dashed rgba(136, 136, 136, 0.45);}

.section6-col{
  width: 33.0000%;

}
</style>