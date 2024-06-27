#Parte do HTML#

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Serviços Contratados</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <nav class="navbar navbar-light bg-light">
                    <span class="navbar-toggler-icon"></span>
                    <span class="navbar-text">Serviços contratados</span>
                </nav>
            </div>
        </div>
        <div class="row mt-3">
            <div class="col-12">
                <table class="table">
                    <thead>
                        <tr>
                            <th>Item</th>
                            <th>Valor do mês</th>
                            <th>INFO</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Seguro Cartão</td>
                            <td>R$ 10,00</td>
                            <td><button class="btn btn-info">i</button></td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <button class="btn btn-primary btn-block">Adicionar Serviço</button>
            </div>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

#Parte do CSS#

body {
    background-color: #f8f9fa;
}

.navbar {
    padding: 0.5rem 1rem;
}

.table th, .table td {
    text-align: center;
    vertical-align: middle;
}

.table td button {
    border-radius: 50%;
    width: 30px;
    height: 30px;
    padding: 0;
}

.btn-block {
    margin-top: 1rem;
}
