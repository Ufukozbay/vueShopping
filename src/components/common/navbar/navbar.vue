<template>
  <div id="navbar" class="container">
    <div class="navbar-logo">
        <p>LOGO</p>
    </div>
    <div class="navbar-menu">
        <ul class="navbar-links">
            <li><a href="#">HOME</a></li>
            <li><a href="#">PAGES</a></li>
            <li><a href="#">SHOP</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">BLOG</a></li>
            <li><a href="#">CONTACT</a></li>
        </ul>
    </div>
    <div class="navbar-carts">
        <ul>
            <li class="navbar-carts-item">
                <a href="#">CARTS</a>
            </li>
        </ul>
    </div>
  </div>
</template>

<script>
export default {
    name:"navbar"
}
</script>

<style>
#navbar{
    position: sticky;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: black ;
    height:auto;
    width: 100%;
    padding: 2rem 2%;
}
   .navbar-logo{
        background-color: #3a4a5a;;
        height:50px;
        width: 75px;
        display: flex;
        cursor: pointer;
        align-items: center;
        justify-content: center;
}
    .navbar-links{
        list-style: none;
    }
        .navbar-links li {
        display: inline-block;
        padding: 0 20px;
        }
            .navbar-links li a{
                text-decoration: none;
                transition: all 0.3s ease 0s;
                color: gainsboro;
            }
            .navbar-links li a:hover {
                color: #0088a9;   
            }   
.navbar-carts-item {
    list-style: none;
}
    .navbar-carts-item a {
        padding: 9px 25px;
        border-radius: 30px;
        text-decoration: none;
        background-color: rgba(0, 136, 169, 1);
        color: gainsboro;
    }
    .navbar-carts-item a:hover{
        transition: all 0.5s ease 0s;
        color: #3a4a5a;
    }
   

       
    
</style>