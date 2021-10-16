<template>
  <div>
    <b-navbar>
      <b-navbar-brand href="#">NavBar</b-navbar-brand>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item-dropdown text="Pages">
            <b-dropdown-item href="#">About US</b-dropdown-item>
            <b-dropdown-item href="#">Founder Message</b-dropdown-item>
            <b-dropdown-item href="#">Faq</b-dropdown-item>
            <b-dropdown-item href="#">our Impect</b-dropdown-item>
            <b-dropdown-item href="#">Bourd of Directer</b-dropdown-item>
            <b-dropdown-item href="#">Become a volunteer</b-dropdown-item>
            <b-dropdown-item href="#">privacy Poliece</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item href="#">Events</b-nav-item>
          <b-nav-item href="#">Causes</b-nav-item>
          <b-nav-item href="#">OurBlog</b-nav-item>
          <b-nav-item href="#">REcognition</b-nav-item>
          <b-nav-item href="#">Appreciation</b-nav-item>
          <b-nav-item href="#">Contact Us</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
<style scoped>
b-navbar-nav {
  margin-left: 20px;
}
</style>
