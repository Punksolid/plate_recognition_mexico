<template>
    <div class="wrapper">

        <text class="greeting">License Plate Recognition</text>
        <div style="flex-direction: row;margin-bottom: 16px;justify-content: space-between">
            <text class="button" value="Focus" type="primary" @click="focus"></text>
        </div>
        <input type="text" placeholder="Input Text" class="input" :autofocus=true value="" @change="onchange" @input="oninput"/>

    </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {}
  }
}
</script>
.greeting {
text-align: center;
margin-top: 70px;
font-size: 50px;
color: #41B883;
}
.message {
margin: 30px;
font-size: 32px;
color: #727272;
}
</

style

>
