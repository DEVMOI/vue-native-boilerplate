<template>
    <view class="container">
        <text class="text-color-primary">
            {{Heading}}
        </text>
    </view>
</template>
<script>
export default {
    name:'HelloWorld',
    props:{
        Heading:String
    }
}
</script>
<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: blue;
}
</style>

