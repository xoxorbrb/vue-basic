<template>
<div>
  <MyHeader/>
  <div class = "wrap">
    <MyMenu/>
    <MyContent/>
  </div>
</div>
<div>
  <MyBox color = "blue"/>
  <MyBox color = "purple"/>
  <MyBox color = "green"/>
  <MyBox color = "blue"/>
  <MyBox color = "purple"/>
  <MyBox/>
</div>
</template>

<script>
import MyContent from '@/components/MyContent';
import MyHeader from '@/components/MyHeader';
import MyMenu from '@/components/MyMenu';
import MyBox from '@/components/MyBox';
export default {
  name: "app" , 
  components: {
    MyContent,
    MyHeader,
    MyMenu,
    MyBox
  }
};
</script>

<style scoped>
h1 {
  color: #03a9f4
}
.wrap {
  display: flex;
}
</style>
