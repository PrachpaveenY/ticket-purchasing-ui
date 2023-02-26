<template>
    <page-card>
        <h1  class="head-full">Ticket Purchasing Full</h1>
    </page-card>
    <page-card>
        <h1 class="head-ticket">List of show tickets available for purchase</h1>
        <form action="">
            <tbody>
                <tr>
                    <td class="compareother">List of Tickets 
                        <label>
                            <select style="width:250px; height:18px; color:#0066CC;" onchange="check1('r');tilek1.nr1.focus();" name="menu11" class="blue12px">
                                          
                                <option value="100,Movie Vue.js">Movie Vue.js</option>
                                            
                                <option value="200,Movie React.js">Movie React.js</option>
                                            
                                <option value="300,Movie Docker">Movie Docker</option>
                                            
                                <option value="400,Movie SQL">Movie SQL</option>
                                            
                                <option value="1000,Movie Ubuntu">Movie Ubuntu</option>
                                            
                                <option value="1100,Movie NoSQL">Movie NoSQL</option>
                                            
                                <option value="1200,Movie PostgreSQL">Movie PostgreSQL</option>
                                            
                                <option value="1300,Movie MongoDB">Movie MongoDB</option>
                                            
                                <option value="1400,Movie Express.js">Movie Express.js</option>
                                            
                                <option value="1500,Movie Golang">Movie Golang</option>
                                            
                                <option value="1600,Movie Git">Movie Git</option>
                                            
                                <option value="2100,Movie Jenkins">Movie Jenkins</option>
                                            
                                <option value="2700,Movie Flutter">Movie Flutter</option>
                                            
                            </select>
                        </label>
                    </td>
                </tr>				
            </tbody>
        </form>
    </page-card>
    <page-card>
        <h1 class="">Delivery</h1>
        <form action="">
            <div class="form-ticket">
                <b>Mobile Entry - Free</b>
            </div>
            <div class="form-ticket">
                <p>Available by Sun Apr 3 , 2022 <br> These mobile tickets will be transferred directly to you from a trusted seller . We'll email you instructions on how to accept them on the original ticket provider's mobile app.</p>
            </div>

            <div>
                <page-button type="submit">
                    Next
                </page-button>
            </div>
        </form>
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
    name: 'TicketPurchasingFull',
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
    background-color: #f7ebff;
}

.form-full {
    margin: 1rem 0;
}

.head-full {
    background-image: linear-gradient(to right, #00F260, #f79d00, #0575E6, #64f38c, #be5cff);
    -webkit-background-clip: text;
    color: transparent;
    background-size: 300%;
    background-position: -100%;
    animation: animatedText 5s infinite alternate-reverse;
    text-align:center;
}
.head-ticket {
    background-image: linear-gradient(to right, #7abdff, #ff5f5f, #f364a4, #be5cff);
    -webkit-background-clip: text;
    color: transparent;
    background-size: 300%;
    background-position: -100%;
    animation: animatedText 3s infinite alternate-reverse;
    text-align:center;
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

/* TicketList-Delivery.vue */
#div1 {
    float:left;
}
#div2 {
    float:left;
}

/* Payment.vue */
#div1-payment {
    float:left;
}
#div2-payment {
    float:left;
}

/* SummaryTotal.vue */
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

hr {
    color: #0000002f;
}
</style>