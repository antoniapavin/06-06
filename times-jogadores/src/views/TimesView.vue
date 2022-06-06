<template>
<div class="container">
  <div class="title">
    <h2>Gerenciamento de times</h2>
  </div>
  <div class="form-input">
    <input type="text">
    <button>salvar</button>
  </div>
  <div class="list-times">
    <table>
      <thead>
        <tr>
          <th>ID</th>
          <th>Nome</th>
          <th>Ações</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Time 1</td>
          <td>???</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Time 2</td>
          <td>???</td>
        </tr>
         <tr>
          <td>3</td>
          <td>Time 3</td>
          <td>???</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
</template>

<style>
.title{
  text-align: center;
  margin: 2rem 0;
}
.form-input{
  display: flex;
  justify-content: center;
}
.form-input input{
  width: 50%;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 0 1rem;
  height: 40px;
}
.form-input button{
  height: 40px;
  margin-left: 1%;
  background-color: #2a539b;
  font-weight: bold;
  color: white;
  border: 1px solid #2a539b;
  border-radius: 10px;
  width: 15%;

}
.list-times{
  display: flex;
  justify-content: center;
  margin: 2rem 0;
}
table{
  width: 40%;
  border: 1px solid black;
  border-collapse: collapse;
  text-align: center;
  font-size: 1.1rem;
}
table thead{
  background-color: black;
  color: white;
}
table thead th{
  font-weight: bolder;
}
table tbody tr:nth-child(odd) {
  background-color: #2a539b;
  color: white;
}


</style>
