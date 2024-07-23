<template>
    <div class="footer">
        <div id="services">
            <div>
            <h3>Services</h3>
            <a href="">website Design</a>
            <a href="">Ecommerece Website</a>
            <a href="">Portfolio Website</a>
            </div>
           
            <div id="support-us">
            <img src="@/assets/github.png" alt="">
            <img src="@/assets/fblogo.png" alt="">
            <img src="@/assets/linkedin.webp" alt="" id="last">
         

        </div>
   

        
        </div>
        <div id="contact-us">
            <div>
            <h3>Contact Us</h3>
            <p>Email:</p>  <a href="mailto:smajeesh3@gmail.com">smajeesh3@gmail.com</a>
            <p>Contact Us:<a href="">877876575334</a></p>
            </div>


        </div>
       
        <div id="feedback">
            <form action="">
                <input type="text" placeholder="Name">
                <input type="email" placeholder="Email">
                <input type="email" placeholder="Contact Number">
                <textarea name="" id="" cols="60" rows="5" placeholder="Feedback"></textarea>
                <input type="submit" name="" id="">

            </form>
        </div>
       
    </div>
    
    
    
</template>

<script>
export default {
    name:"FooterBar"
   
}
</script>


<style>
*
{
    margin: 0px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-transform: capitalize;
    
}
.footer
{
    color:green;
    display: flex;
    justify-content: space-between;
    background-color: rgb(10, 10, 10);
    padding: 20px 0px 0px 50px;
   
}

.footer h3
{
    margin-bottom: 20px;
    font-size: 1.6em;
}

 a{
    display: block;
    text-decoration: none;
    color:rgb(184, 183, 183);
    margin: 20px 0px;
    
}
#services a{
    margin: 40px 0px;
}
#services
{
    flex:1;
    align-self: center;
    display:flex;
    flex-direction: column;
    justify-content:space-between;
}
#contact-us
{
    flex:1;
    padding:20px;
}
#feedback
{
    flex:1.3;
    justify-self: center;
    align-self: center;
  
}

a:hover{
    color:green;
    width:fit-content;
    border-bottom: 2px solid green;
    transition: .5s;
}

#support-us img{
    border-radius: 50%;
    width:40px;
    margin-left: 15px;
}
input{
    display: block;
    width: 70%;
    border: none;
    outline: none;
    border-bottom: 2px solid green;
    background-color: black;
    color: white;
    padding: 10px 0px;
    margin-bottom: 18px;
}
textarea
{
    border: 2px solid green;
    background-color: black;
}
input[type="submit"]
{
    margin: 10px 0px;
    border:2px solid green;
    background-color: rgb(5, 92, 5);
    letter-spacing: 2px;
}
@media (max-width: 768px) {
  .footer {
    flex-direction: column;
  }
  #services, #support-us, #contact-us, #feedback {
    margin-bottom: 20px;
    align-self: center;
  }
  input, textarea {
    width: 100%;
  }
}

</style>