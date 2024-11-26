<script setup>

</script>

<template>
  <section>
    <div class="wrapper">
      <div class="main">
        <div class="main-text">
          <p class="main-text__sale">
            <span>75% SAVE</span>
            For the Black Friday weekend
          </p>
          <h1 class="main-text__title">
            Fastest and secure platform to invest in crypto
          </h1>
          <p class="main-text__description">
            Buy and sell cryptocurrencies, trusted by 10M wallets with over $30 billion in transactions.
          </p>
          <a href="#" class="main-text__link">
            Try for FREE
          </a>
        </div>
        <div class="main-img">
          <img src="@/assets/images/main.svg" alt="" class="main-img__image">
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="stat">
        <div class="stat-item">
          <div class="stat-item__icon stat-item__icon--01"></div>
          <p class="stat-item__text">
            <span>$30B</span>
            Digital Currency Exchanged
          </p>
        </div>
        <div class="stat-item">
          <div class="stat-item__icon stat-item__icon--02"></div>
          <p class="stat-item__text">
            <span>10M+</span>
            Trusted Wallets Investor
          </p>
        </div>
        <div class="stat-item">
          <div class="stat-item__icon stat-item__icon--03"></div>
          <p class="stat-item__text">
            <span>195</span>
            Countries Supported
          </p>
        </div>
      </div>
    </div>
    <div class="wrapper">
      <div class="text">
        <h2 class="text__title">
          Check how much you can earn
        </h2>
        <p class="text__description">
          Let’s check your hash rate to see how much you will earn today, Exercitation veniam consequat sunt nostrud amet.
        </p>
      </div>
      <div class="calc-head">
        <input type="text" class="calc-head__input" placeholder="Enter your hash rate">
        <select class="calc-head__select">
          <option value="th">TH/s</option>
          <option value="ph">PH/s</option>
          <option value="eh">EH/s</option>
        </select>
        <button class="calc-head__btn" type="submit">Calculate</button>
      </div>
      <div class="page-light">
        <div class="calc-foot">
          <p class="calc-foot__title">
            ESTIMATED 24 HOUR REVENUE:
          </p>
          <p class="calc-foot__total">
            0.055 130 59 ETH
            <span>($1275)</span>
          </p>
          <p class="calc-foot__description">
            Revenue will change based on mining difficulty and Ethereum price.
          </p>
        </div>
        <div class="wrapper">
          <h2 class="page-light__title">
            Trade securely and market the high growth cryptocurrencies.
          </h2>
          <div class="crypto">
            <div class="crypto-item">
              <img src="@/assets/images/btc.svg" alt="BTC">
              <p class="crypto-item__title">
                Bitcoin
                <sup>BTC</sup>
              </p>
              <p class="crypto-item__description">
                Digital currency in which a record of transactions is maintained.
              </p>
              <a class="crypto-item__btn" href="#">
                <span class="crypto-item__btn-text">Start&nbsp;mining</span>
                <span class="crypto-item__btn-icon"></span>
              </a>
            </div>
            <div class="crypto-item">
              <img src="@/assets/images/eth.svg" alt="ETH">
              <p class="crypto-item__title">
                Ethereum
                <sup>ETH</sup>
              </p>
              <p class="crypto-item__description">
                Digital currency in which a record of transactions is maintained.
              </p>
              <a class="crypto-item__btn" href="#">
                <span class="crypto-item__btn-text">Start&nbsp;mining</span>
                <span class="crypto-item__btn-icon"></span>
              </a>
            </div>
            <div class="crypto-item">
              <img src="@/assets/images/ltc.svg" alt="LTC">
              <p class="crypto-item__title">
                Litecoin
                <sup>LTC</sup>
              </p>
              <p class="crypto-item__description">
                Digital currency in which a record of transactions is maintained.
              </p>
              <a class="crypto-item__btn" href="#">
                <span class="crypto-item__btn-text">Start&nbsp;mining</span>
                <span class="crypto-item__btn-icon"></span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="page-gradient">
      <div class="wrapper">
        <div class="form">
          <div class="form-text">
            <h3 class="form-text__title">
              Start mining now
            </h3>
            <p class="form-text__description">
              Join now with CRAPPO to get the latest news and start mining now
            </p>
          </div>
          <div class="form-letter">
            <input type="text" class="form-letter__input" placeholder="Enter your email">
            <button class="form-letter__btn" type="submit">Subscribe</button>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <p class="footer-text">
        &copy;2021 CRAPPO. All rights reserved
      </p>
      <ul class="footer-list">
        <li class="footer-list__item">
          <a href="#" target="_blank">
            <img src="@/assets/images/social-networks/fb.svg" alt="">
          </a>
        </li>
        <li class="footer-list__item">
          <a href="#" target="_blank">
            <img src="@/assets/images/social-networks/in.svg" alt="">
          </a>
        </li>
        <li class="footer-list__item">
          <a href="#" target="_blank">
            <img src="@/assets/images/social-networks/inst.svg" alt="">
          </a>
        </li>
        <li class="footer-list__item">
          <a href="#" target="_blank">
            <img src="@/assets/images/social-networks/tw.svg" alt="">
          </a>
        </li>
        <li class="footer-list__item">
          <a href="#" target="_blank">
            <img src="@/assets/images/social-networks/yt.svg" alt="">
          </a>
        </li>
      </ul>
    </footer>
  </section>
</template>

<style scoped>
.wrapper {
  max-width: 1202px;
  padding-right: 15px;
  padding-left: 15px;
  margin: 0 auto;
}
.main {
  display: flex;
  align-items: center;
  margin-top: 61px;
}
.main-text {
  flex: 0 0 600px;
}
.main-text__sale {
  background-color: rgba(var(--white-rgb), 0.1);
  display: inline-block;
  padding: 10px 12px 10px 4px;
  border-radius: 32px;
  margin: 0;
}
.main-text__sale span {
  background-color: var(--white);
  color: var(--dark);
  padding: 6px 19px;
  border-radius: 32px;
  margin-right: 13px;
  font-weight: 500;
}
.main-text__title {
  font-size: 64px;
  font-weight: 700;
  margin-top: 26px;
  line-height: 1.2;
  margin-bottom: 24px;
}
.main-text__description {
  color: var(--light-gray);
  line-height: 1.6;
  max-width: 400px;
  margin-bottom: 57px;
}
.main-text__link {
  color: var(--white);
  background-color: var(--blue);
  padding: 20px 30px;
  border-radius: 32px;
  font-weight: 500;
  text-decoration: none;
  transition: .2s ease background-color;
}
.main-text__link:hover {
  background-color: var(--purple);
}
.main-img {
  flex-grow: 1;
}
.main-img__image {
  width: 100%;
}
.stat {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 200px;
  padding-bottom: 196px;
}
.stat-item {
  display: flex;
  align-items: center;
}
.stat-item__icon {
  background-color: rgba(var(--white-rgb), 0.1);
  flex: 0 0 80px;
  width: 80px;
  height: 80px;
  border-radius: 100%;
  margin-right: 24px;
  background-repeat: no-repeat;
  background-position: center center;
}
.stat-item__icon--01 {
  background-image: url("@/assets/images/icon01.svg");
}
.stat-item__icon--02 {
  background-image: url("@/assets/images/icon02.svg");
}
.stat-item__icon--03 {
  background-image: url("@/assets/images/icon03.svg");
}
.stat-item__text {
  color: var(--light-gray);
  margin: 0;
}
.stat-item__text span {
  display: block;
  font-size: 40px;
  font-weight: 700;
  color: var(--white);
  margin-bottom: 15px;
}
.text {
  text-align: center;
  padding-bottom: 60px;
}
.text__title {
  font-size: 40px;
  font-weight: 700;
}
.text__description {
  color: var(--light-gray);
  font-size: 18px;
  line-height: 1.5;
  max-width: 630px;
  margin: 0 auto;
}
.calc-head {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #FBFCFE;
  border-radius: 16px 16px 0 0;
  max-width: 942px;
  margin: 0 auto;
  padding: 47px 46px;
  box-sizing: border-box;
}
.calc-head__input {
  font-size: 20px;
  color: var(--dark);
  border: none;
  border-bottom: 1px solid var(--light-gray);
  flex-grow: 1;
  padding: 12px 0;
}
.calc-head__input:focus {
  outline: none;
}
.calc-head__input::placeholder {
  color: var(--dark);
}
.calc-head__select {
  font-size: 20px;
  color: var(--dark);
  border: none;
  border-bottom: 1px solid var(--light-gray);
  flex: 0 0 200px;
  margin-right: 48px;
  margin-left: 48px;
  appearance: none;
  background-image: url("@/assets/images/arrow-select.svg");
  background-repeat: no-repeat;
  background-position: 98% 18px;
  padding: 12px 0;
}
.calc-head__select:focus {
  outline: none;
}
.calc-head__btn {
  font-size: 18px;
  color: var(--white);
  background-color: var(--blue);
  padding: 19px 0;
  border-radius: 32px;
  font-weight: 500;
  text-decoration: none;
  transition: .2s ease background-color;
  border: none;
  flex: 0 0 146px;
}
.calc-head__btn:hover {
  background-color: var(--purple);
}
.page-light {
  background-color: #F8F9FB;
  color: var(--dark);
  padding-bottom: 100px;
}
.page-light__title {
  font-size: 40px;
  font-weight: 700;
  text-align: center;
  max-width: 741px;
  margin: 0 auto;
  line-height: 1.5;
}
.calc-foot {
  max-width: 942px;
  margin: 0 auto;
  padding: 53px 46px;
  background-color: var(--white);
  border-radius: 0 0 16px 16px;
  box-sizing: border-box;
  margin-bottom: 105px;
}
.calc-foot__title {
  font-size: 16px;
  font-weight: 500;
  color: var(--blue);
  margin: 0;
}
.calc-foot__total {
  font-size: 32px;
  font-weight: 700;
  color: #000000;
  margin-top: 25px;
  margin-bottom: 14px;
}
.calc-foot__total span {
  color: var(--blue);
}
.calc-foot__description {
  font-size: 16px;
  color: #828282;
  margin: 0;
}
.crypto {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  text-align: center;
  margin-top: 57px;
}
.crypto-item {
  background-color: var(--white);
  color: var(--dark);
  border-radius: 16px;
  flex: 0 0 31%;
  padding: 52px 30px 47px;
  box-sizing: border-box;
  transition: .2s ease background-color, .2s ease color;
}
.crypto-item:hover {
  background-color: var(--purple);
  color: var(--white);
}
.crypto-item__title {
  font-size: 32px;
  font-weight: 700;
  margin-top: 47px;
  margin-bottom: 21px;
}
.crypto-item__title sup {
  font-size: 18px;
  font-weight: 500;
  color: #BDBDBD;
}
.crypto-item__description {
  font-size: 16px;
  color: #828282;
  line-height: 1.7;
  transition: .2s ease color;
  margin-bottom: 25px;
}
.crypto-item:hover .crypto-item__description {
  color: var(--white);
}
.crypto-item__btn {
  background-color: var(--white);
  font-size: 18px;
  color: var(--white);
  text-decoration: none;
  border-radius: 32px;
  padding: 0 15px;
  display: flex;
  align-items: center;
  justify-content: center;
  max-width: 205px;
  margin: 0 auto;
  transition: .2s ease background-color;
}
.crypto-item:hover .crypto-item__btn {
  background-color: var(--blue);
}
.crypto-item__btn-text {
  font-size: 18px;
  font-weight: 500;
  width: 0;
  transition: .2s ease width;
}
.crypto-item:hover .crypto-item__btn-text {
  width: 133px;
}
.crypto-item__btn-icon {
  background-color: var(--white);
  width: 64px;
  height: 64px;
  display: block;
  border-radius: 100%;
  background-image: url("@/assets/images/arrow.svg");
  background-repeat: no-repeat;
  background-position: center center;
  border: 2px solid rgba(var(--purple-rgb), 0.2);
  transform: scale(1);
  transition: .2s ease border, .2s ease transform;
}
.crypto-item:hover .crypto-item__btn-icon {
  border: 2px solid var(--white);
  transform: scale(0.5);
}
.page-gradient {
  background: linear-gradient(180deg, var(--purple) 0%, var(--dark) 100%);
  padding-top: 88px;
  padding-bottom: 88px;
}
.form {
  background-color: var(--blue);
  border-radius: 16px;
  display: flex;
  justify-content: space-between;
  padding: 54px 50px;
}
.form-text {
  flex-grow: 1;
}
.form-text__title {
  margin-top: 0;
  font-size: 32px;
  font-weight: 700;
  margin-bottom: 27px;
}
.form-text__description {
  font-size: 16px;
  margin-bottom: 0;
  max-width: 348px;
  line-height: 1.5;
}
.form-letter {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex: 0 0 566px;
}
.form-letter__input {
  font-size: 16px;
  border: none;
  border-bottom: 1px solid var(--white);
  background-color: transparent;
  color: var(--white);
  width: 100%;
  margin-right: 40px;
  padding: 10px 0;
}
.form-letter__input::placeholder {
  color: var(--white);
}
.form-letter__btn {
  border: none;
  background-color: var(--white);
  color: var(--dark);
  font-size: 18px;
  font-weight: 500;
  padding: 18px 32px;
  border-radius: 32px;
}
</style>