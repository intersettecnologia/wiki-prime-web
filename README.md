<!DOCTYPE html>
<html>
<head>
    <title>Documentação</title>
    <style>
        .sidebar { width: 250px; float: left; padding: 10px; background: #f4f4f4; }
        .content { margin-left: 260px; padding: 10px; }
    </style>
</head>
<body>
    <div class="sidebar">
        {% include sidebar.md %}
    </div>
    <div class="content">
        {{ content }}
    </div>
</body>
</html>
