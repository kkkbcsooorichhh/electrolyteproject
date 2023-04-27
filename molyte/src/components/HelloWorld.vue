<script setup lang="ts">
defineProps<{
	msg: string;
}>();
</script>

<template>
	<div class="eProjectHome">
		<div class="home">
			<div class="navBox">
				<!-- <div class="nav">
                    <div class="navLeft">
                        <div class="logoWrap">
                            <img src="./icon.jpg" alt="">
                        </div>
                        <div class="ytcsWrap">
                            <img src="./ytcs.jpg" alt="">
                        </div>
                    </div>
                    <div class="navRight">
                    </div>
                </div> -->
			</div>
			<div class="eProjectIntroduction">
				<div class="text-introduction">
					<p class="p1">Molyte电解液数据库</p>
					<p class="p2">渊图远算，意在无遗</p>
					<p class="p3">高通量计算·电解液结构数据库·机器学习</p>
				</div>
			</div>
			<div class="eProjectOutline">
				<nav>
					<RouterLink to="/">Molyte简介</RouterLink>
					<RouterLink to="/project">成果展示</RouterLink>
				</nav>
        	<RouterView />
			</div>
		</div>
		<div class="homeFooter">
			<div class="footerDescription">
				<div class="descriptionHeader">
					<div class="descriptionHeaderLeft">
						<p>Molyte</p>
					</div>
					<div class="descriptionHeaderRight">
						<div class="descriptionHeaderRightItem">
							<p>用户</p>
						</div>
						<div class="descriptionHeaderRightItem">
							<p>协议</p>
						</div>
						<div class="descriptionHeaderRightItem">
							<p>引用</p>
						</div>
					</div>
				</div>
				<div class="descriptionFooter"></div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.home {
	display: block;
	min-width: 800px;
	font-size: 24px;
}

.eProjectIntroduction {
	position: relative;
	width: 100%;
	height: 100%;
	height: 15rem;
	background-size: 100%;
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	overflow: hidden;
	background-image: url(../assets/introductionBg.png);
}

.text-introduction {
	width: 90%;
	padding-left: 5rem;
	/* padding-top: 4.25rem; */
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	text-align: left;
}

.eProjectIntroduction .text-introduction .p2 {
	font-size: 0.9rem !important;
	font-weight: 500;
}

.eProjectIntroduction .text-introduction .p1 {
	font-size: 1.5rem;
	margin-bottom: 0.5rem;
}

.eProjectIntroduction .text-introduction .p3 {
	font-size: 0.6rem;
	font-weight: 500;
}

.eProjectIntroduction .text-introduction p {
	font-family: Noto Sans SC, Source Han Sans SC;
	font-style: normal;
	font-weight: 700;
	color: #fff;
}

.eProjectOutline {
	position: relative;
	left: 50%;
	-webkit-transform: translate(-50%);
	transform: translate(-50%);
	background-color: #fff;
	-webkit-box-shadow: 0 0 3px rgb(0 0 0 / 25%),
		-20px 20px hsl(0deg 0% 90% / 70%);
	box-shadow: 0 0 3px rgb(0 0 0 / 25%), -20px 20px hsl(0deg 0% 90% / 70%);
	border-radius: 3px;
	overflow: hidden;
	width: 40rem;
	padding-bottom: 1.75rem;
	top: -2rem;
	/* height: 1000px; */
}



.homeFooter {
	width: 100%;
	background-color: #006acb;
	height: 6rem;
}

.footerDescription {
	width: 28.975rem;
	position: relative;
	left: 50%;
	-webkit-transform: translateX(-50%);
	transform: translateX(-50%);
}

.descriptionHeader {
	position: relative;
	height: 2.95rem;
}

.descriptionHeaderLeft {
	height: 100%;
	float: left;
	padding-top: 0.75rem;
}

.descriptionHeaderRight {
	float: right;
	padding-top: 0.7rem;
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
}

.descriptionHeaderRightItem {
	position: relative;
	height: 100%;
	display: inline-block;
	margin-left: 0.75rem;
	font-family: Noto Sans SC, Source Han Sans SC;
	font-style: normal;
	font-weight: 700;
	font-size: 0.45rem;
	color: #fff;
}

.descriptionHeaderRightItem p {
	text-decoration: none;
	font-family: Noto Sans SC, Source Han Sans SC;
	font-style: normal;
	font-weight: 700;
	font-size: 0.45rem;
	color: #fff;
}

.descriptionHeaderLeft p {
	text-decoration: none;
	font-family: Noto Sans SC, Source Han Sans SC;
	font-style: normal;
	font-weight: 700;
	font-size: 1rem;
	color: #fff;
}

.nav {
	width: 30rem;
	top: 1rem;
	/* height: 2.25rem; */
	left: 2rem;
	position: fixed;
	z-index: 100;
	display: flex;
	flex-direction: column;
}

.navLeft {
	display: flex;
	flex-direction: row;
}

.logoWrap {
	background-color: white;
	width: 3rem;
	/* height: 3rem; */
	border-radius: 50%;
}

.logoWrap img {
	margin-left: 50%;
	margin-top: 50%;
	transform: translate(-50%, -50%);
}

.ytcsWrap {
	width: 3rem;
	height: 3rem;
	margin-left: 1rem;
}

.ytcsWrap img {
	margin-left: 50%;
	margin-top: 50%;
	transform: translate(-50%, -50%);
	width: 4rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
  display: inline-flex;
  flex-direction: row;
  gap: 2rem;
  justify-content: center;
}

nav a.router-link-exact-active {
  color: rgb(90, 191, 8);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
  text-decoration: none;
  color: black;
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
