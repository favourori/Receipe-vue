<template>
  <div>
    <nav class="light-blue darken-4 z-depth-0">
      <div class="nav-wrapper container">
        <a href="#" class="brand-logo"><img src="@/assets/recipe-book.png" width="45"></a>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
          <li>
            <a href="sass.html">Add recipe</a>
          </li>
                <li>
            <a href="sass.html">About</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
.brand-logo > span,.brand-logo > img{
   vertical-align: middle;
}
</style>