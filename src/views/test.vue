<template>
  <div class="about">
    <h1>This is a test page</h1>
  </div>
</template>
<script>
export default {
  mounted () {
    const obj = {
      s: '문자',
      n: 12,
      as: ['사과', '바나나']
    }
    console.log(obj.s, obj.n, obj.as[0]) // 문자 12 사과
    console.log(obj['s'], obj['n'], obj['as'][0]) // 문자 12 사과

  }
}
</script>
