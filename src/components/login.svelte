<div class="logo-container">
  <img src="assets/head.png" height="70px" alt="">
</div>
<form action="">
  <input type="text" name="user" id="user" placeholder="username"/>
  <input type="password" name="password" id="password" placeholder="password"/>
  <div>
    <button class="submit" type="submit">
      <img alt="continue" width="15px" src="assets/arrow-forward-outline.svg">
    </button>
  </div>
</form>

<style>
  div {
    display: flex;
    justify-content: center;
  }

  input {
    width: 100%;
  }

  button {
    width: 30px;
    height: 30px;
    margin: 0.5em 0 0 0;
    background-color: rgb(100, 160, 225);
  }
  
  .logo-container {
    margin-bottom: 15px;
  }

  .submit {
    display: inline-block;
    border-radius: 50%;
    cursor: pointer;
  }
</style>