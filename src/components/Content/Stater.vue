<template>
    <div id="stater">
       <div id="stater-content">
             <p>
                 <span id="for-c">C</span>reate a  engaging <span>websites</span><br>
                 using <span>vue,react </span> <br>and so on,<br>
                 that can <span>  run on any device</span>.
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
    margin-top:150px;
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
    border:2px solid green ;
    width: 40%;
    margin-top:50px;
    padding: 10px ;
letter-spacing: 2px;
}
#stater span{
    color: green;
    font-weight: 650;

}
#stater button:hover{
    background-color: white;
    /* /* transition: .4s; */
    border: 2px solid green; 
    color:green;
    animation: border-anim 0.4s forwards;
    
    
}
@keyframes border-anim {
    from {
        border-color: transparent;
    }
    to {
        border-color: green;
    }
}
@media (max-width: 1000px) {
    #stater
    {
        height: 100vh;
        margin:0px 0px 0px ;
        flex-direction: column;
        background:url("@/assets/website-media.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        color:black
        
    }
    
  
    #stater-content
    {
        align-self: center;
    
        
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