<template>

<div id="logform">
<form action="#" class="logform">
    
<h1>USER LOGIN</h1>
    <label for="username">USERNAME</label>
    <input type="text" id="username" name="username" >
    <label for="password">PASSWORD</label>
    <input type="password" id="password" name="password" >
    <button>LOGIN</button>
    <a href="#">forgot password?</a>
</form>
</div>

</template>
<script>
export default {
   name : 'LogIn'
}
</script>
<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

input,button{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-left: auto;
    margin-right: auto;
    border: 1px solid skyblue;
}
button{
    background-color: skyblue;
    cursor: pointer;
}


</style>