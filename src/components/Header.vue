<script>
export default {}
</script>

<template>
	<div class="container mx-auto">
		<div class="flex justify-between items-end py-5">
			<div class="flex items-center gap-8">
				<img
					class="bg-gradient-to-r from-purple-500 to-pink-500 p-5 cursor-pointer"
					src="/icons/burger.svg"
					alt=""
				/>
				<img src="/icons/logo.svg" alt="" />
			</div>
			<nav>
				<ul class="flex gap-5 mb-6">
					<li class="font-light text-xs">
						<select class="focus:outline-none bg-white" name="" id="">
							<option value="">Покупателям</option>
						</select>
					</li>
					<li class="font-light text-xs">
						<select class="focus:outline-none bg-white" name="" id="">
							<option value="">Поставщикам</option>
						</select>
					</li>
					<li class="font-light text-xs"><a href="#">Частые вопросы</a></li>
				</ul>
				<form action="" class="flex relative">
					<select
						class="text-base font-light focus:outline-none bg-gradient-to-r from-purple-500/10 to-pink-500/10 absolute py-2 px-3 top-1 left-1 cursor-pointer"
						name=""
						id=""
					>
						<option value="">Везде</option>
					</select>
					<input
						type="text"
						class="min-w-[700px] gradient-border border border-gradien py-2 focus:outline-none"
					/>
					<img class="absolute right-5 top-2" src="/icons/search.svg" alt="" />
				</form>
			</nav>
			<div class="">
				<div
					class="flex font-light divide-x-2 divide-black text-xs justify-end mb-6 cursor-pointer"
				>
					<img class="px-2" src="/icons/FlagRu.svg" alt="" />
					<p class="px-2">Русский</p>
					<select class="focus:outline-none bg-white cursor-pointer" name="" id="">
						<option value="">₽</option>
					</select>
				</div>
				<div class="flex text-center text-sm gap-14 cursor-pointer">
					<span class="text-center">
						<img class="mx-auto mb-1" src="/icons/user.svg" alt="" />
						<p>Войти</p>
					</span>
					<span class="text-center">
						<img class="mx-auto mb-1" src="/icons/like-heart.svg" alt="" />
						<p>Избранное</p>
					</span>
					<span class="text-center">
						<img class="mx-auto mb-1" src="/icons/cart.svg" alt="" />
						<p>Корзина</p>
					</span>
				</div>
			</div>
		</div>
	</div>
</template>

<style lang="scss" scoped></style>
