<script setup></script>

<template>
  <header>
    <div class="header__top">
      <div class="container">
        <a href="../../index.html" class="logo">
          <img src="../../public/images/logo.svg" alt="header-logo">
        </a>

        <nav class="header__nav">
          <ul>
            <li class="link_active"><a href="#">Games</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Terms of Use</a></li>
            <li><a href="#">About</a></li>
          </ul>
        </nav>

        <div class="btns-container">
          <a href="#" class="btn">Sign up</a>
          <a href="#" class="btn main-btn">Log in</a>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="header__banner">
        <h1>awesome html5 games <br> - NO MONEY!</h1>
        <h2>Your perfect place to get some <br> fun and excitement</h2>
        <div class="btns-container">
          <a href="#" class="btn second-btn">Log in</a>
          <a href="#" class="btn main-btn">Play</a>
        </div>

        <form action="#" class="registration-form">
          <div class="form__row">
            <h3>Create a free account now</h3>

            <ul class="advantages">
              <li class="advantage _games">
                <img src="../../public/images/icons/dice.png" alt="dice">1000+ Games <br> available
              </li>
              <li class="advantage _newGame">
                <img src="../../public/images/icons/slot.png" alt="slot">New game <br> Every week
              </li>
              <li class="advantage _support">
                <img src="../../public/images/icons/24h.png" alt="time">Support our <br> users 24/7
              </li>
            </ul>
          </div>
          <div class="form__row _info">
            <label class="_short">
              <input type="text" placeholder="Firstname">
            </label>
            <label class="_short">
              <input type="text" placeholder="Lastname">
            </label>
            <label>
              <input type="email" placeholder="Email Address">
            </label>
            <button type="submit" class="submit-btn main-btn">Join Now</button>
          </div>
          <label class="privacy">
            <input type="checkbox" name="privacy" value="agree-with-privacy">
            <span>I accept the <a href="#">Privacy Policy</a></span>
          </label>
        </form>
      </div>
    </div>
  </header>

  <main>
    <div class="container">
      <section>
        <h2 class="section__header">Our Games</h2>
        <h3 class="section__subtitle _long">
          Get Virtual Welcome bonus after Sign Up <a href="#">All games</a>
        </h3>

        <div class="games">
          <div class="games__container">
            <a href="#" class="game">
              <picture>
                <img src="../../public/images/games/DoubleJackpot.jpg" alt="DoubleJackpotImg">
              </picture>
              <h4 class="game__title">Double Jackpot</h4>
              <h5 class="game__creator">NetentGames</h5>
            </a>

            <a href="#" class="game">
              <picture>
                <img src="../../public/images/games/AllAboardDynamate.jpg" alt="AllAboardDynamateImg">
              </picture>
              <h4 class="game__title">All Aboard: Dynamic super game</h4>
              <h5 class="game__creator">RushGameStudio</h5>
            </a>

            <a href="#" class="game">
              <picture>
                <img src="../../public/images/games/BookOfTombs.jpg" alt="BookOfTombsImg">
              </picture>
              <h4 class="game__title">Book Of Tombs</h4>
              <h5 class="game__creator">NetentGames</h5>
            </a>

            <a href="#" class="game">
              <picture>
                <img src="../../public/images/games/Rudolph’sRide.jpg" alt="Rudolph’sRideImg">
              </picture>
              <h4 class="game__title">Rudolph’s Ride</h4>
              <h5 class="game__creator">NetentGames</h5>
            </a>

            <a href="#" class="game">
              <picture>
                <img src="../../public/images/games/StarburstXXXtreme.jpg" alt="StarburstXXXtremeImg">
              </picture>
              <h4 class="game__title">Starburst XXXtreme</h4>
              <h5 class="game__creator">StarBurst Inc.</h5>
            </a>

            <a href="#" class="game">
              <picture>
                <img src="../../public/images/games/BlackDiamond.jpg" alt="BlackDiamond">
              </picture>
              <h4 class="game__title">Black Diamond</h4>
              <h5 class="game__creator">RushGameStudio</h5>
            </a>
          </div>

          <div class="games__container _big">
            <div class="game _full">
              <h4 class="game__title">Dynamite Riches <br> Megaways</h4>
              <h5 class="game__description">Miners revealed a gain of €46,672 for Sandra M.! You too, dynamite
                the reels of the Red Tiger Daily Jackpot machines</h5>
              <a href="#" class="play-game-btn">Play now</a>
            </div>
            <div class="game _full">
              <h4 class="game__title">Gator Gold Deluxe <br> Gigablox</h4>
              <h5 class="game__description">These swamps conceal many dangers but especially precious
                treasures. Will you be able to find them?</h5>
              <a href="#" class="play-game-btn">Play now</a>
            </div>
            <div class="game _span2">
              <picture>
                <img src="../../public/images/Our-deals-are-not-to-be-missed.jpeg" alt="OurDealsImg">
              </picture>
              <h4 class="game__title">Our deals are not to be missed</h4>
              <h5 class="game__creator">Discover a wide range of weekly promotions</h5>
              <a href="#" class="read-more play-game-btn">Read more</a>
            </div>
          </div>
        </div>

        <p class="footnote">
          * We don't offer opportunities to play for real money. Our games are free demo. All games were invented
          <br>
          for entertainment purposes only and do not offer real money prizes.
        </p>
      </section>

      <section class="form__section">
        <h2 class="section__header">Contact us</h2>
        <h3 class="section__subtitle">
          If you have some questions, send us a message
        </h3>

        <form action="#" class="contact-form">
          <label>
            <input type="text" placeholder="Firstname">
          </label>
          <label>
            <input type="text" placeholder="Email Address">
          </label>
          <label>
            <textarea name="message" placeholder="Your message here..."></textarea>
          </label>

          <div class="form__row">
            <label class="privacy">
              <input type="checkbox" name="privacy" value="agree-with-privacy">
              <span>I accept the <a href="#">Privacy Policy</a></span>
            </label>

            <button type="submit" class="main-btn">Send</button>
          </div>
        </form>
      </section>
    </div>
  </main>

  <footer>
    <div class="container">
      <nav>
        <ul class="footer__nav">
          <li><a href="#">Disclaimer</a></li>
          <li><a href="#">Privacy Policy</a></li>
          <li><a href="#">Terms of Conditions</a></li>
        </ul>
      </nav>

      <p class="footer__text">
        This site does not provide any form of online gambling and delivers information for entertainment and
        research purposes only. The games listed by Topwinningslots are intended for adult audience entertainment
        (underage visitors are restricted) and do not offer real money or prizes. Practicing online free games does
        not imply future success at 'real money' gambling.
      </p>

      <div class="footer__bottom">
        <span class="rights">2022 | &#169; Lorem Inc. All Rights Reserved</span>
        <ul class="social">
          <li><a href="#" class="icon _twitter"><img src="../../public/images/icons/twitter.svg" alt="twitter-icon"></a></li>
          <li><a href="#" class="icon _facebook"><img src="../../public/images/icons/facebook.svg" alt="facebook-icon"></a></li>
          <li><a href="#" class="icon _instagram"><img src="../../public/images/icons/instagram.svg" alt="instagram-icon"></a></li>
        </ul>
      </div>
    </div>
  </footer>
</template>