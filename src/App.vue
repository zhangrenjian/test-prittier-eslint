<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.png">
        <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
        <div class="a">
            <div class="b">
                b容器里面的呢人
            </div>
            <div class="c">
                cl里面的 内容
                <ul>
                    <li v-for="item in nameArr">
                        {{ item }}
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
    name: 'App',
    components: {
    // HelloWorld
    },
    data() {
        return {
            name: "121",
            age: 'age',
            nameArr: ['1', '2', '3']
        }
    },
    methods: {
        handClick() {
            console.log(111);
        },
        aa() {
              let a
            const b = 1;
               const c = 'asdsa'
        }
    }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
