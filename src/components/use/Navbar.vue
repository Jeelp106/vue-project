<template>
<div class="container">
    <ul class="list">
        <li class="con_item"><a href=" #">Home</a></li>
        <li class="con_item"><a href="#">About</a></li>
        <li class="con_item"><a href="#">Signup</a></li>
        <li class="con_item"><a href="#">Login</a></li>
    <input class="serch_elm" type="serch" />
    <button class="serch_btn">Serch</button>
    </ul>
</div>
</template>

<script>
export default {
    name: "Nav"
}
</script>

<style scoped>
html{
    margin: 0px;
    padding: 0px;
}
.container{
    margin: 0px;
    padding: 0px;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: #111;
}
.serch_elm{
    padding-top: 5px;
    margin-top: 11px;
    margin-left: 300px;
    border-radius: 5px;
}
.serch_btn{
    margin-left: 5px;
    padding-bottom: -5px;
    padding-top: 2px;
    border-radius: 5px;
    background-color: blanchedalmond;
    color: black;
}
.serch_btn:hover{
    background-color: #333;
    color: whitesmoke;
}
</style>
