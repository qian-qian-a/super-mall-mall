<template>
  <div class="layui-fluid">
    <div class="layui-col-md12">
      <form class="layui-form layui-form-pane" action="" id="frm-reg">
        <div class="layui-form-item">
					<label class="layui-form-label layui-bg-green">寄件人姓名</label>
					<div class="layui-input-block">
						<input type="text" name="postname" placeholder="请输入姓名" class="layui-input">
					</div>
				</div>
        <div class="layui-form-item">
					<label class="layui-form-label layui-bg-green">寄件人电话</label>
					<div class="layui-input-block">
						<input type="text" name="postnumber" placeholder="请输入电话号码" class="layui-input">
					</div>
				</div>
        <div class="layui-form-item">
					<label class="layui-form-label layui-bg-green">收件人姓名</label>
					<div class="layui-input-block">
						<input type="text" name="receivename" placeholder="请输入姓名" class="layui-input">
					</div>
				</div>
        <div class="layui-form-item">
					<label class="layui-form-label layui-bg-green">收件人电话</label>
					<div class="layui-input-block">
						<input type="text" name="receivenumber" placeholder="请输入电话号码" class="layui-input">
					</div>
				</div>
        <div class="layui-form-item">
					<label class="layui-form-label layui-bg-green">收件人电话</label>
					<div class="layui-input-block">
						<input type="text" name="receivenumber" placeholder="请输入电话号码" class="layui-input">
					</div>
				</div>
      </form>
    </div>
  </div>
</template>

<script>
  
  export default {
    name: "InputMessage",
    mounted(){
      layui.use('element', function(){
        var element = layui.element
      })
    }
  }
</script>

<style>

</style>