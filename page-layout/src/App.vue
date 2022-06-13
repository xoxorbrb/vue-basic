<template>
    <div id="app">
      <MyWebtoon :items="webtoons"/>
    </div>
    <div></div>
</template>

<script>
import MyWebtoon from '@/components/MyWebtoon.vue';
export default {
    name: "app",
    data() {
        return {
            webtoons: [
                {
                    name: "참교육",
                    link: "https://comic.naver.com/webtoon/list?titleId=758037&weekday=mon",
                    img: "https://shared-comic.pstatic.net/thumb/webtoon/758037/thumbnail/thumbnail_IMAG10_a2297504-4912-4c7e-a5a8-524d6fc77103.jpg",
                    isUpdate: true
                },
                {
                    name: "신의탑",
                    link: "https://comic.naver.com/webtoon/list?titleId=183559&weekday=mon",
                    img: "https://shared-comic.pstatic.net/thumb/webtoon/183559/thumbnail/thumbnail_IMAG10_9a752bec-9ebd-4214-9449-28cf4defc650.jpg",
                    isUpdate: true
                },
                {
                    name: "뷰티풀 군바리",
                    link: "https://comic.naver.com/webtoon/list?titleId=648419&weekday=mon",
                    img: "https://shared-comic.pstatic.net/thumb/webtoon/648419/thumbnail/thumbnail_IMAG10_1421195d-13be-4cde-bcf9-0c78d51c5ea3.jpg",
                    isUpdate: false
                },
                {
                    name: "윈드브레이커",
                    link: "https://comic.naver.com/webtoon/list?titleId=602910&weekday=mon",
                    img: "https://shared-comic.pstatic.net/thumb/webtoon/602910/thumbnail/thumbnail_IMAG10_3944ddad-8a6b-4568-98be-ca5f0be357d9.jpg",
                    isUpdate: false
                }
            ]
        };
    },
    components: { MyWebtoon }
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
