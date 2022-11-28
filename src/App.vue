<template>
  <div id="app">
    <Navbar></Navbar>
    <BreadCrumb></BreadCrumb>
    <Galley></Galley>
    <Slider></Slider>
    <Card></Card>
    <Footer></Footer>
    <Copyright></Copyright>
  </div>
</template>

<script>
import Copyright from './components/CopyrightComponent.vue'
import Footer from './components/FooterComponent.vue'
import Card from './components/CardComponent.vue'
import Slider from './components/SliderComponent.vue'
import Galley from './components/GalleyComponent.vue'
import BreadCrumb from './components/BreadcrumbComponent.vue';
import Navbar from './components/NavbarComponent.vue';


export default {
  name:'app',
  components: {
    Navbar,
    BreadCrumb,
    Galley,
    Slider,
    Card,
    Footer,
    Copyright
  }
}
</script>

<style>


#soal {
    border-style: ridge;
    background-color: grey;
    padding-top: 20px;
    padding-bottom: 20px;
}

.container {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin-top: 30px;
    margin-bottom: 30px;
}


p {
    height: 40px;
    width: 40px;
    margin: 20px auto;
    border-radius: 7px;
}


    .coba {
        display: flex;
        flex-direction: row;
        /* width: 350px;
        height: 350px;
        padding: 60px; */
        justify-content: center;
    }

.kiri {
    width: 100px;
    padding: 40px;
}

.tengah {
    flex: 40%;
    width: 500px;
    
    padding: 20px;
    
}

.kanan {
    flex: 30%;
    width: 200px;
    margin-left: 10px;
}

.list-footer {
    display: flex;
    justify-content: space-around;
}

.list-footer a {
    color:black;
    text-decoration: none;
}

.bold {
    font-weight: bold;
}

.list-footer .item {
    display: flex;
    flex-direction: column;
}

footer {
    text-align: center;
    background-color: grey;
    padding-top: 10px;
    padding-bottom: 10px;
}


</style>
