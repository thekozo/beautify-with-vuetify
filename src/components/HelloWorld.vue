<template>
	<v-container>
		<v-layout text-center wrap>
			<v-flex xs12>
				<v-img
					:src="require('../assets/logo.svg')"
					class="my-3"
					contain
					height="200"
				></v-img>
			</v-flex>

			<v-flex mb-4>
				<h1 class="display-2 font-weight-bold mb-3">
					DAU TU 101
				</h1>
				<p class="subheading font-weight-regular">
					Kết nối và đồng hành,
					<br />Cộng đồng Nhà đầu tư Telegram
					<a href="https://t.me/dautu101" target="_blank"
						>@dautu101</a
					>
				</p>
			</v-flex>

			<v-flex mb-5 xs12>
				<h2 class="headline font-weight-bold mb-3">Cách chúng tôi hỗ trợ bạn?</h2>

				<v-layout justify-center>
					<a
						v-for="(next, i) in whatsNext"
						:key="i"
						:href="next.href"
						class="subheading mx-3"
						target="_blank"
					>
						{{ next.text }}
					</a>
				</v-layout>
			</v-flex>

			<v-flex xs12 mb-5>
				<h2 class="headline font-weight-bold mb-3">Mạng xã hội chính</h2>

				<v-layout justify-center>
					<a
						v-for="(link, i) in importantLinks"
						:key="i"
						:href="link.href"
						class="subheading mx-3"
						target="_blank"
					>
						{{ link.text }}
					</a>
				</v-layout>
			</v-flex>

			<v-flex xs12 mb-5>
				<h2 class="headline font-weight-bold mb-3">Liên lạc với chúng tôi</h2>

				<v-layout justify-center>
					<a
						v-for="(eco, i) in ecosystem"
						:key="i"
						:href="eco.href"
						class="subheading mx-3"
						target="_blank"
					>
						{{ eco.text }}
					</a>
				</v-layout>
			</v-flex>
		</v-layout>
	</v-container>
</template>

<script>
export default {
	data: () => ({
		ecosystem: [
			{
				text: 'Hotline: 0938 239 388',
				
			},
			{
				text: 'Email: support@dautu101.com',
				
			},
			{
				text: 'hoặc:  research@dautu101.com',
				
			}
			
		],
		importantLinks: [
			{
				text: 'Telegram cho người mới',
				href: 'https://t.me/addautu101'
			},
			{
				text: 'Telegram cho Nhà đầu tư',
				href: 'https://t.me/dautu101'
			},
			{
				text: 'WhatsApp Business',
				href: 'https://wa.me/message/QLTBJG5O3HHLE1'
			},
			{
				text: 'Twitter',
				href: 'https://twitter.com/'
			}
			
		],
		whatsNext: [
			{
				text: 'Cơ cấu lại danh mục miễn phí',
				href: 'https://t.me/dautu101'
			},
			{
				text: 'Tư vấn tạo danh mục tối ưu',
				href: 'https://t.me/dautu101'
			},
			{
				text: 'Các chia sẻ về kinh nghiệm đầu tư',
				href: 'https://t.me/dautu101'
			}
		]
	})
}
</script>


<!--Zoho Campaigns Embed Button Starts--> <script type="text/javascript" src="https://ntkx.maillist-manage.com/js/jquery-1.11.0.min.js"></script> <script type='text/javascript' src='https://ntkx.maillist-manage.com/js/jquery-migrate-1.2.1.min.js'></script> <script type='text/javascript' src='https://ntkx.maillist-manage.com/js/jquery-ui-1.10.4.custom.min.js'></script> <a href="https://ntkx.maillist-manage.com/ua/Optin?od=11287ecbdbb541&amp;zx=12e08496f&amp;sD=1cd2afa5c098a5dd" id="embedLink" target="_blank"> <button type="button" purpose="nrmlBtn" class="" style="outline: none 0px; background-color: rgb(167, 167, 167); color: rgb(255, 255, 255); border-width: 1px; border-image: initial; padding: 6px 10px; border-radius: 5px; text-align: center; width: auto; cursor: pointer; font-size: 14px; font-family: Arial; border-style: solid;" changetype="EMBED_BUTTON" id="EMBED_BUTTON" name="EMBED_BUTTON" value="Tham Gia Nhận Thư Thông Báo Của Chúng Tôi" formopenin="New Window" btntype="nrmlBtn" onclick="zc_loadForm('campaigns.zoho.com','https://ntkx.maillist-manage.com/ua/Optin?od=11287ecbdbb541&amp;zx=12e08496f&amp;sD=1cd2afa5c098a5dd')"> <span class="zceditcnt" style="">Tham Gia Nhận Thư Thông Báo Của Chúng Tôi</span> </button> </a> <div purpose="uploadButtonImageCtn" style="display: none;"><a name="EMBED_BUTTON" style="cursor: pointer" href="https://ntkx.maillist-manage.com/ua/Optin?od=11287ecbdbb541&amp;zx=12e08496f&amp;sD=1cd2afa5c098a5dd" target="_blank"><img id="uploadedBtnImg" class="uploadedBtnImg" src="//img.zohostatic.com/campaigns/static1/images/spacer.gif" style="width: 300px; height: 158px; cursor: pointer" onclick="zc_loadForm('','https://ntkx.maillist-manage.com/ua/Optin?od=11287ecbdbb541&amp;zx=12e08496f&amp;sD=1cd2afa5c098a5dd')"></a> <div id="logoCustomizeDiv" class="mt5 ml10" style="font-weight: normal;"> <a for="" class="linktxt" name="uploadFromLib" purpose="uploadBtnImg" id="uploadBtnImage" href="https://ntkx.maillist-manage.com/ua/Optin?od=11287ecbdbb541&amp;zx=12e08496f&amp;sD=1cd2afa5c098a5dd" onclick="showSignupFormImagesLib(this);" onmouseover="$(this).css('text-decoration','underline')" onmouseout="$(this).css('text-decoration','none')" style="text-decoration: none;" target="_blank"> Thay đổi</a> <span class="lightgray">|</span><a href="https://ntkx.maillist-manage.com/ua/Optin?od=11287ecbdbb541&amp;zx=12e08496f&amp;sD=1cd2afa5c098a5dd" class="linktxt" id="delSignTmLogo" onclick="removeEmbedBtnImage(this);" target="_blank"> Xóa</a></div></div> <input type='hidden' id='zc_Url' value='ntkx.maillist-manage.com'/> <input type='hidden' id='zc_formIx' name='zc_formIx' value='3zcde47ea08d63c2ea75b0bf59cfb179cdc962ac06d43d15f40fb8f00b279e5788' > <input type='hidden' id='cmpZuid' name='zx' value='12e08496f' > <input type='hidden' id='viewFrom' name='viewFrom' value='BUTTON_ACTION' /> <input type='hidden' id='button_tc_codeVal' name='button_tc_codeVal' value='ZCFORMVIEW' /> <script type='text/javascript' src='https://ntkx.maillist-manage.com/js/optin_min.js'></script> <script> var trackingText='ZCFORMVIEW'; var $ZC = jQuery.noConflict(); $ZC('[id=embedLink]').append("<input type='hidden' id='tc_code"+$ZC('[id=embedLink]').size()+"' value="+trackingText+">"); var elemSize = parseInt($ZC('[id=embedLink]').size())-1; var embedLink = $ZC($ZC('[id=embedLink]')[elemSize]).attr('href'); if(embedLink!=undefined && embedLink!=null && embedLink!='null'){ var dynamicCodeVal = $ZC("#tc_code"+$ZC('[id=embedLink]').size()).val(); embedLink = embedLink+'&trackingcode='+dynamicCodeVal; $ZC($ZC('[id=embedLink]')[elemSize]).attr('href',embedLink); $ZC('[id=button_tc_codeVal]').val(dynamicCodeVal); trackSignupEvent(dynamicCodeVal,'buttonView'); } </script> <!-- Zoho Campaigns Embed Button End -->
