<template>
  <div class="view">
	<div>海内存知己，天涯若比邻</div>
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
	}
	.view:hover{
		box-shadow: 0px 0px 8px rgba(240, 248, 255, 0.3);
	}
</style>