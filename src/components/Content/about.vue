<template>
    <div class="main">
       <div class="heading"> <p>Websites as you <span>customize!!!!</span></p></div>
       <div class="box">
       <div class="box1"><img src="@/assets/mp.jpeg"><br><br><button>MORE DETAILS</button><br><p class="title">Marketing websites</p><p class="title-content">Create a website to develop your business.</p></div>
       <div class="box2"><img src="@/assets/th.jpeg"><br><br><button>MORE DETAILS</button><br><p class="title">Portfolio Websites</p><p class="title-content">Create a website to develop your business.</p></div>
       <div class="box3"><img src="@/assets/ep.jpeg"><br><br><button>MORE DETAILS</button><br><p class="title">E-commerce Website</p><p class="title-content">Create a website to develop your business.</p></div>

    </div>
    </div>
</template>
<script>
export default{
    name:'AboutContent',
}
</script>
<style scoped>
*
{
    margin:0px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.main{
    margin:100px 0 40px;
    padding: 10px 40px;
}
span{
    color: green;
    font-family: cursive;
}
.heading p{
    font-size: 2.5em;
    font-weight: 500;
    text-align: center;
    margin-bottom: 30px;
    
}
.title
{
    text-align: center;
    font-size: 1.2em;
    font-weight: 600;
    margin:10px 0px;
}
img{
    width:100%;
    height: 50%;
    
}

.box{
    display:flex;
    gap:20px;
    justify-content: space-evenly;
}
.box1:hover,.box2:hover,.box3:hover{
    border-radius: 0.5em;
    box-shadow: 2px 2px 0px 0px green;
    transform: scale(1.03);
    transition: 0.5s;
}
.box1,.box2,.box3{
    padding:30px;
}
button{
    background-color: black;
    color:white;
   padding: 2px 0px;
    width:100%;
}

@media(max-width:768px){

    .box{
        flex-direction: column;
    }
}



</style>
