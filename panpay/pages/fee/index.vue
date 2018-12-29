<template>
    <section>
        <hea-der />
            <div  id="pricePage_cn" ng-controller="contactUsCtrl">
                <div class="container panpay_container t-c price_page price_page_css mobile_top_css">
                    <h1 class="f-s-40 t-c f-c-2c f-w-6 hedng">Standard service fee for PanPay banking service</h1>

                    <div class="row clrmrg row_headCss">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <h3 class="f-c-2c f-s-24 t-l f-w-6 l-h-80 p-l-40">Item</h3>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <h3 class="f-c-2c f-s-24 t-l f-w-6 l-h-80 p-l-40">Individual</h3>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <h3 class="f-c-2c f-s-24 t-l f-w-6 l-h-80 p-l-40">Corporate</h3>
                    </div>
                    </div>

                    <div class="row row_OneCss clrmrg br-l br-r">
                    <div class="col-md-4 col-xs-4 row_lftPdg clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5">Account usage</p>
                    </div>
                    <div class="col-md-4 col-xs-4 br-l br-r row_cntrPdg clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5">Usually for Study/Tourism/Shopping purpose, don’t support normal trading</p>
                    </div>
                    <div class="col-md-4 col-xs-4 row_rytPdg clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5">Usually for  normal trading purpose, support hierarchy account management </p>
                    </div>
                    </div>

                    <div class="row clrmrg row_SecondheadCss">
                    <h4 class="f-c-2c f-s-20 t-l f-w-6">Account management</h4>
                    </div>
                <!-- <div class="row row_TwoCss clrmrg br-b br-l br-r h62">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Open account</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h62 br-l br-r">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h62">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    </div>-->
                    <div class="row row_TwoCss clrmrg br-b br-l br-r h62 h62h86">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">SMS authentication service（OTP）</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg br-l br-r h62 h62h86">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    </div>
                    <div class="row row_TwoCss clrmrg h253 br-b br-l br-r">
                    <div class="col-md-4 col-xs-4 clrpdg h253">        
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-100 m-l-32">Account management(Each independent Multi-Currency account)</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg br-r br-l">
                        <div class="row clrmrg br-b h126">
                        <p class="f-c-2c f-s-18 t-l f-w-5 l-h-35 m-t-20 m-l-32"> 1 <= total account number<=5: <br>
                            2.00 € /month
                        </p>
                        </div>
                        <div class="row clrmrg h127">
                        <p class="f-c-2c f-s-18 t-l f-w-5 l-h-35 m-t-20 m-l-32"> 5 < total account number<=10: <br>
                            10.00 €/month
                        </p>
                        </div>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-100 m-l-32">5.00 €/month</p>
                    </div>
                    </div>
                    <div class="row row_TwoCss clrmrg br-b br-l br-r h86 h62h126">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Close account (Each independent Multi-Currency account)</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h86 br-l br-r h62h126">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">5.00 €</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">10.00 €</p>
                    </div>
                    </div>
                    <div class="row row_TwoCss clrmrg br-l br-r h62">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Initial deposits funds</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h62 br-l br-r">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">No requirement</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">No requirement</p>
                    </div>
                    </div>

                    <div class="row clrmrg row_SecondheadCss">
                    <h4 class="f-c-2c f-s-20 t-l f-w-6">Incoming payments</h4>
                    </div>
                    <div class="row row_TwoCss clrmrg br-l br-r br-b h62 h62h86">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Between PanPay Accounts</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h62 br-l br-r h62h86">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    </div>
                    <div class="row row_TwoCss clrmrg br-l br-r br-b h62 h62h86">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">SEPA<a ng-href="#34euc"><sup class="clr_pp f-s-12">34 European countries</sup></a></p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h62 br-l br-r h62h86">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">0.5 €/PCS</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">1.00 €/PCS</p>
                    </div>
                    </div>
                    <div class="row row_TwoCss clrmrg h62 br-l br-r">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">SWIFT<a ng-href="#sha"><sup class="clr_pp f-s-12">SHA</sup></a></p>
                    </div>
                    <div class="col-md-4 col-xs-4 h62 clrpdg br-l br-r">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">10.00 €/PCS</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">20.00 €/PCS</p>
                    </div>
                    </div>

                    <div class="row clrmrg row_SecondheadCss">
                    <h4 class="f-c-2c f-s-20 t-l f-w-6">Outward remittance</h4>
                    </div>
                    <div class="row row_TwoCss clrmrg br-l br-r br-b h62 h62h86">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Between PanPay Accounts</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h62 br-l br-r h62h86">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">waived</p>
                    </div>
                    </div>
                    <div class="row row_TwoCss clrmrg br-l br-r br-b h62 h62h86">
                    <div class="col-md-4 col-xs-4 clrpdg br-r">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">SEPA<a ng-href="#34euc"><sup class="clr_pp f-s-12">34 European countries</sup></a></p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg br-l br-r h62 h62h86">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">1.00 €/PCS</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">2.00 €/PCS</p>
                    </div>
                    </div>
                    <div class="row row_TwoCss clrmrg br-l br-r h86 h62h126">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">SWIFT<a ng-href="#highRk"><sup class="clr_pp f-s-12">SHA</sup></a>（Not include High risk 
                            countries）</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h86 br-l br-r h62h126">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">20.00 €/PCS</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">30.00 €/PCS</p>
                    </div>
                    </div>

                    <div class="row clrmrg row_SecondheadCss">
                    <h4 class="f-c-2c f-s-20 t-l f-w-6">Foreign Exhange</h4>
                    </div>
                    <div class="row row_TwoCss clrmrg br-l br-r h62 h62h86">
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Currency exchange(Non cash)</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg h62 br-l br-r h62h86">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Real-time Inter-bank rate</p>
                    </div>
                    <div class="col-md-4 col-xs-4 clrpdg">
                        <p class="f-c-2c f-s-18 t-l f-w-5 m-t-20 m-l-32">Real-time Inter-bank rate</p>
                    </div>
                    </div>

                    <div class="row clrmrg row_SecondheadCss">
                    <h4 class="f-c-2c f-s-20 t-l f-w-6">Debit Card （Coming soon）</h4>
                    </div>
                    <div class="row clrmrg pricing_row br-l br-r br-b p-t-33 p-r-25 p-b-18 p-l-39">
                    <p class="f-s-18 t-l f-c-2c f-w-5 l-h-35" id="multiCur">
                    <span class="clr_pp">* Multi-Currency：</span>US dollar，Euro，Pound sterling，Canadian dollar，Australian dollar，Moroccan Dirham，Chinese yuan renminbi，Hong Kong dollar，Japanese yen，Czech koruna，Danish krone，Norwegian krone，Polish zloty，Romanian leu，Swedish krona，Thai baht，South African rand，New Zealand dollar；  
                    </p>
                    <p class="f-s-18 t-l f-c-2c f-w-5 l-h-35 m-t-35" id="34euc">
                        <span class="clr_pp">* 34 European countries:</span>Austria, Belgium, Cyprus, Estonia, Finland, France, Germany, Greece, Ireland, Italy, Latvia, Lithuania, Luxembourg, Malta, Netherlands, Portugal, Slovakia, Slovenia, Spain, Bulgaria, Croatia, Czech Republic, Denmark Hungary, Poland, Romania, Sweden, Switzerland, Britain, Iceland, Liechtenstein, Norway, Monaco, San Marino.
                    </p>  
                    <p class="f-s-18 t-l f-c-2c f-w-5 l-h-35 m-t-35" id="highRk">
                        <span class="clr_pp">* High risk countries：</span>Afghanistan, Belarus, Burkina Faso, Cambodia, Central African Republic, Congo, Democratic Republic of the Congo, Ivory Coast IV, Cuba, Eritrea, Islamic Republic of Iran, Iraq, Lebanon, Liberia, Libya, Mozambique, Myanmar, North Korea, Palestine, South Sudan, Soviet Union Dan, Swaziland, Syria, East Timor, Vanuatu, Yemen, Zimbabwe.
                    </p>  
                    <p class="f-s-18 t-l f-c-2c f-w-5 l-h-35 m-t-35 m-b-35" id="sha">
                        <span class="clr_pp">* SHA: </span>The payer (sender of the payment) will pay all fees charged by PanPay, and the Payee (recipient of the payment) will pay all fees charged by receiving banks (correspondent /intermediary/ receiving bank).
                    </p>
                    </div>

                </div>
                </div>
        <foo-ter />
    </section>
</template>
<script>
import HeaDer from '~/components/head/header.vue';
import FooTer from '~/components/footer/footer.vue'
export default {
    components: {
        HeaDer,
        FooTer
    }
}
</script>
<style scoped>
@import 'assets/css/fee.css';
.main_cntnr{
    margin: 60px auto 0px;
    flex-flow: row wrap;
    width: 1200px;
    justify-content: center;
    align-items: center;
    text-align: center;
}
</style>
