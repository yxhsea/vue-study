<template>
    <div class="main">
        <div class="left">
            <Left></Left>
        </div>
        <div class="right">
            <div class="top">
                <img src="img/title.png"/>
            </div>
            <div class="buttom">
                <Right></Right>
            </div>
        </div>
    </div>
</template>

<style>
    * {
        padding: 0;
        margin: 0;
    }

    .left {
        width: 100px;
        float: left;
        margin-right: 10px;
    }

    .right {
        width: 1000px;
        float: left;
        margin-left: 10px;
    }

    .main {
        width: 1200px;
        margin: 20px auto;
    }

    .top img {
        height: 200px;
        width: 1000px;
    }

    .left, .right {
        background-color: #f5f5f5;
        height: 500px;
    }

</style>

<script>
    import Left from '../components/Left';
    import Right from '../components/Right'

    export default {
         components: {
             Left,
             Right
         }
    }
</script>
