<script setup></script>
<template>
  <main>
    <div class="container">
      <div class="title">
        <h1>Clientes</h1>
      </div>
      <div class="form-input">
        <div class="center_input">
          <input id="input_tit" type="text" placeholder="Nome" />
          <input id="input_tit" type="text" placeholder="CPF" />
          <input id="input_tit" type="email" placeholder="Endereço" />
          <input id="input_quant" type="tel" placeholder="Telefone" />
          <input id="input_pre" type="email" placeholder="Email" />
          <div class="center">
            <button>Salvar</button>
          </div>
        </div>
      </div>
      <div class="list-livros">
        <table>
          <thead>
            <tr>
              <th>ID</th>
              <th>Nome</th>
              <th>CPF</th>
              <th>Endereço</th>
              <th>Telefone</th>
              <th>Email</th>
              <th>Manutenção</th>

            </tr>
          </thead>
          <tbody>
            <tr>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
              <td>
                <button>editar</button>
                <button>excluir</button>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </main>
</template>
<style></style>
