<template>
    <footer id="footer" class="m-t-100">
        <div class="container panpay_container clrpdg footer_cntr">
            <div class="row footer_pdg clrpdg">
                <div class="col-2  clrpdg t-l ftr_lft">
                    <img src="https://static.panpay.cn/static/image/en/header/logoB@2x.png" class="ftr_img" alt="panpay" />		
                </div>
                <div class="col-sm clrpdg t-l footer_pdg_css">
                    <h4 class="">About Us</h4>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:'about'}">Company introduction</nuxt-link></p>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:'contact'}">Contact Us</nuxt-link></p>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:'career'}">Careers</nuxt-link></p>			
                </div>
                <div class="col-sm clrpdg t-l footer_pdg_css">
                    <h4 class="">Products & Solutions</h4>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:'contact'}">Products</nuxt-link></p>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:'solutions'}">Solutions</nuxt-link></p>			
                </div>
                <div class="col-sm clrpdg t-l footer_pdg_css">
                    <h4 class="m-b-6" style="margin-bottom:0px;">Security & Qualifications</h4>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:''}" style="margin-top:12px;">Security</nuxt-link></p>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:''}">Qualifications</nuxt-link></p>			
                </div>
                <div class="col-sm p-l-12 p-r-0 t-l footer_pdg_css">
                    <h4 class="">Rates & Fee</h4>
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:'fee'}">Fee</nuxt-link></p>			
                </div>
                <div class="col-sm clrpdg t-l footer_pdg_css">
                    <h4 class="">Help</h4>			
                    <p class="f-w-2"><nuxt-link class="nav-link" :to="{name:'faqs'}">FAQs</nuxt-link></p>			
                </div>
                <div class="col-2 t-l clrpdg footer_pdg_css mobile_brcss">
                    <h4>Certification organization</h4>
                    <div class="row clrmrg">
                        <div class="col-3 clrpdg">
                            <img class="img-responsive" src="https://static.panpay.cn/static/image/en/footer/pciDDS.png" alt="PIC DDS" />
                        </div>
                        <div class="col-9 clrpdg client_p">
                            PCI DSS approved					
                        </div>
                    </div>
                    <div class="row m-t-12 clrmrg">
                        <div class="col-3 clrpdg">
                            <img class="img-responsive" src="https://static.panpay.cn/static/image/en/footer/Eu.png" alt="欧盟特许金融机构" />
                        </div>
                        <div class="col-9 clrpdg client_p">
                            EU Licensed & Regulated<br> Financial Institution
                        </div>
                    </div>				
                </div>
            </div>
        </div>
        <div class="container-fluid second_footer_bg p-t-50">
            <div class="container panpay_container second_footer p-t-50">
                <p class="t-c f-s-14 m-b-20">
                    <a class="p-l-15 p-r-6 link" href="https://static.panpay.cn/static/image/en/Serviceagreement.pdf" target="_blank">Service Agreement</a>
                    <a class="p-l-6 p-r-6 link" href="https://static.panpay.cn/static/image/en/Privacyagreement.pdf" target="_blank">Privacy Agreement</a>			
                    <a class="p-l-6 p-r-6 link" ui-sref="cookie" target="_blank">Cookie Agreement</a>	
                </p>		
                <p class="t-c f-s-14">
                    <a target="_blank" href="http://www.miitbeian.gov.cn/">Copyright ©2018 PanPay Holdings Inc. Record number: 17044843 Shanghai ICP</a>
                </p>
                <p class="t-c f-s-12 footer_english p-t-20 p-b-30">
                    PanPay USA is authorized by the FinCEN of the United States under the Money Service Operator Regulations；<br/>
                    PanPay Hong Kong is authorized by the Commissioner of Customs & Excise under<br/>
                    the Money Service Operator Regulations；PanPay Europe is authorized by the European Central Bank under the unrestricted Electronic Money Regulations.<br/>
                    PanPay Europe Bank code: 38700, PanPay Europe BIC (SWIFT): PAEOLT21.
                </p>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
    
}
</script>
<style scoped>
@import 'assets/css/footer.css';
</style>


