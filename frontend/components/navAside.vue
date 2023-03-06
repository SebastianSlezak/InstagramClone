<template>
  <aside>
    <div class="logo">
      <img src="@/assets/img/logoInstagram.svg" alt="logo Instagram">
    </div>

    <div>
      <div>
        <img src="@/assets/img/face.jpg" alt="profile">
        <span>Mario Sanitario</span>
        <span>Cracow, Poland</span>
      </div>
      <div>
        <div>
          <span>578</span>
          <span>posts</span>
        </div>
        <div>
          <span>37.7k</span>
          <span>followers</span>
        </div>
        <div>
          <span>153</span>
          <span>following</span>
        </div>
      </div>
    </div>

    <div>
      <ul>
        <li>
          <nuxt-link to="/">
            <nuxt-icon name="feed"/>
            Feed
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/explore">
            <nuxt-icon name="explore"/>
            Explore
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/myfavorites">
            <nuxt-icon name="bookmark"/>
            My Favorites
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/direct">
            <nuxt-icon name="direct"/>
            Direct
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/stats">
            <nuxt-icon name="stats"/>
            Stats
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/setting">
            <nuxt-icon name="setting"/>
            Setting
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/logout">
            <nuxt-icon name="logout"/>
            Log out
          </nuxt-link>
        </li>
      </ul>
    </div>
  </aside>
</template>

<style scoped>

aside {
  display: flex;
  flex-direction: column;
}

</style>