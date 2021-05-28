<template>
  <Layout>
    <div class="columns">
      <div class="column is-two-fifths">
        <p class="is-size-3 has-text-weight-bold">Xoori</p>
        <div class="columns">
          <div class="column">
            <g-image
              alt="Xoori"
              src="~/assets/images/xoori-avatar.jpg"
              width="250"
              height="250"
            />
          </div>
          <div class="column">
            <p>
              Non-Binary<br />
              They/Them/Theirs<br />
              "24" Years Old<br />
              Utah<br />
              United States
            </p>
          </div>
        </div>
        <div class="columns">
          <div class="column">
            <nav class="panel">
              <p class="panel-heading">Xoori's Links</p>
              <div class="columns">
                <div class="column">
                  <a class="panel-block is-active">
                <span class="panel-icon">
                  <i class="fab fa-tiktok" aria-hidden="true"></i>
                </span>
                @Xoori555
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fab fa-twitter" aria-hidden="true"></i>
                </span>
                @Xoori555
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fab fa-instagram" aria-hidden="true"></i>
                </span>
                @Xoori555
              </a>
                </div>
                <div class="column">
                  <a class="panel-block">
                <span class="panel-icon">
                  <i class="fas fa-magic" aria-hidden="true"></i>
                </span>
                Book a Reading
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fab fa-discord" aria-hidden="true"></i>
                </span>
                Join the Xeeds Server
              </a>
              <a class="panel-block">
                <span class="panel-icon">
                  <i class="fab fa-amazon" aria-hidden="true"></i>
                </span>
                Amazon Wishlist
              </a>
                </div>
              </div>
            </nav>
          </div>
        </div>
      </div>
      <div class="column is-three-fifths">
        <div class="box">
          <p class="is-size-4 has-text-centered">
            Xoori is doing private Readings!
          </p>
        </div>
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">Xoori's Latest Blog Entry</p>
          </header>
          <div class="card-content">
            <div class="content">
              <ul class="no-bullets">
                <li>Blog One... (<a href="#">view more</a>)</li>
                <li>Blog Two... (<a href="#">view more</a>)</li>
                <li>Blog Starseed... (<a href="#">view more</a>)</li>
                <li>Blog Tarot... (<a href="#">view more</a>)</li>
                <li>Blog Oracle... (<a href="#">view more</a>)</li>
                <li>[<a href="#">View All Blog Entries</a>]</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
ul.no-bullets {
  list-style-type: none; /* Remove bullets */
  padding: 0; /* Remove padding */
  margin: 0; /* Remove margins */
}

ul.no-bullets > li:first-of-type {
  padding-bottom: 5px;
}

ul.no-bullets > li:not(:first-of-type) {
  padding-top: 5px;
  padding-bottom: 5px;
}
</style>
