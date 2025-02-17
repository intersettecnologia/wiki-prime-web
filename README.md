<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentação</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
        }
        .sidebar {
            width: 250px;
            padding: 15px;
            background: #f4f4f4;
            height: 100vh;
            overflow-y: auto;
            position: fixed;
        }
        .content {
            margin-left: 270px;
            padding: 20px;
        }
        a {
            text-decoration: none;
            color: #0366d6;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <h3>Menu</h3>
        <div id="sidebar-content">Carregando menu...</div>
    </div>
    <div class="content">
        <h1>Bem-vindo à Documentação</h1>
        <p>Selecione um tópico no menu para visualizar.</p>
    </div>

    <script>
        fetch('_Sidebar.md')
            .then(response => response.text())
            .then(text => {
                document.getElementById('sidebar-content').innerHTML = text.replace(/\[(.*?)\]\((.*?)\)/g, '<a href="$2">$1</a><br>');
            })
            .catch(error => console.log('Erro ao carregar sidebar:', error));
    </script>
</body>
</html>
