<template>
	<div>
		home
		<div class="box">

		</div>
	</div>
</template>
<script>
export default {
	
}
</script>
<style lang="scss">
@import "../../assets/scss/_mixin.scss";
.box{
	@include dpr(2){
		@include bg2(brand);
	}
	@include dpr(3){
		@include bg3(brand);
	}
	


}
</style>

