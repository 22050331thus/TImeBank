<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	.index{
		background-color: #e0e0e0;
	}
	.centerWord{
		flex: auto;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		
	}
</style>
