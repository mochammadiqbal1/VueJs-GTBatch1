<template>
    <div>
        <div class="d-flex justify-content-around mt-5 mb-5 ">
        <img alt="bs4.html" src="../assets/logo.png" width="134" height="35" style="border-radius: 20px">
    </div>
    
    <div class="d-flex justify-content-around mb-5">
        <div class="d-flex flex-column">
            <h4>Overview</h4>
            <a href="" style="text-decoration: none; color:black;">Shipping</a>
            <a href="" style="text-decoration: none; color:black;">Refund</a>
            <a href="" style="text-decoration: none; color:black;">Promotion</a>
        </div>
        <div class="d-flex flex-column">
            <h4>Company</h4>
            <a href="" style="text-decoration: none; color:black;">About</a>
            <a href="" style="text-decoration: none; color:black;">Career</a>
            <a href="" style="text-decoration: none; color:black;">Contuct Us</a>
        </div>
        <div class="d-flex flex-column">
            <h4>Explorer</h4>
            <a href="" style="text-decoration: none; color:black;">Terms & Couns</a>
            <a href="" style="text-decoration: none; color:black;">Privacy Policy</a>
            <a href="" style="text-decoration: none; color:black;">For Developer</a>
        </div>
        
        <form class="form-inline my-2 my-lg-0" id="formEmail">
          <input class="form-control mr-sm-2" id="inputNama" type="email" name="email" placeholder="Your Email Address" required>
          <button type="submit" id="btnAlert" class="btn"><img src="../assets/cart-icon.png"
                  alt="icon" style="background-color: pink; padding: 5px;"></button>
      </form>
    </div>
    </div>
</template>

<script>
export default {
    name:'FooterTo'
}
</script>