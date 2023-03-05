<template>
  <div class="view">
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
		width: 420px;
		height: 280px;
		position: absolute;
		margin: auto;
		top: 0px;
		bottom: 200px;
		right: 0px;
		left: 0px;
		background-color: rgba(240, 248, 255, 0.3);
		border-radius: 10px;
		transition: 0.3s;
		box-sizing: border-box;
	}
	.view:hover{
		box-shadow: 0px 0px 8px rgba(240, 248, 255, 0.3);
	}
</style>