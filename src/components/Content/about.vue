<template>
    <div class="main">
       <div class="heading"> <p>Websites as you <span>customize!!!!</span></p></div>
       <div class="box">
       <div class="box1"><img src="@/assets/mp.jpeg"><br><br><button>MORE DETAILS</button><br><p>Marketing websites</p><p>Create a website to develop your business.</p></div>
       <div class="box2"><img src="@/assets/th.jpeg"><br><br><button>MORE DETAILS</button><br><p>Portfolio Websites</p><p>Create a website to develop your business.</p></div>
       <div class="box3"><img src="@/assets/ep.jpeg"><br><br><button>MORE DETAILS</button><br><p>Website designing</p><p>Create a website to develop your business.</p></div>

    </div>
    </div>
</template>
<script>
export default{
    name:'AboutContent',
}
</script>
<style scoped>
.main{
    margin:50px 0;
}
span{
    color: green;
    font-family: cursive;
}
.heading{
    font-size: 2.5em;
    font-weight: 500;
    text-align: center;
    
}
.box{
    display:flex;
    gap:10px;
    justify-content: space-evenly;
}
.box1:hover,.box2:hover,.box3:hover{
    /* border:2px solid black; */
    border-radius: 0.5em;
    box-shadow: 2px 2px 2px 2px green;
    transform: scale(1.05);
    transition: 0.5s;
}
.box1,.box2,.box3{
    padding:20px;
}
button{
    background-color: black;
    color:white;
    /* font-weight: 100; */
    /* width:100%; */
}
.box2 p{
    font-weight: 600;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}
@media(max-width:768px){
    .box{
        flex-direction: column;
    }
}
/* img{
    width:400px;
    height:100px;
    padding: 0 100px;
} */


</style>
