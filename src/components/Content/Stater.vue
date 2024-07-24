<template>
    <div id="stater">
       <div id="stater-content">
             <p>
                 <span id="for-c">C</span>reate a  engaging <span>websites</span><br>
                 using <span>vue,react </span> <br>and so on,<br>
                 that can run on any device.
             </p>
             <button>CONTACT US</button>
       </div>
       <div id="stater-img">
            <img src="@/assets/website-removebg-preview.jpg" alt="">
       </div>
    </div>
    
</template>

<script>

export default{
    name:"StaterPage"

}
</script>

<style scoped>
*
{
    margin:0px;
    text-transform: capitalize;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color:rgb(57, 57, 57);
}
#for-c
{
  font-size:1.5em;
}
#stater
{
    margin-top:80px;
    display: flex;
    justify-content: space-evenly;
  
}
#stater p{
    font-size: 2.5em;
    font-weight: 500;
   
    
}

#stater button{
    background-color: green;
    color: white;
    border: none;
    width: 40%;
    margin-top:50px;
    padding: 10px ;
letter-spacing: 2px;
}
#stater span{
    color: green;

}
@media (max-width: 768px) {
    #stater
    {
        flex-direction: column;
        background:url("@/assets/website-media.jpg");
        background-repeat: no-repeat;
    }
  
    #stater-content
    {
        align-self: center;
        /* justify-self: center; */
        
    }
    #stater-img
    {
        display: none;
    }
    #stater img
    {
        width:20em;
    }
}

</style>