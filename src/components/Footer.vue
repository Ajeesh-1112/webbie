<template>
      <div id="support-us">
        <div>
            <p>@WEBBIE!</p>
        </div>
        <div>
            <span>follow us</span>
            <img src="@/assets/github.png" alt="">
            <img src="@/assets/fblogo.png" alt="">
            <img src="@/assets/linkedin.webp" alt="" id="last">
        </div>

        </div>
    <div class="footer">
        <div id="services">
            <div>
            <h3>Services</h3>
            <p>website Design</p>
            <p>Ecommerece Website</p>
            <p>Portfolio Website</p>
            </div>
        </div>
        <div id="contact-us">
            <div>
            <h3>Contact Us</h3>
            <p>Email:</p>  <a href="mailto:smajeesh3@gmail.com">smajeesh3@gmail.com</a>
            <p>Phone Number:</p><a href="">877876575334</a>
            </div>


        </div>
       
        <div id="feedback">
            <form action="">
                <input type="text" placeholder="Name">
                <input type="email" placeholder="Email">
                <input type="email" placeholder="Contact Number">
                <textarea name="" id="" cols="50" rows="3" placeholder="Feedback"></textarea>
                <input type="submit" name="" id="" value="SUBMIT">

            </form>
        </div>
       
    </div>
    <div id="copy-rights">
        <p>copyrights@2024</p>

    </div>
  
    
    
    
</template>

<script>
export default {
    name:"FooterBar"
   
}
</script>


<style scoped>
*
{
    margin:0px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    text-transform: capitalize;
    
}
.footer
{
    background-color: rgb(232, 232, 232);
    /* border-top: 2px solid green; */
    color:green;
    display: flex;
    justify-content: space-between;
    background-color:white;
    flex-wrap: wrap;
    padding: 20px 40px 0px 50px;
    /* background-color: rgb(232, 232, 232); */
  
   
}

.footer h3
{
    margin-bottom: 20px;
    font-size: 1.6em;
}

 a,p{
    display: block;
    text-decoration: none;
    color:black;
    margin: 20px 0px;
    
}
#services p{
    margin: 40px 0px;
}
#services,#contact-us
{
    flex:1;
    align-self: center;
 
}
#copy-rights
{
    text-align: center;
    background-color: rgb(232, 232, 232);
    padding: 1px 0px;
 

}
#support-us
{
    width:100%;
   
    display: flex;
    justify-content: space-between;
    background-color: rgb(232, 232, 232);
 
  
}
#support-us p {
    color: green;
    font-size: 1.2em;
    margin-left: 18px;

}
#support-us div{
    
    align-self:center;
}

#feedback
{
    flex:1.3;
    
}

a,#services p:hover{
    color:green;
    width:fit-content;
    border-bottom: 2px solid green;
   
}

#support-us img{
    border-radius: 50%;
    width:40px;
    margin-left: 15px;
}
input,textarea{
    display: block;
    width: 80%;
    border: none;
    outline: none;
    border-bottom: 2px solid green;
    color:black;
    padding: 10px 0px;
    margin-bottom: 10px ;
}
span{
    color: green;
}
textarea
{
   
    border: 2px solid green;
    resize: none;
    padding: 10px;
    
}
input[type="submit"]
{
    margin: 10px 0px 10px;
    border:2px solid green;
    background-color: rgb(5, 92, 5);
    letter-spacing: 2px;
    color: white;
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