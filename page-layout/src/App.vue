<template>
    <div>
      <!--웹툰-->
      <!-- <h1>webtoon</h1>
      <input type = "checkbox" id="참교육" value ="참교육" v-model="checkedWebtoons">
      <label for="참교육">참교육</label>
      <input type = "checkbox" id="신의탑" value ="신의탑" v-model="checkedWebtoons">
      <label for="신의탑">신의탑</label>
      <input type = "checkbox" id="뷰티풀군바리" value ="뷰티풀군바리" v-model="checkedWebtoons">
      <label for="뷰티풀군바리">뷰티풀군바리</label>
      <input type = "checkbox" id="윈드브레이커" value ="윈드브레이커" v-model="checkedWebtoons">
      <label for="윈드브레이커">윈드브레이커</label>
      <br>
      <span>찜한웹툰: {{checkedWebtoons}}</span> -->
      
      <!--성별-->
      <!-- <h2>성별</h2>
      <input type="radio" id = "남" value = "male" v-model="gender">
      <label for="남">남</label>
      <br>
      <input type="radio" id = "여" value = "female" v-model="gender">
      <label for="여">여</label>
      <br>
      <span>당신의 성별을 알려주세요: {{gender}}</span> -->

      <!--선호장르-->
      <h2>선호장르</h2>
      <select v-model="category">
          <option disabled value>선택해주세요</option>
          <option>로맨스</option>
          <option>호러</option>
          <option>스릴러</option>
      </select>
      <span>선택: {{category}}</span>
    </div>
    
</template>

<script>
export default {
    name: "app",
    data() {
        return {
            // checkedWebtoons: []
            // gender: ""
            category: ""
        };
    }
};
</script>

<style scoped>
</style>
