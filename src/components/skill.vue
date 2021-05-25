<template>
    <div class="part_skill">
        <div><h2>SKILL STACK</h2></div>
        <div class="All_skill">
            <div>
                <h3>Back-End Skill</h3>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/java.png">
                </div> 
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/Python.png">
                </div>
                <div>
                    <img class="skillimg" src="@/assets/spring-logo.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/jenkins.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/node.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/aws.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/firebase.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/docker.png">
                </div>
            </div>
            <div>
                <h3>Front-End Skill</h3>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/logo.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/jquery.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/jsp.png">
                </div>
                <div class="back_skill">
                    <img class="skillimg" src="@/assets/ajax.jpg">
                </div>
            </div>
        </div>
        <div>
            <h3>DataBase</h3>
            <div class="back_skill">
                <img class="skillimg" src="@/assets/oracle.png">
            </div>
            <div class="back_skill">
                <img class="skillimg" src="@/assets/nosql.jpg">
            </div>
            <div class="back_skill">
                <img class="skillimg" src="@/assets/mongodb.png">
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .part_skill{
        margin-top: 50px;
        text-align: center;
    }
    .All_skill{
        display: flex;
        justify-content: space-evenly;
    }
    .back_skill{
        display: inline;
        margin: 50px;
    }
    .skillimg{
        width: 150px;
        height: auto;
    }
</style>