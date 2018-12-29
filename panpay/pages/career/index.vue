<template>
    <section>
        <hea-der />
        <div class="clrpdg job_page_bg">
            <div class="row justify-content-md-center job_page job_page_css">
				<div class="col-6 align-self-center">
                    <h1 class="t-c f-w-2">Welcome to Join Us</h1>
                    <p class="t-c f-w-2 hidden">We are looking for extraordinary talented people to help the company grow fast.</p>
                    <p class="t-c f-w-2">Sorry Currently we have no openings.</p>
                </div>
            </div>
        </div>
        <foo-ter />
    </section>
</template>
<script>
import HeaDer from '~/components/head/header.vue'
import FooTer from '~/components/footer/footer.vue'
export default {
    components: {
        HeaDer,
        FooTer
    }
}
</script>
<style>
.job_page_bg{
 background-image: url(https://static.panpay.cn/static/image/en/contactus/AboutUs_Invite_BG.png);
 background-size: cover;
 background-position: center;
 background-repeat: no-repeat;
 min-height: 480px;
 margin: auto;
 width: 1400px;
 max-width: 100%;
 /* display: flex; */
 flex-flow: row wrap;
 justify-content: center;
 align-items: center;
}
.job_page_css{
    margin-top: 60px;
}
.job_page_css h1{
    font-size: 2.5rem;
    color: #0f0f0f;
    margin: 4rem 0rem 1.875rem 0rem;
    font-weight: 200;
}
.job_page_css p{
	font-weight: 200;
    font-size: 1.125rem;
    color: #4f4f4f;
    line-height: 2rem;
}
</style>

