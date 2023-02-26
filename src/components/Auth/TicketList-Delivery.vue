<template>
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
</template>
<script>
export default {
    name: 'TicketListDelivery',   
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

.form-ticket {
    margin: 1rem 0;
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
@keyframes animatedText{
    to{
        background-position: 100%;
    }
}

</style>