# Tic-toe
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic-Tac-Toe</title>
    <style>
        .board {
            display: grid;
            grid-template-columns: repeat(3, 100px);
            grid-gap: 5px;
        }
        .cell {
            width: 100px;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 36px;
            border: 1px solid #000;
            cursor: pointer;
        }
        .message {
            margin-top: 20px;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <h1>Tic-Tac-Toe</h1>
    <div class="board" id="board"
