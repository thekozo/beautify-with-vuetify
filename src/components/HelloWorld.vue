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
					MỞ TÀI KHOẢN MIỄN PHÍ,
					<br />Để đồng hành cùng Đầu Tư 101
					<a href="https://bit.ly/Mo_Tai_khoan_VPS" target="_blank"
						>@dautu101</a
					>
				</p>
			</v-flex>

			<v-flex mb-5 xs12>
				<h2 class="headline font-weight-bold mb-3">Đồng hành cùng Đầu Tư 101</h2>

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
				href: 'https://t.me/addautu101'
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
				href: 'https://t.me/thekozo'
			},
			{
				text: 'Kênh Zalo',
				href: 'https://zalo.me/dautu101'
			},
			{
				text: 'Mở Tài khoản miễn phí VPS',
				href: 'https://bit.ly/Mo_Tai_khoan_VPS'
			},
			{
				text: 'Hoặc chứng khoán Techcombank',
				href: 'https://bit.ly/opentcbs'
			}
		]
	})
}
</script>

