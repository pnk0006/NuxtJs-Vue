<template>
<section>
<hea-der />
<div class="main_cntnr" id="contactUs_cn" >
	<div class="container-fluid t-c contact_page contact_page_css">
		<div class="contact_us_one_bg">
			<h1 class="t-c animated bounceInDown delay-2s f-c-ff">Contact Us</h1>
		</div>		
		<div class="container panpay_container clrpdg contact_div_imgs hidden-xs">
			<div class="img_div">
				<img src="https://static.panpay.cn/static/image/en/contactus/Shanghai.png?index=3" class="img-responsive" alt="Shanghai" />
			</div>
			<div class="img_div">
				<img src="https://static.panpay.cn/static/image/en/contactus/HongKong.png" class="img-responsive" alt="HongKong" />
			</div>
			<div class="img_div">
				<img src="https://static.panpay.cn/static/image/en/contactus/Europe.png" class="img-responsive" alt="Europe" />
			</div>
			<div class="img_div">
				<img src="https://static.panpay.cn/static/image/en/contactus/SanFranCisco.png" class="img-responsive" alt="SanFranCisco" />
			</div>
		</div>
		<div class="container panpay_container clrpdg address_row_container">
			<div class="row address_row">
				<div class="col-md-3 col-sm-3 col-xs-12 cntct_sh t-l">
					<div class="clr_hvr"><h2><span class="spot"></span>Shanghai</h2></div>
					<p>Tel:+86 21 6031 4480<br>Email:sh@panpay.com.cn<br>Address:Room 22 B, No 5 building,<br>Fudu Plaza, 1365 Dongfang Road,<br>New Pudong District, Shanghai.
					</p>
				</div>
				<div class="col-md-3 col-sm-3 col-xs-12 cntct_hk t-l">
					<div class="clr_hvr"><h2><span class="spot"></span>Hong Kong</h2></div>
					<p>Tel:+852 9717 4058<br>Email:hk@panpay.com.cn<br>Address:Suite 1109, 11/F, Ocean<br>Centre, Harbour City,<br>Tsim Sha Tusi, Hong Kong.
					</p>
				</div>
				<div class="col-md-3 col-sm-3 col-xs-12 cntct_eu t-l">
					<div class="clr_hvr"><h2><span class="spot"></span>Europe</h2></div>
					<p>Tel:+370 6042 1022<br>Email:eu@panpay.com.cn<br>Address:Antano Tumėno g.4-27,<br>01109, Vilnius, Lithuania.
					</p>
				</div>
				<div class="col-md-3 col-sm-3 col-xs-12 cntct_sf t-l">
					<div class="clr_hvr"><h2><span class="spot"></span>San Francisco</h2></div>
					<p>Tel:+1 805 704 0669<br>Email:us@panpay.com.cn<br>Address:100 Pine Street, Suite<br>1250, San Francisco, CA 94111.
					</p>
				</div>
			</div>
			
			<h1 class="t-c f-c-85 f-s-34 f-w-2 mt2">Contact Form</h1>
			<div class="row justify-content-md-center contact_form_row">
				<div class="col-6 align-self-center">
					<div class="" id="contact_form">
						<div class="layui-form-item">
							<div class="layui-input-block intput_companyName">
								<input name="companyName" lay-verify="companyName" autocomplete="off" id="companyName" placeholder="Please input your company name" class="form-control form-control-md" type="text">
								<p class="error_intro t-l"></p>
							</div>
						</div>
						<div class="layui-form-item">
							<div class="layui-input-block intput_email">
								<input class="form-control form-control-md" type="email" name="youremail" lay-verify="youremail" autocomplete="off" id="youremail" placeholder="Please input your mail address">
								<p class="error_intro t-l"></p>
							</div>
						</div>
						<div class="layui-form-item">
							<div class="layui-input-block intput_phone">
								<input type="phone" onkeyup="value=value.replace(/[^\d]/g,'')" name="personalPhone" lay-verify="personalPhone" autocomplete="off" id="personalPhone" placeholder="Input your phone number" class="form-control form-control-md">
							<p class="error_intro t-l"></p>
							</div>
						</div>
						<div class="layui-form-item layui-form-text">
							<div class="layui-input-block intput_mess">
								<textarea placeholder="Enter your message" id="message" class="form-control form-control-md" name="message" lay-verify="message" ></textarea>
							<p class="error_intro t-l"></p>
							</div>
						</div>
						<div class="layui-form-item m-t-40 t-c">
							<div class="layui-input-block">
							<button class="layui-btn layui-btn-normal cntct_send f-c-ff f-s-16 f-w-3 t-c">Send</button>
							</div>
						</div>
					</div>
				</div>
			</div>
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
<style scoped>
@import 'assets/css/contact.css';
.main_cntnr{
    margin: 60px auto 0px;
    display: flex;
    flex-flow: row wrap;
    width: 100%;
    justify-content: center;
    align-items: center;
}
</style>

