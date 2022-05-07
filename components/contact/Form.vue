<template>
  <form action="#">
    <div>
      <label for="name">お名前</label>
      <input type="text" id="name" name="name" />
    </div>

    <div>
      <label for="email">メールアドレス</label>
      <input type="text" id="email" name="email" />
    </div>

    <div>
      <label for="message">メッセージ</label>
      <textarea id="message" name="message"></textarea>
    </div>

    <input type="submit" class="button" value="送信" />
  </form>
</template>

<style scoped>
form div {
  margin-bottom: 14px;
}

label {
  font-size: 1.125rem;
  margin-bottom: 10px;
  display: block;
}

input[type="text"],
input[type="email"],
textarea {
  background-color: rgba(255, 255, 255, 0.5);
  border: 1px #FFF solid;
  border-radius: 5px;
  padding: 10px;
  font-size: 1rem;
}

input[type="text"],
input[type="email"] {
  width: 100%;
  max-width: 240px;
}

textarea {
  width: 100%;
  max-width: 480px;
  height: 6rem;
}

input[type="submit"] {
  border: none;
  cursor: pointer;
  line-height: 1;
}


.button {
  font-size: 1.125rem;
  background: #0bd;
  color: #fff;
  border-radius: 5px;
  padding: 10px 20px;
}
</style>
