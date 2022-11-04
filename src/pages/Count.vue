<template>
  <button @click="count++">{{ count }}</button>
</template>

<script>
export default {
  // 컴포넌트
  // data:{
  //     counter:0
  // }
  data() {
    return {
      count: 0,
    };
  },
};
</script>
