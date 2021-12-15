<template>
  <footer>
    <!--FOOTER UP-->
    <div class="footerUp">
      <div class="container">
        <div>
          <ul>
            <li><a href="#"> dc comics</a></li>
            <li><a href="#"> characters </a></li>
            <li><a href="#"> comics </a></li>
            <li><a href="#"> movies </a></li>
            <li><a href="#"> tv </a></li>
            <li><a href="#"> games</a></li>
            <li><a href="#"> videos</a></li>
            <li><a href="#"> news</a></li>
          </ul>

          <ul>
            <li><a href="#"> shop </a></li>
            <li><a href="#"> shop DC </a></li>
            <li><a href="#"> shop DC Collectibles </a></li>
          </ul>
        </div>

        <div>
          <ul>
            <li><a href="#"> dc </a></li>
            <li><a href="#"> Terms of Use </a></li>
            <li><a href="#"> Privacy policy (New) </a></li>
            <li><a href="#"> Ad Choices </a></li>
            <li><a href="#"> Advertising </a></li>
            <li><a href="#"> Jobs</a></li>
            <li><a href="#"> Subscriptions</a></li>
            <li><a href="#"> Talent Workshops</a></li>
            <li><a href="#"> CPSC Certificates </a></li>
            <li><a href="#"> Ratings </a></li>
            <li><a href="#"> Shop Help </a></li>
            <li><a href="#"> Contact Us </a></li>
          </ul>
        </div>

        <div>
          <ul>
            <li><a href="#"> sites </a></li>
            <li><a href="#"> DC </a></li>
            <li><a href="#"> MAD Magazine </a></li>
            <li><a href="#"> DC Kids </a></li>
            <li><a href="#"> DC Universe </a></li>
            <li><a href="#"> DC Power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
    <!--///FOOTER UP-->

    <!--FOOTER DOWN-->
    <div class="footerDown">
      <div class="container">
        <div class="sx">SIGN-UP NOW!</div>

        <div class="dx">
          FOLLOW US
          
            <a href="#">
              <img src="../../assets/img/footer-facebook.png" alt="fb" />
            </a>

            <a href="#">
              <img src="../../assets/img/footer-twitter.png" alt="tw" />
            </a>

            <a href="#">
              <img src="../../assets/img/footer-youtube.png" alt="yt" />
            </a>

            <a href="#">
              <img src="../../assets/img/footer-pinterest.png" alt="pn" />
            </a>

                        <a href="#">
              <img src="../../assets/img/footer-periscope.png" alt="pe" />
            </a>
          
        </div>
      </div>
    </div>
    <!--///FOOTER DOWN-->
  </footer>
</template>



<script>
export default {
  name: "Footer",
};
</script>


<style lang='scss' scoped>
footer {
  height: 500px;
  background-color: rgb(53, 53, 53);

  font-family: Arial, Helvetica, sans-serif;
  .footerUp {
    background-image: url("../../assets/img/footer-bg.jpg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;



    .container {
      height: 400px;

      padding:50px;

      display: flex;

          display: flex;
    align-items: flex-start;

      ul {
        list-style: none;
        margin-bottom: 15px;

        li a {
          display: inline-block;
          padding: 0 20px 5px 0;
          text-decoration: none;
          color: rgba(255, 255, 255, 0.5);
          font-size: 14px;
        }

        li:first-child a {
          color: white;
          text-transform: uppercase;
          font-weight: bold;
          font-size: 20px;
          padding: 5px 50px 10px 0;
        }
      }
    }
  }

  .footerDown {
    .container {
      height: 100px;
      display: flex;
      justify-content: space-around;
      align-items: center;
    }

    .sx {
      color: white;
      padding: 10px;
      border: 3px solid #0282f9;
      font-weight: bold;
    }

    .dx {
display: flex;
align-items: center;
      color: #0282f9;
      font-weight: bold;

      a {
          padding: 10px;
      }
    }
  }
}
</style>