<template>
  <div class="view">
	<div>海内存知己<span>，</span><br>天涯若比邻</div>
		<!-- <div>
			<input type="password" pattern="password">
		</div>
		<div>
			<input type="button" value="enter">
		</div> -->
  </div>
</template>

<script>
export default {
	data(){
		return {

		}
	}
}
</script>

<style>
	.view{
		font-size: 46px;
		color: aliceblue;
		position: absolute;
		width: 100%;
		top: 190px;
		transition: 0.3s;
		user-select: none;
		box-sizing: border-box;
	}
	.view>div>br{
		display: none;
	}
	.view:hover{
		box-shadow: 0px 0px 8px rgba(240, 248, 255, 0.3);
	}
	@media (max-width: 768px) {
		.view{
			top: 100px;
			padding: 0px 20px;
		}
		.view>div>span{
			display: none;
		}
		.view>div>br{
			display: block;
		}
	}
</style>