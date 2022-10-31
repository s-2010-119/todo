<template>
    <div>
        <a class="text-5xl font-serif text-teal-300" @click="sampleAlert('押された！')">todo</a>
        <button @click="sampleAlert('ボタンだよ')">ボタン</button>
        <h6>hogehoge</h6>
    </div>
</template>

<script lang="ts">
export default {
  name: 'HeaderLogo',
  methods: {
    sampleAlert(hensu: string) {
        // const mojiretu: string = "yahho"
        alert(hensu)
    }
  }
}
</script>