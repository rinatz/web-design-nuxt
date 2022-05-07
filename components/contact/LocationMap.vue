<template>
  <section id="location">
    <div class="wrapper">
      <div class="location-info">
        <h3 class="sub-title">カフェ東駅前店</h3>
        <p>
          住所：東京都〇〇区<br />
          〇〇〇〇〇〇〇 000-22-1<br />
          電話：03-1111-1111<br />
          営業時間：10:00〜20:00<br />
          休日：水曜
        </p>
      </div>
      <div class="location-map">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3240.827853398546!2d139.76493611532845!3d35.6812405375787!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188bfbd89f700b%3A0x277c49ba34ed38!2z5p2x5Lqs6aeF!5e0!3m2!1sja!2sjp!4v1651937211080!5m2!1sja!2sjp"
          width="800" height="400" style="border:0;" allowfullscreen="false" loading="lazy"
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
      </div>
    </div>
  </section>
</template>

<style scoped>
#location {
  padding: 4% 0;
}

#location .wrapper {
  display: flex;
  justify-content: space-between;
}

.location-info {
  width: 22%;
}

.location-info p {
  padding: 12px 10px;
}

.location-map {
  width: 74%;
}

iframe {
  widows: 100%;
}
</style>
