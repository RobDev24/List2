<template>

 <div id="nav">
  <div class="navigation">

    <nav>
      <ul>

        <li class="dropdown">
          <a href="">Menu</a>

          <div class="dropdown-menu">
            <a href="">home</a>
            <a href="">Seviços</a>
            <a href="">Contato</a>
            </div>

        </li>
      </ul>

    </nav>

  </div>
 </div>
</template>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

nav{
  background-color: blue;
}

nav li{
display: inline-block;
margin-left: 94%;

}

nav li a{
  display: inline-block;
  color: aliceblue;
  text-decoration: none;
  padding: 15px;
}

nav li a:hover{
  background-color: blueviolet;
}

.dropdown-menu{
  position: absolute;
  box-shadow: 0 0 2px black;
  display: none;
}
.dropdown-menu a{
  display: block;
  color: black;
  }

  .dropdown:hover .dropdown-menu{
    display: block;
  }
</style>