<template>
    <div class="row banner">
        <div class="col">
            <div class="text1-container">
                <span class="text1">مسؤوليتنا حمايتك, والالتزام مسؤوليتك</span>
            </div>
        </div>
        <div class="col">
            <div class="row text2">حمل تطبيق توكلنا</div>
            <div class="row">
                <div class="col-4"><img class="download" src="../assets/huaweigalary.png" alt="huawei galary"></div>
                <div class="col-4"><img class="download" src="../assets/appstore.png" alt="app store"></div>
                <div class="col-4"><img class="download" src="../assets/googleplay.png" alt="google play"></div>
            </div>
            <div class="row arrows">
                <ul class="pagination center">
                    <li class="left"><span>&lt;</span></li>
                    <li class="unselected"></li>
                    <li class="selected"></li>
                    <li class="unselected"></li>
                    <li class="unselected"></li>
                    <li class="right"><span>&gt;</span></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>
    .arrows {
        margin-top: 100px;
        margin-left: -360px;
        color: #1FA99A;
        font-size: 20px;
    }

    .center {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .left, .right {
        font-family: sans-serif;
        width: 40px;
        height: 40px;
        border-radius: 50%;
        box-shadow: 0 0 10px 0 #80808061;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .left {
        margin-right: 40px;
    }

    .right {
        margin-left: 40px;
        margin-right: 100px;
    }

    .selected, .unselected {
        height: 10px;
        width: 10px;
        border-radius: 45%;
        margin: 0px 5px 0 5px
    }
    
    .selected {
        background-color: red;
    }

    .unselected {
        background-color: grey;
    }

    .download {
        width: 90%;
    }

    .text1-container {
        background-color: #1FA99A;
        width: 80%;
        height: 100px;
        margin-top: 300px;
        margin-left: -12px;
        display: flex;
        align-items: center;
        justify-content: center;
        border-start-end-radius: 3em 3em;
        border-end-end-radius: 3em 3em;
    }

    .text1 {
        font-size: 35px;
        color: white;
    }

    .text2 {
        margin-top: 500px;
        margin-bottom: 20px;
        margin-right: 15px;
        font-size: 30px;
        color: rgb(16, 54, 22);
        justify-content: flex-end;
    }

    .banner {
        background-image: url("../assets/hero.png");
        background-size: 90% 100%;
        background-repeat: no-repeat;
        width: 100%;
        height: 45rem;
    }
</style>