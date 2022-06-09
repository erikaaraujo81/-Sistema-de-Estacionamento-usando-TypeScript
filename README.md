# -Sistema-de-Estacionamento-usando-TypeScript

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Estacionamento</title>
  </head>
  <body>
    <div>
      <input
        type="text"
        id="name"
        placeholder="Nome do veículo"
        autocomplete="off"
      />
      <input
        type="text"
        id="licence"
        placeholder="Placa do veículo"
        autocomplete="off"
      />
      <button id="send" class="success">Registrar</button>
    </div>
    <table>
      <thead>
        <tr>
          <th>Veículo</th>
          <th>Placa</th>
          <th>Entrada</th>
          <th>Ações</th>
        </tr>
      </thead>
      <tbody id="garage"></tbody>
    </table>
  </body>

  <script src="main.js"></script>
</html>
 
