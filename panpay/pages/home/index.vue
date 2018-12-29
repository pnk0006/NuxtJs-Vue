<template>
    <section>
        <hea-der />
        <div class="container-fluid clrpdg m-t-60">
            <div class="swiper-container">
                <div class="swiper-wrapper">
                    <div class="swiper-slide"><img src="../../assets/img/KV.png" alt="background" /></div>
                    <div class="swiper-slide"><img src="../../assets/img/KV.png" alt="background" /></div>
                    <div class="swiper-slide"><img src="../../assets/img/KV.png" alt="background" /></div>
                </div>
            </div>
            <div class="container clrpdg home_bg_two">
                <h1 class="t-c">Getting an European Current Bank Account Has Never Been Easier</h1>
                <div class="row panpay_container2 home_two_css t-c">
                    <div class="col-8 clrpdg home_two_css_lft_2">
                        <img src="https://static.panpay.cn/static/image/en/home_page/illustrator.png" class="img-responsive" alt="illustrator" />
                    </div>
                    <div class="col-4 clrpdg home_two_css_ryt clrpdg">
                    <ul>
                        <li><span>Individuals and corporations</span></li>
                        <li><span>Without leaving home</span></li>
                        <li><span>No offshore company required</span></li>
                        <li><span>Start your global journey immediately</span></li>
                    </ul>
                    <button class="btn btn-md btn-danger t-c" ui-sref="product">Learn More</button>
                    </div>
                </div>
            </div>
            <div class="container-fluid home_bg_three">
                <div class="container panpay_container home_three_css t-c">
                <h1 class="f-w-2">Why PanPay can open  European Current bank account for customer?</h1>
                    <h3>It is the first Chinese FinTech company that obtain an Electronic Money <br>Institution license from the EU Central Bank</h3>
                    <p>Learn More<img src="https://static.panpay.cn/static/image/en/home_page/Arrow-right.png"/></p>
                </div>
            </div>
            <div class="container-fluid home_bg_four t-c">
                <h1>PanPay Advantages</h1>
                <div class="container home_four_css clrpdg">
                    <div class="row home_four_adv_css panpay_container">
                        <div class="col-sm adv_item_css t-j animated slideInUp delay-4s">
                            <div class="item_div">
                                <img class="img-responsive iconSafe" src="https://static.panpay.cn/static/image/en/home_page/iconSafe.png" alt="iconSafe" />
                                <h4 class="f-w-2 t-c">Security</h4>
                                <p>PanPay’s core banking system is certified by the European Central Bank and directly connected to the ECB Clearing system. Its system security is aligned with the requirement of European bank institutions, ensuring that each client's funds, transactions, and information are protected by the Central-Bank-level security standard.</p>
                            </div>
                        </div>
                        <div class="col-sm adv_item_css t-j animated slideInUp delay-4s">
                            <div class="item_div">
                                <img class="img-responsive iconSafe" src="https://static.panpay.cn/static/image/en/home_page/iconQuike.png" alt="iconSafe" />
                                <h4 class="f-w-2 t-c">Convenience</h4>
                                <p>PanPay Account can be topped-up or withdrawn worldwide, saving up to 80% of cross-border payment fee. PanPay supports up to 14 different currencies, exchanging and transferring to more than 100 countries and regions around the world, unlimited capital accumulation, boundless currency converting, and instant cross-border transferring.</p>
                            </div>
                        </div>
                        <div class="col-sm adv_item_css t-j animated slideInUp delay-4s">
                            <div class="item_div">
                                <img class="img-responsive iconSafe" src="https://static.panpay.cn/static/image/en/home_page/iconNice.png" alt="iconSafe" />
                                <h4 class="f-w-2 t-c">Competitive Rates</h4>
                                <p>Offshore banking, the lowest rates can be 1/10 of that of traditional banks; For The e-commerce collection business, the minimum rates can be 1/3 of the mainstream collection agencies.</p>
                            </div>
                        </div>
                    </div>
                    <div class="row clrpdg m-t-70 home_four_seemore">
                        <p class="t-c">
                            Learn More <img alt="arrow" src="https://static.panpay.cn/static/image/en/home_page/Arrow-right.png"/>
                        </p>
                    </div>
                </div>
            </div>

        </div>
        <foo-ter />
    </section>
</template>
<script>
import HeaDer from '~/components/head/header.vue';
import FooTer from '~/components/footer/footer.vue';
import Swiper from 'swiper';
export default {
    components: {
        HeaDer,
        FooTer
    },
    data(){
        return{
            title:"Hi..! I am Naveen"
        }
    },
    mounted(){
        this.$nextTick(() => {
                new Swiper('.swiper-container', {
            })
        })
    }
}
</script>
<style scoped>
@import 'assets/css/home_page.css';
.main_cntnr{
    margin: 60px auto 0px;
    flex-flow: row wrap;
    width: 1200px;
    justify-content: center;
    align-items: center;
    text-align: center;
}
.swiper-container {
    width: 100%;
    height: 650px;
}
.swiper-slide {
    text-align: center;
    font-size: 18px;
    background: #fff;
    /* Center slide text vertically */
    display: -webkit-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    -webkit-align-items: center;
    align-items: center;
}
.swiper-slide img{
    width: 100%;
    height: auto;
}
</style>

