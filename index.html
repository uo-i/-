<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Простой Кликер</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            user-select: none;
        }

        .game-container {
            text-align: center;
            background-color: white;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            width: 300px;
        }

        h1 {
            color: #333;
            margin-bottom: 10px;
        }

        .score-display {
            font-size: 24px;
            font-weight: bold;
            color: #4caf50;
            margin-bottom: 20px;
        }

        .click-btn {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 20px 40px;
            font-size: 18px;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            transition: transform 0.1s, background-color 0.2s;
            box-shadow: 0 5px 15px rgba(0, 123, 255, 0.3);
            width: 100%;
        }

        .click-btn:hover {
            background-color: #0056b3;
        }

        .click-btn:active {
            transform: scale(0.95);
        }

        .upgrade-section {
            margin-top: 30px;
            border-top: 1px solid #eee;
            padding-top: 20px;
        }

        .upgrade-btn {
            background-color: #ff9800;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 14px;
            border-radius: 8px;
            cursor: pointer;
            width: 100%;
            transition: background-color 0.2s;
        }

        .upgrade-btn:hover {
            background-color: #e68a00;
        }

        .upgrade-btn:disabled {
            background-color: #cccccc;
            cursor: not-allowed;
        }
    </style>
</head>
<body>

    <div class="game-container">
        <h1>Кликер</h1>
        <div class="score-display">Монеты: <span id="score">0</span></div>
        
        <button class="click-btn" id="clickBtn">КЛИК!</button>

        <div class="upgrade-section">
            <button class="upgrade-btn" id="upgradeBtn" disabled>
                Купить улучшение (+1 к клику)<br>Цена: <span id="upgradeCost">10</span> монет
            </button>
        </div>
    </div>

    <script>
        // Инициализация переменных игры
        let score = 0;
        let clickPower = 1;
        let upgradeCost = 10;

        // Получение элементов DOM
        const scoreDisplay = document.getElementById('score');
        const clickBtn = document.getElementById('clickBtn');
        const upgradeBtn = document.getElementById('upgradeBtn');
        const upgradeCostDisplay = document.getElementById('upgradeCost');

        // Функция обновления интерфейса
        function updateUI() {
            scoreDisplay.textContent = score;
            upgradeCostDisplay.textContent = upgradeCost;
            
            // Кнопка улучшения активна, только если хватает монет
            upgradeBtn.disabled = score < upgradeCost;
        }

        // Логика клика
        clickBtn.addEventListener('click', () => {
            score += clickPower;
            updateUI();
        });

        // Логика покупки улучшения
        upgradeBtn.addEventListener('click', () => {
            if (score >= upgradeCost) {
                score -= upgradeCost;      // Списываем монеты
                clickPower += 1;           // Увеличиваем силу клика
                upgradeCost = Math.round(upgradeCost * 1.5); // Увеличиваем цену следующего улучшения
                updateUI();
            }
        });
    </script>

</body>
</html>
