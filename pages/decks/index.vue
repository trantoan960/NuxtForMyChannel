<template>
  <div>
    <div class="ct">
      <h3>List of your decks:</h3>
      <ul class="decks-list">
        <li>
          <nuxt-link class="deck" to="/decks/1">
            <div class="card deck-card">
              <img
                src="https://img2.pngio.com/intl-word-v601-english-for-mac-english-class-wallpaper-png-1920_1080.png"
                alt="Thumbnail card"
              />
              <div class="card_body">
                <h3>Title card</h3>
                <p>Description card</p>
              </div>
            </div>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link class="deck" to="/decks/2">
            <div class="card deck-card">
              <img
                src="https://img2.pngio.com/intl-word-v601-english-for-mac-english-class-wallpaper-png-1920_1080.png"
                alt="Thumbnail card"
              />
              <div class="card_body">
                <h3>Title card</h3>
                <p>Description card</p>
              </div>
            </div>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link class="deck" to="/decks/3">
            <div class="card deck-card">
              <img
                src="https://img2.pngio.com/intl-word-v601-english-for-mac-english-class-wallpaper-png-1920_1080.png"
                alt="Thumbnail card"
              />
              <div class="card_body">
                <h3>Title card</h3>
                <p>Description card</p>
              </div>
            </div>
          </nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.decks-list {
  li {
    margin-bottom: 1rem;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .deck {
    display: block;
  }
  .deck-card {
    display: flex;
    flex-direction: row;
    height: 250px;
    img {
      width: 250px;
      height: auto;
    }
  }
}
</style>
