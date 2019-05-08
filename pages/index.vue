<template>
  <main class="main">
    <section class="section">
      <div class="container">
        <div class="content">
          <div id="splash">
            <div id="left" class="about">
              <h1>Let's enjoy with Mona！</h1>
              <p>MonaWalletはシンプルなモナコインウォレットです。<br>手軽にモナコインの送金、受け取りが出来ます。</p><br>
              <div id="description">
                <p> 本アプリは「プロ生ちゃんアプリ開発支援プログラム」を利用し提供しています。<br>
                  アプリに関する一切のお問い合わせは合同会社プロ生ではなく、
                  <a href="https://discordapp.com/invite/tQ2NpJ5">MonaWalletDevTeam</a>までお願いします。
                </p>
                <br>
              </div>
              <div id="appstore">
                <a href="https://itunes.apple.com/us/app/monawallet/id1343235820?mt=8&amp;uo=4">
                  <img class="appstore" src="~/assets/appstore.svg" alt="Download on the Apple App Store">
                </a>
              </div>
            </div>
            <div id="right">
              <div>
                <img src="~/assets/iphone.png">
              </div>
            </div>
          </div>
        </div>
        <div id="description-mobile">
          <p>
            本アプリは「プロ生ちゃんアプリ開発支援プログラム」を利用してアプリを提供しています。<br>
            アプリに関するお問い合わせは合同会社プロ生ではなく、<a href="https://discordapp.com/invite/tQ2NpJ5">MonaWalletDevTeam</a>までお願いします。
          </p>
          <br>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  fetch({store}) {
    store.commit('resetMenu')
  },
}
</script>