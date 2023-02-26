<template>
    <page-card>
        <h1 class="head-total">Summary Total</h1>
    </page-card>
    <page-card>
        <div id='div1-total' style="font-size: 33px;"><b>Total</b></div>
        <div id='div3-total' style="font-size: 25px;">$458.00^</div><br><br><br>
        <form action="">
            <div class="form-ticket">
                <div><b style="font-size: 24px;">Tickets</b></div>
                <div>
                    <div id='div1-total'>Resale Tickets: $229.00 x 2</div>
                    <div id='div3-total'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$458.00</div><br><br>
                </div>
            </div>
            <div class="form-ticket">
                <b>Notes From Seller</b>
                <p>xfr XFER Proof of at least one dose of COVID - 19 vaccination for ages 5 to 11 and guests ages 12 and up will be required to show proof of two COVID - 19 vaccine doses one dose of the Johnson & Johnson vaccine , Masks must be worn.</p>
            </div><br>
            <b>Fees</b>
            <div class="form-ticket">
                <div>
                    <div id='div1-total'>Service Fee: $44.08 x 2</div>
                    <div id='div3-total'>$88.16</div><br>
                </div>
                <div>
                    <div id='div1-total'>Order Processing Fee</div>
                    <div id='div3-total'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;$2.95</div>
                </div>
            </div>
            <br><br>
            <div class="form-ticket">
                <div><b style="font-size: 24px;">Delivery</b></div>
                <div>
                    <div id='div1-total'>Mobile Entry</div>
                    <div id='div3-total'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Free</div><br><br>
                </div>
            </div>
            <div class="form-ticket">
                <p style="color: #0094d8;">Cancel Order</p>
            </div><br>
            <div class="form-ticket">
                <p>*All Sales Final - No Refunds</p>
            </div>
            <div>
                <div id='div1-total'><input type="checkbox"></div>
                <div id='div2-total'>&nbsp;I have read and agree to the current</div>
                <div id='div2-total' style="color: #0094d8;">&nbsp;Terms of Use</div>
                <br><br>
                <page-button type="submit">
                    <h2 style="padding: 0rem;">Place Order</h2>
                </page-button>
                <p style="font-size: 12px;">*Exceptions may apply, see our Teams of Use</p>
            </div>
        </form>
    </page-card>
</template>
<script>
export default {
    name: 'SummaryTotal',
}
</script>
<style scoped>
input {
    display: block;
    width: 100%;
    font: inherit;
    padding: 0.15rem;
    border: 1px solid #ccc;
}

input:focus {
    outline: none;
    border-color: #3a0061;
    background-color: #000c95;
}

.form-total {
    margin: 1rem 0;
}

.head-total {
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

#div1-total {
    float:left;
    text-align:center;
}
#div2-total {
    float:left;
    text-align:center;
}
#div3-total {
    float:right;
    width:100px;
    height:100px;
    text-align:center;
}
</style>