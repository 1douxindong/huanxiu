<template>
    <div>
        <img class="img-default" src="../../assets/huanxiu.jpg" alt="">
        <div class="bottom-bg" >
            <div class="conect">
                <span>联系方式：</span>
                <span> 021-52991657</span>
                <span> 上海市静安区延安西路129号华侨大厦23层 xucheng@1foli.com</span>
            </div>
<!--            <img class="logo" src="../../assets/shaolinzenlogo.jpeg" alt="">-->
            <span class="bottom-txt">Copyright @ 2019-2022 幻休科技（上海）有限公司 All rights reserved. </span>
        </div>
    </div>
</template>

<script>
    export default {
        name: "index"
    }
</script>

<style scoped>
    .img-default{
        display: block;
        width: 100%;
        background: #F1F1F1;
        border: none;
    }
    .bottom-bg{
        padding: 20px;
        background: #262626;
        /*padding: 10px;*/
        color: #F1F1F1;
    }
    .conect{
        display: flex;
        flex-direction: column;

    }
    .bottom-txt{
        margin-top: 40px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

</style>