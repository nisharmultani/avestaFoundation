<template>
  <div>
    <b-navbar >
      <b-navbar-brand href="#">NavBar</b-navbar-brand>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item active href="#">Home</b-nav-item>
          <b-nav-item-dropdown text="Pages">
            <b-dropdown-item href="#">About US</b-dropdown-item>
            <b-dropdown-item href="#">Founder Message</b-dropdown-item>
            <b-dropdown-item href="#">FAQ</b-dropdown-item>
            <b-dropdown-item href="#">Our Impect</b-dropdown-item>
            <b-dropdown-item href="#">Bourd of Directer</b-dropdown-item>
            <b-dropdown-item href="#">Become a volunteer</b-dropdown-item>
            <b-dropdown-item href="#">privacy Policy</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item href="#">Events</b-nav-item>
          <b-nav-item href="#">Causes</b-nav-item>
          <b-nav-item href="#">OurBlog</b-nav-item>
          <b-nav-item href="#">Recognition</b-nav-item>
          <b-nav-item href="#">Appreciation</b-nav-item>
          <b-nav-item href="#">Contact Us</b-nav-item>
                    <b-button  size="sm" class="my-2 my-sm-0" type="submit">Donate Now</b-button>

        </b-navbar-nav>
      </b-collapse>

    </b-navbar>
  </div>
</template>
<style scoped>
.item{
    color: black;
}
</style>
