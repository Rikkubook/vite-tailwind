
<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
  <ul id="messages"></ul>
  <form id="form" action="">
    <input id="user" type="text" placeholder="user" style="width: 100px" autocomplete="off" />
    <input id="msg"  type="text" placeholder="message" autocomplete="off" />
    <button>Send</button>
  </form>
  <h1 class="text-3xl font-bold underline text-red-500">
    不是吧? ??? 13245 咖黑
  </h1>
  <p class="link">不是吧? ??? 13245 咖黑</p>
  <div class="card">
    <p class="link">dfsfsdf</p>
  </div>
</template>

<script setup>
import HelloWorld from '@/components/HelloWorld.vue'

// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup


//     var socket = io();

//     var messages = document.getElementById('messages');
//     var form = document.getElementById('form');
//     var msg = document.getElementById('msg');
//     var user = document.getElementById('user');
  
//     const params = new Proxy(new URLSearchParams(window.location.search), {
//       get: (searchParams, prop) => searchParams.get(prop),
//     });
//     let name = params.name; // "some_value"
//     user.value = name

//     form.addEventListener('submit', function(e) {
//       e.preventDefault();
//       if (user.value && msg.value) {
//         let umsg = `${user.value} : ${msg.value}`
//         socket.emit('chat message', umsg);
//         msg.value = '';
//       }
//     });
  
//     socket.emit('join', name)  

//     socket.on('join the room', function(name) {
//       console.log('user connected22')
//       var item = document.createElement('li');
//       item.textContent = `${name} 加入群組`;
//       messages.appendChild(item);
//       window.scrollTo(0, document.body.scrollHeight);
//     });
//     socket.on('get chat message', function(msg) {
//       console.log('user connected22')
//       var item = document.createElement('li');
//       item.textContent = msg;
//       messages.appendChild(item);
//       window.scrollTo(0, document.body.scrollHeight);
//     });
//     socket.on('offline', function(msg) {
//       console.log('offline')
//       var item = document.createElement('li');
//       item.textContent = `${msg}`;
//       messages.appendChild(item);
//       window.scrollTo(0, document.body.scrollHeight);
//     });
</script>


<style>

</style>
