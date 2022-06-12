<template>
<div>
  <MyHeader/>
  <div class = "wrap">
    <MyMenu/>
    <MyContent/>
  </div>
</div>
</template>

<script>
import MyContent from '@/components/MyContent';
import MyHeader from '@/components/MyHeader';
import MyMenu from '@/components/MyMenu';

export default {
  name: "app" , 
  components: {
    MyContent,
    MyHeader,
    MyMenu
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
