<template>
    <page-card>
        <h2 class="head-total">Summary Total</h2>
        <form action="">
            <div class="form-total">
                <p></p>
            </div>
            <div>
                <page-button type="submit">
                    Submit
                </page-button>
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
    background-color: #f7ebff;
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
}
@keyframes animatedText{
    to{
        background-position: 100%;
    }
}
</style>