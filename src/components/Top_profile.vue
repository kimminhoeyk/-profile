<template>
    <div>
        <div class="Mprofile">
            <img class="imgP" src="@/assets/profilephoto.png">
            <div class="Tprofile">
                <div>
                    <h3>김민혁</h3> (Kim Min Heoyk)
                </div>
                <div>
                    <img class="icon" src="@/assets/phone.png">
                    : 010-3032-6117
                </div>
                <div>
                    <img class="icon" src="@/assets/email.png">
                    : rhdlsem@gmail.com
                </div>
                <div>
                    <img class="icon" src="@/assets/github.png">
                    : <a href="https://github.com/kimminhoeyk">github.com/kimminhoeyk</a>
                </div>
            </div>
        </div>
            
    </div>
</template>

<script>
export default {

}
</script>
<style>
    .Mprofile{
        display: flex;
        margin-left: 10vw;
        padding: auto;
    }
    .Tprofile{
        display:grid;
        margin-left: 3vw;
        color:rgb(238, 156, 32);
    }
    .imgP{
        width: 20%;
        height: auto;  

    }
    .icon{
        width : 5%;    
    }
    a{
        text-decoration : none;
    }
    a:hover{
        text-decoration : none;
    }
    a:link{
        color: rgb(238, 156, 32);
    }
    a:visited {
        color: rgb(238, 156, 32);
    }
</style>