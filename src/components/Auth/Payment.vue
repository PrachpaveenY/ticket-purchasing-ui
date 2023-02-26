<template>
    <page-card>
        <h1 class="head-payment">Payment</h1>
    </page-card>
    <page-card>
        <form action="">
            <div class="form-payment">
                <h1>Payment</h1>
            </div>
            <ul class="form-payment">
                <b>Use Credit &nbsp;/&nbsp; Debit Card</b>
            </ul>
            <div class="form-payment" style="border: width: 100px; height: 100px; border:solid 2px #00ffff11; background-color: #00fff111;">
                <div id='div1-payment'><input type="radio"></div>
                <div id='div2-payment'>&nbsp;&nbsp;<b>VISA - 9999</b></div>
            </div><br><hr><br>
            <div class="form-payment">
                <div>
                    <b style="font-size: 20px;">Or Pay With</b>
                </div>
                <div style="font-weight: bold;">By using digital wallet and continuing past this page, you have read and are accepting the Teams of Use</div>
            </div><br>
            <div>
                <page-button type="submit">
                    Next
                </page-button>
            </div>
        </form>
    </page-card>
</template>
<script>
export default {
    name: 'Payment',
}
</script>
<style scoped>
input {
    display: block;
    width: 100%;
    font: inherit;
    padding: 0.15rem;
    border: 1px solid #cccccc;
}

input:focus {
    outline: none;
    border-color: #3a0061;
    background-color: #f7ebff;
}

.form-payment {
    margin: 1rem 0;
}

.head-payment {
    background-image: linear-gradient(to right, #7abdff, #ff5f5f, #f364a4, #be5cff);
    -webkit-background-clip: text;
    color: transparent;
    background-size: 300%;
    background-position: -100%;
    animation: animatedText 2s infinite alternate-reverse;
    text-align:center;
}
@keyframes animatedText{
    to{
        background-position: 100%;
    }
}

#div1-payment {
    float:left;
}
#div2-payment {
    float:left;
}

hr {
    color: #0000002f;
}
</style>