<script setup></script>
<template>
  <main>
    <div class="container">
      <div class="title">
        <h1>Agendamentos</h1>
      </div>
      <div class="form-input">
        <div class="center_input">
          <input id="input_tit" type="text" placeholder="Nome" />
          <select>
            <option  value="">Escolha um cliente</option>
<!--             <option
              v-for="editora of editoras"
              :key="editora.id"
              :value="editora.nome"
            >
              {{ editora.nome }}
            </option> -->
          </select>
          <select>
            <option  value="">Escolha um Procedimento</option>
<!--             <option
              v-for="editora of editoras"
              :key="editora.id"
              :value="editora.nome"
            >
              {{ editora.nome }}
            </option> -->
          </select>
          <input id="input_tit" type="datetime" placeholder="Data e hora" />
          <select>
            <option  value="">Confirmação</option>
<!--             <option
              v-for="editora of editoras"
              :key="editora.id"
              :value="editora.nome"
            >
              {{ editora.nome }}
            </option> -->
          </select>
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
              <th>Cliente</th>
              <th>Procedimento</th>
              <th>Data e Hora</th>
              <th>Confirmação</th>
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
