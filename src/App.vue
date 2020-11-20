<template>
  <div id="app">
    <div class="wrapper">
      <header class="king-header" :class="isOpen ?'bg-black': 'bg-transparent'">
        <nav class="king-nav">
          <div class="king-logo">
            <img src="./assets/logo-king.png" alt="">
          </div>
          <div class="button-responsive">
            <button
                @click="isOpen = !isOpen">
              <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>
                Menu</title>
                <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/>
              </svg>
            </button>
          </div>
          <div :class="isOpen ? 'block' : 'hidden'" class=" w-full block flex-grow lg:flex lg:items-center lg:w-auto">
            <div class="text-sm lg:flex-grow">
            </div>
            <div>
              <a href="#responsive-header"
                 class="block mt-4 lg:inline-block lg:mt-0 text-yellow-500 text-xl text-bold hover:text-white mr-5">
                Commission
              </a>
              <a href="#responsive-header"
                 class="block mt-4 lg:inline-block lg:mt-0 text-yellow-500 text-xl text-bold hover:text-white mr-5">
                Login
              </a>
              <a href="#responsive-header"
                 class="block mt-4 lg:inline-block text-xl text-bold lg:mt-0 text-yellow-500 hover:text-white mr-5">
                Register
              </a>
            </div>
          </div>
        </nav>
      </header>
      <!--===================== Header ========================-->
      <!--===================== End of Header ========================-->
      <!--===================== Banner ========================-->
      <div class="king-banner">
        <div class="king-banner-text">
          <div class="king-banner-title">
            <span>FAST ONLINE TRADING </span>
          </div>
          <div class="king-banner-desc">
            <div>
              <p>
                We did our best to bring you a powerful toolkit for your intraday and global
                endeavors. Pick the type of option the best suits your trading style and profitability
                expectant
              </p>
            </div>
            <div>
              <p>
                A multichart layout, technical analysis, historical quotes and beyond. Everything you're
                looking for in a platforms -- on the device of your choice.
              </p>
            </div>
          </div>
          <div class="king-banner-button">
            <button>TRADE NOW</button>
          </div>
        </div>

      </div>

      <div class="king-banner-static">
        <div class="king-col-static">
          <div class="static-number">
            <span>1000+</span>
          </div>
          <div class="static-tetx">
            <span>Trading Instruments</span>
          </div>
        </div>
        <div class="king-col-static">
          <div class="static-number">
            <span>0.6</span>
          </div>
          <div class="static-tetx">
            <span>Spreads as low as 0.6 pips</span>
          </div>
        </div>
        <div class="king-col-static">
          <div class="static-number">
            <span>888:1</span>
          </div>
          <div class="static-tetx">
            <span>Leverage</span>
          </div>
        </div>
        <div class="king-col-static">
          <div class="static-number">
            <span>$500</span>
          </div>
          <div class="static-tetx">
            <span>Bonus</span>
          </div>
        </div>
      </div>
      <!--===================== End of Banner ========================-->
      <!--===================== Reasons Block ========================-->
      <div class="king-reason">
        <div class="king-container">
          <div class="king-reason-logo">
            <img src="./assets/logo-king.png" alt="">
          </div>
          <div class="king-reason-row">
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason1.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Personal Account Managers</span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason6.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Free Access to Market Research </span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason9.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Free Access to Daily Webinars</span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason2.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Unlimited Access to Video Tutorials</span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason5.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Daily Access to Trading Signals</span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason8.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Diversity Platforms to Choose From</span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason3.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Free Daily Technical Analysis</span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason6.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>Free Access to Market Research </span>
              </div>
            </div>
            <div class="king-reason-col">
              <div class="king-reason-icon">
                <img src="./assets/icon-reason7.png" alt="">
              </div>
              <div class="king-reason-text">
                <span>24/7 Hour Live Help</span>
              </div>
            </div>
          </div>
        </div>

      </div>
      <!--===================== End of Reasons Block ========================-->
      <!--===================== philosophy Block ========================-->
      <div class="king-platforms">
        <div class="container">
          <div class="king-platforms-title">
            <span>The ULTIMATE Platforms at your disposal</span>
          </div>
          <div class="king-platforms-desc">
            <p>Our trading platforms offer you a world-class trading experience with numerous features and
              tolls
              that suit your trading style</p>
          </div>
        </div>

        <div class="king-platform-feature">
          <div class="king-platforms-feature-title">
            <span>Key Features</span>
          </div>
          <div class="king-feature-row">
            <div class="king-feature-col">
              <div class="king-feature-col-icon">
                <img src="./assets/icon-right.png" alt="">
              </div>
              <div class="king-feature-col-text">
                <span>Advanced charting and analytical tools</span>
              </div>
            </div>
            <div class="king-feature-col">
              <div class="king-feature-col-icon">
                <img src="./assets/icon-right.png" alt="">
              </div>
              <div class="king-feature-col-text">
                <span>Sophisticated order management tools</span>
              </div>
            </div>
            <div class="king-feature-col">
              <div class="king-feature-col-icon">
                <img src="./assets/icon-right.png" alt="">
              </div>
              <div class="king-feature-col-text">
                <span>Trade from your desktop or mobile device</span>
              </div>
            </div>
            <div class="king-feature-col">
              <div class="king-feature-col-icon">
                <img src="./assets/icon-right.png" alt="">
              </div>
              <div class="king-feature-col-text">
                <span>Trade from your desktop or mobile device</span>
              </div>
            </div>
          </div>
        </div>
        <div class="king-platform-device">
          <div>
            <img src="./assets/icon-platform-1.png" alt="">
          </div>
          <div>
            <img src="./assets/icon-platform-2.png" alt="">
          </div>
          <div>
            <img src="./assets/icon-platform-3.png" alt="">
          </div>
        </div>
      </div>
      <!--===================== End of philosophy Block ========================-->
      <!--===================== king option Block ========================-->
      <div class="king-option">
        <div class="king-option-row">
          <div class="king-option-left">
            <img src="./assets/icon-earth.png" alt="">
          </div>
          <div class="king-option-right">
            <div class="king-option-right-title">
              <span>Why trade with</span>
              <span>King Option</span>
            </div>
            <div class="king-option-right-row">
              <div class="king-option-right-col">
                <div class="option-right-col-img">
                  <img src="./assets/icon-option1.png" alt="">
                </div>
                <div class="option-right-col-text">
                  <div class="text-title">
                    <span>Powerful and competitive</span>
                  </div>
                  <div class="text-desc">
                    <p>
                      Industry leading trading conditions designed to take your trading to next level.
                    </p>
                  </div>
                </div>
              </div>

              <div class="king-option-right-col">
                <div>
                  <img src="./assets/icon-option2.png" alt="">
                </div>
                <div class="option-right-col-text">
                  <div class="text-title">
                    <span>Powerful and competitive</span>
                  </div>
                  <div class="text-desc">
                    <p>
                      Industry leading trading conditions designed to take your trading to next level.
                    </p>
                  </div>
                </div>
              </div>

              <div class="king-option-right-col">
                <div>
                  <img src="./assets/icon-option3.png" alt="">
                </div>
                <div class="option-right-col-text">
                  <div class="text-title">
                    <span>Powerful and competitive</span>
                  </div>
                  <div class="text-desc">
                    <p>
                      Industry leading trading conditions designed to take your trading to next level.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!--===================== End of king option Block ========================-->
      <!--===================== King Ready ========================-->
      <div class="king-ready">
        <div class="king-container-ready">
          <div class="king-ready-title">
            <span>Ready to TRADE?</span>
          </div>
          <div class="king-ready-col">
            <div class="king-ready-icon">
              <div>
                <img src="./assets/icon-ready-1.png" alt="">
              </div>
              <div class="king-ready-text">
                <span>Sign Up</span>
                <p>Sign up for a skilling account in just a matter of minutes </p>
              </div>
            </div>
            <hr>
            <div class="king-ready-icon">
              <div>
                <img src="./assets/icon-ready-2.png" alt="">
              </div>
              <div class="king-ready-text">
                <span>Verify Your ID</span>
                <p>Verify your ID by uploading your documents or by registering with BankID </p>
              </div>
            </div>
            <hr>
            <div class="king-ready-icon">
              <div>
                <img src="./assets/icon-ready-3.png" alt="">
              </div>
              <div class="king-ready-text">
                <span>Start Trading</span>
                <p>Fund your account and start trading on the world's financial markets</p>
              </div>
            </div>
          </div>
          <div class="king-ready-button">
            <button>Start Trading</button>
          </div>
        </div>

      </div>
      <!--===================== End of King Ready ========================-->
      <!--===================== King Broker ========================-->
      <div class="king-broker">
        <div class="king-container-broker">
          <div class="king-broker-title">
            <div>Choose a Big, Fair and Human Broker. </div>
          </div>
          <div class="king-broker-desc">
            <p>There us a reason why over 3.5 Million Client Choose ACB for Forex Trading, Stock Indices
              Trading, Commodity Trading, Stock, Metals and Energies Trading</p>
          </div>

          <div class="king-broker-row">
            <div class="king-broker-col">
              <div class="king-broker-icon">
                <img src="./assets/icon-broker1.png" alt="">
              </div>
              <div class="king-broker-text">
                <div class="king-broker-text-title">
                  <span>Licensed and Regulated Broker</span>
                </div>
                <div class="king-broker-text-desc">
                  <p>
                    XM Group is licensed by ASIC in Australia (Trad-ing Point of Financial Instruments
                    Pty
                    Limited), the IFSC in Belize (XM Global Limited) and by CySEC in Cyprus (Trading
                    Point
                    of Financial In-struments Ltd), adhering to enhanced regulato-ry standards
                  </p>
                </div>
              </div>
            </div>

            <div class="king-broker-col">
              <div class="king-broker-icon">
                <img src="./assets/icon-broker5.png" alt="">
              </div>
              <div class="king-broker-text">
                <div class="king-broker-text-title">
                  <span>Globally Renowned</span>
                </div>
                <div class="king-broker-text-desc">
                  <p>
                    We have clients from over 196 countries and staff speaking over 30 languages. Our
                    management has visited over 120 cities globally to understand clients' and partners'
                    needs.
                  </p>
                </div>
              </div>
            </div>

            <div class="king-broker-col">
              <div class="king-broker-icon">
                <img src="./assets/icon-broker2.png" alt="">
              </div>
              <div class="king-broker-text">
                <div class="king-broker-text-title">
                  <span>Focused on the Client</span>
                </div>
                <div class="king-broker-text-desc">
                  <p>
                    Size does not matter. At XM the client comes first regardless of net capital worth,
                    account type or size of investment. All our clients receive the same quality
                    services, the same execution, and the same level of support. XM was founded on these
                    values, and that will not change.
                  </p>
                </div>
              </div>
            </div>

            <div class="king-broker-col">
              <div class="king-broker-icon">
                <img src="./assets/icon-broker4.png" alt="">
              </div>
              <div class="king-broker-text">
                <div class="king-broker-text-title">
                  <span>Range of Trading Instruments</span>
                </div>
                <div class="king-broker-text-desc">
                  <p>
                    Our clients can choose to trade forex and CFDS on stock indices, commodities,
                    stocks, metals and energies from the same trading account. With a wide range of
                    trading instruments available from a single multi asset platform XM makes trading
                    easier and efficient.
                  </p>
                </div>
              </div>
            </div>

            <div class="king-broker-col">
              <div class="king-broker-icon">
                <img src="./assets/icon-broker3.png" alt="">
              </div>
              <div class="king-broker-text">
                <div class="king-broker-text-title">
                  <span>Transparent and Fair</span>
                </div>
                <div class="king-broker-text-desc">
                  <p>
                    At XM what you see is what you get, with no hidden terms. Be that pricing, execution
                    or pro- motions. What we advertise is what we give our clients, regardless of the
                    size of their investment.
                  </p>
                </div>
              </div>
            </div>

            <div class="king-broker-col">
              <div class="king-broker-icon">
                <img src="./assets/icon-broker6.png" alt="">
              </div>
              <div class="king-broker-text">
                <div class="king-broker-text-title">
                  <span>Easy and Convenient</span>
                </div>
                <div class="king-broker-text-desc">
                  <p>
                    All our systems are built and updated with the client in mind. Starting from our
                    account opening procedure, to managing your account, depositing or withdrawing funds
                    and finally trading, it's all straightforward simple and easy to use for all our
                    clients.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!--===================== End of King Broker ========================-->
      <!--===================== Footer ========================-->
      <footer class="king-footer">
        <!--===================== Copyright ========================-->
        <div class=" text-center">
          <span> &copy; Coppy Right 2020</span>
        </div>
        <!--===================== End of Copyright ========================-->
      </footer>
      <!--===================== End of Footer ========================-->
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  // components: {
  //   HelloWorld
  // }
  data() {
    return {
      isOpen: false,
    }
  },
}
</script>
