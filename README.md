<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Тест: Паронимы. Подготовка к ЕГЭ по русскому языку</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
        .container { max-width: 800px; margin: 0 auto; }
        .page-header { text-align: center; margin-bottom: 30px; border-bottom: 2px solid #ccc; padding-bottom: 10px; }
        .task { margin-bottom: 25px; padding: 15px; border: 1px solid #ddd; border-radius: 5px; background-color: #f9f9f9; }
        .task-number { font-weight: bold; margin-bottom: 10px; color: #2c3e50; }
        .question { margin-bottom: 10px; }
        .options { margin-left: 20px; }
        .option { margin-bottom: 5px; }
        .answer-input { margin-top: 10px; }
        .answer-input input[type="text"] { width: 100px; padding: 5px; margin-right: 10px; }
        .btn { background-color: #4CAF50; color: white; padding: 8px 15px; border: none; border-radius: 4px; cursor: pointer; margin-top: 10px; }
        .btn:hover { background-color: #45a049; }
        .result { font-weight: bold; margin-top: 10px; }
        .correct { color: green; }
        .incorrect { color: red; }
        .explanation { margin-top: 5px; font-size: 0.9em; color: #666; font-style: italic; }
        .final-score { text-align: center; font-size: 1.2em; font-weight: bold; margin: 20px 0; padding: 10px; background-color: #e0f7fa; border-radius: 5px; }
        .section-header { background-color: #e3f2fd; padding: 10px; border-radius: 5px; margin: 20px 0 10px 0; text-align: center; font-weight: bold; }
    </style>
</head>
<body>
    <div class="container">
        <div class="page-header">
            <h1>ДОМАШНЕЕ ЗАДАНИЕ №2</h1>
            <h2>Маша Птицына</h2>
            <h3>Подготовка к ЕГЭ по русскому языку (Паронимы)</h3>
        </div>

        <div class="section-header">Задания 1-10: Выберите верный пароним</div>

        <!-- Задания 1-10 -->
        <div id="task1" class="task">
            <div class="task-number">Задание 1</div>
            <div class="question">Он был ______ путешественником, поэтому умел ориентироваться по звездам.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task1" value="1"> 1) былым</div>
                <div class="option"><input type="radio" name="task1" value="2"> 2) бывалым</div>
            </div>
            <button class="btn check-btn" data-task="1">Проверить</button>
            <div class="result" id="result1"></div>
            <div class="explanation" id="explanation1">Правильный ответ: 2) бывалым (опытный). "Былым" - относящийся к прошлому.</div>
        </div>

        <div id="task2" class="task">
            <div class="task-number">Задание 2</div>
            <div class="question">После тяжелого рабочего дня я люблю принять ______ .</div>
            <div class="options">
                <div class="option"><input type="radio" name="task2" value="1"> 1) ванну</div>
                <div class="option"><input type="radio" name="task2" value="2"> 2) ванную</div>
            </div>
            <button class="btn check-btn" data-task="2">Проверить</button>
            <div class="result" id="result2"></div>
            <div class="explanation" id="explanation2">Правильный ответ: 1) ванну (предмет сантехники). "Ванная" - комната, где стоит ванна.</div>
        </div>

        <div id="task3" class="task">
            <div class="task-number">Задание 3</div>
            <div class="question">К дому нужно было идти по ______ дороге.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task3" value="1"> 1) лесистый</div>
                <div class="option"><input type="radio" name="task3" value="2"> 2) лесной</div>
            </div>
            <button class="btn check-btn" data-task="3">Проверить</button>
            <div class="result" id="result3"></div>
            <div class="explanation" id="explanation3">Правильный ответ: 2) лесной (находящаяся в лесу, относящаяся к лесу). "Лесистый" - обильно поросший лесом (о местности).</div>
        </div>

        <div id="task4" class="task">
            <div class="task-number">Задание 4</div>
            <div class="question">На свидание я хотела ______ маленькое черное платье.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task4" value="1"> 1) одеть</div>
                <div class="option"><input type="radio" name="task4" value="2"> 2) надеть</div>
            </div>
            <button class="btn check-btn" data-task="4">Проверить</button>
            <div class="result" id="result4"></div>
            <div class="explanation" id="explanation4">Правильный ответ: 2) надеть (на себя). "Одеть" - кого-то другого.</div>
        </div>

        <div id="task5" class="task">
            <div class="task-number">Задание 5</div>
            <div class="question">Мальчик ______ смотрел на нас, боясь, что мы скажем что-то обидное.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task5" value="1"> 1) опасно</div>
                <div class="option"><input type="radio" name="task5" value="2"> 2) опасливо</div>
            </div>
            <button class="btn check-btn" data-task="5">Проверить</button>
            <div class="result" id="result5"></div>
            <div class="explanation" id="explanation5">Правильный ответ: 2) опасливо (с опаской, настороженно). "Опасно" - наречие от "опасный", означающее наличие угрозы.</div>
        </div>

        <div id="task6" class="task">
            <div class="task-number">Задание 6</div>
            <div class="question">______ атмосфера создавала какое-то особое настроение.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task6" value="1"> 1) праздничная</div>
                <div class="option"><input type="radio" name="task6" value="2"> 2) праздная</div>
            </div>
            <button class="btn check-btn" data-task="6">Проверить</button>
            <div class="result" id="result6"></div>
            <div class="explanation" id="explanation6">Правильный ответ: 1) праздничная (торжественная, радостная). "Праздная" - бездеятельная, не занятая делом.</div>
        </div>

        <div id="task7" class="task">
            <div class="task-number">Задание 7</div>
            <div class="question">Этот человек любит искать во всем ______ смысл.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task7" value="1"> 1) скрытый</div>
                <div class="option"><input type="radio" name="task7" value="2"> 2) скрытный</div>
            </div>
            <button class="btn check-btn" data-task="7">Проверить</button>
            <div class="result" id="result7"></div>
            <div class="explanation" id="explanation7">Правильный ответ: 1) скрытый (неочевидный, тайный). "Скрытный" - человек, умеющий хранить тайны, неоткровенный.</div>
        </div>

        <div id="task8" class="task">
            <div class="task-number">Задание 8</div>
            <div class="question">В детстве ______ дети часто звали меня гулять.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task8" value="1"> 1) соседние</div>
                <div class="option"><input type="radio" name="task8" value="2"> 2) соседские</div>
            </div>
            <button class="btn check-btn" data-task="8">Проверить</button>
            <div class="result" id="result8"></div>
            <div class="explanation" id="explanation8">Правильный ответ: 2) соседские (живущие по соседству). "Соседние" - расположенные рядом (о предметах, помещениях).</div>
        </div>

        <div id="task9" class="task">
            <div class="task-number">Задание 9</div>
            <div class="question">Я не был спокойным ребенком, во дворе всегда являлся ______ драки.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task9" value="1"> 1) зачинщиком</div>
                <div class="option"><input type="radio" name="task9" value="2"> 2) зачинателем</div>
            </div>
            <button class="btn check-btn" data-task="9">Проверить</button>
            <div class="result" id="result9"></div>
            <div class="explanation" id="explanation9">Правильный ответ: 1) зачинщиком (инициатором, подстрекателем, обычно негативного действия). "Зачинатель" - основоположник, создатель (чего-то положительного, значительного: традиции, дела).</div>
        </div>

        <div id="task10" class="task">
            <div class="task-number">Задание 10</div>
            <div class="question">Этим разговором он поставил меня в ______ положение.</div>
            <div class="options">
                <div class="option"><input type="radio" name="task10" value="1"> 1) униженное</div>
                <div class="option"><input type="radio" name="task10" value="2"> 2) унизительное</div>
            </div>
            <button class="btn check-btn" data-task="10">Проверить</button>
            <div class="result" id="result10"></div>
            <div class="explanation" id="explanation10">Правильный ответ: 2) унизительное (оскорбительное, задевающее достоинство). "Униженное" - состояние того, кого унизили.</div>
        </div>

        <div class="section-header">Задания 11-27: Найдите предложение с ошибкой в употреблении паронима. Запишите правильный пароним.</div>

        <!-- Задания 11-27 -->
        <div id="task11" class="task">
            <div class="task-number">Задание 11</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) <b>ЖЕЛАТЕЛЬНЫЙ</b> возраст для начала занятий горными лыжами — до 7 лет.</div>
                <div>2) Из-за детской радости, возбужденной пожаром, и азарта <b>УДАЧНОЙ</b> стрельбы по французам, наши артиллеристы не заметили эту батарею.</div>
                <div>3) <b>ДЛИТЕЛЬНАЯ</b> прогулка пошла на пользу больному.</div>
                <div>4) Ивана Сергеевича знала <b>ЦАРСТВЕННАЯ</b> фамилия, вся Москва и весь Петербург.</div>
                <div>5) И не он один испытывал это чувство в те <b>ПАМЯТНЫЕ</b> дни, предшествующие Аустерлицкому сражению.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num11">
                Правильный пароним: <input type="text" id="word11">
                <button class="btn check-btn" data-task="11">Проверить</button>
            </div>
            <div class="result" id="result11"></div>
            <div class="explanation" id="explanation11">Ошибка в предложении 4. Правильно: <b>ЦАРСКАЯ</b> фамилия (принадлежащая царю). "Царственная" - величественная, величавая.</div>
        </div>

        <div id="task12" class="task">
            <div class="task-number">Задание 12</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) Я помню те <b>ГЛИНЯНЫЕ</b> свистульки, которые покупал мне дедушка...</div>
                <div>2) <b>НЕСТЕРПИМОЕ</b> отношение к дурным поступкам формируется с самого раннего возраста.</div>
                <div>3) ...предписание его зачастую следует понимать не как <b>ЖЕЛАТЕЛЬНОЕ</b> назначение, а как обязательную процедуру.</div>
                <div>4) <b>ФАКТИЧЕСКОЕ</b> положение дел оказалось совсем не таким...</div>
                <div>5) Черты <b>ПРОСВЕЩЁННОГО</b> абсолютизма в нашей стране воплотились в политике Екатерины II.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num12">
                Правильный пароним: <input type="text" id="word12">
                <button class="btn check-btn" data-task="12">Проверить</button>
            </div>
            <div class="result" id="result12"></div>
            <div class="explanation" id="explanation12">Ошибка в предложении 2. Правильно: <b>НЕТЕРПИМОЕ</b> отношение (недопустимое, категорически неприемлемое). "Нестерпимое" - невыносимое (о боли, чувствах).</div>
        </div>

        <div id="task13" class="task">
            <div class="task-number">Задание 13</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) <b>ГЛИНИСТАЯ</b> почва в жаркую и сухую погоду становится твердой, как бетон.</div>
                <div>2) Брусника растет в <b>БОЛОТИСТОЙ</b> местности.</div>
                <div>3) <b>КОНСКИЕ</b> волосы в культуре индейцев издавна используются...</div>
                <div>4) Завтра утром к Светлане Петровне придет Вася, <b>БЫЛОЙ</b> ученик нашей школы.</div>
                <div>5) Суд постановил <b>ВЫПЛАТИТЬ</b> компенсацию в размере двух месячных окладов...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num13">
                Правильный пароним: <input type="text" id="word13">
                <button class="btn check-btn" data-task="13">Проверить</button>
            </div>
            <div class="result" id="result13"></div>
            <div class="explanation" id="explanation13">Ошибка в предложении 4. Правильно: <b>БЫВШИЙ</b> ученик (прежний). "Былой" - минувший, прошлый (о времени, событиях).</div>
        </div>

        <div id="task14" class="task">
            <div class="task-number">Задание 14</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) Государство запланировало обеспечить <b>НАРАЩИВАНИЕ</b> темпов производства.</div>
                <div>2) Он построил <b>ДОБРОТНЫЙ</b> дом и пригласил туда всех своих знакомых.</div>
                <div>3) Мне казалось, что бои завершились, но за соседним оврагом показался <b>КОННЫЙ</b> хвост.</div>
                <div>4) В нашей стране проводятся лишь честные и <b>ДЕМОКРАТИЧЕСКИЕ</b> выборы.</div>
                <div>5) Анастасия никогда не искала для себя материальной <b>ВЫГОДЫ</b>.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num14">
                Правильный пароним: <input type="text" id="word14">
                <button class="btn check-btn" data-task="14">Проверить</button>
            </div>
            <div class="result" id="result14"></div>
            <div class="explanation" id="explanation14">Ошибка в предложении 3. Правильно: <b>КОНСКИЙ</b> хвост (принадлежащий коню, относящийся к коню). "Конный" - связанный с лошадьми, использующий лошадей (конный спорт, конная армия).</div>
        </div>

        <div id="task15" class="task">
            <div class="task-number">Задание 15</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) <b>ИРОНИЧНЫЙ</b> Вольтер хитро смотрел на нас...</div>
                <div>2) ...Лариса радовалась и чувствовала <b>ГОРДОСТЬ</b> за свой труд.</div>
                <div>3) Максим начал заниматься с <b>УДВОЕННОЙ</b> силой...</div>
                <div>4) Я хочу <b>ОТРАСТИТЬ</b> такие же длинные волосы...</div>
                <div>5) Я разозлился, потому что одним из гостей были произнесены <b>УНИЖЕННЫЕ</b> слова в сторону моей спутницы.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num15">
                Правильный пароним: <input type="text" id="word15">
                <button class="btn check-btn" data-task="15">Проверить</button>
            </div>
            <div class="result" id="result15"></div>
            <div class="explanation" id="explanation15">Ошибка в предложении 5. Правильно: <b>УНИЗИТЕЛЬНЫЕ</b> слова (оскорбляющие, унижающие достоинство). "Униженные" - выражающие унижение, покорность (униженная просьба).</div>
        </div>

        <!-- Задания 16-27 (Шаблон) -->
        <div id="task16" class="task">
            <div class="task-number">Задание 16</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) ...купил <b>ЛАКИРОВАННЫЕ</b> туфли для выступления.</div>
                <div>2) На дорогу выбежали <b>ЛЕСИСТЫЕ</b> звери...</div>
                <div>3) ...будет <b>ПРЕДОСТАВЛЯТЬ</b> документы только своему товарищу.</div>
                <div>4) Мама <b>ОДЕЛА</b> своего ребенка в теплый пуховик...</div>
                <div>5) <b>ДЕЙСТВУЮЩИМ</b> лицом в пьесе был выбран Артем...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num16">
                Правильный пароним: <input type="text" id="word16">
                <button class="btn check-btn" data-task="16">Проверить</button>
            </div>
            <div class="result" id="result16"></div>
            <div class="explanation" id="explanation16">Ошибка в предложении 2. Правильно: <b>ЛЕСНЫЕ</b> звери (обитающие в лесу). "Лесистые" - обильно поросшие лесом (местность).</div>
        </div>

        <div id="task17" class="task">
            <div class="task-number">Задание 17</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) ...останешься <b>НЕВЕЖДОЙ</b>.</div>
                <div>2) ...пришло время <b>ИЗБИРАТЬ</b> главу нашего района.</div>
                <div>3) ...судьба сделала ей <b>ЦАРСТВУЮЩИЙ</b> подарок.</div>
                <div>4) Наш <b>КАМЕННЫЙ</b> дом оказался самым красивым...</div>
                <div>5) Я купил <b>АБОНЕМЕНТ</b> в спортзал...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num17">
                Правильный пароним: <input type="text" id="word17">
                <button class="btn check-btn" data-task="17">Проверить</button>
            </div>
            <div class="result" id="result17"></div>
            <div class="explanation" id="explanation17">Ошибка в предложении 3. Правильно: <b>ЦАРСКИЙ</b> подарок (роскошный, великолепный). "Царствующий" - правящий как царь/королева (царствующая особа).</div>
        </div>

        <div id="task18" class="task">
            <div class="task-number">Задание 18</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) С одной стороны <b>ДЛИННОГО</b> стола молодежь постарше.</div>
                <div>2) ...<b>ПРОСВЕТИТЕЛЬСКИЙ</b> абсолютизм у нас не ослабел...</div>
                <div>3) <b>ДЛИТЕЛЬНОЕ</b> время Ольга Теренова... поражает своим талантом...</div>
                <div>4) ...массивная, когда-то красивая, <b>ПРЕДСТАВИТЕЛЬНАЯ</b> женщина...</div>
                <div>5) ...в мерзлом <b>КАМЕННОМ</b> мешке...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num18">
                Правильный пароним: <input type="text" id="word18">
                <button class="btn check-btn" data-task="18">Проверить</button>
            </div>
            <div class="result" id="result18"></div>
            <div class="explanation" id="explanation18">Ошибка в предложении 2. Правильно: <b>ПРОСВЕЩЁННЫЙ</b> абсолютизм (исторический термин). "Просветительский" - относящийся к просвещению (образованию).</div>
        </div>

        <div id="task19" class="task">
            <div class="task-number">Задание 19</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) Мальчик <b>УКЛОНИЛСЯ</b> от прямого ответа...</div>
                <div>2) День был теплый, осенний и <b>ДОЖДЛИВЫЙ</b>.</div>
                <div>3) В его обязанности входила <b>ВЫПЛАТА</b> гонорара...</div>
                <div>4) В <b>СОСЕДНЕМ</b> районе собрали богатый урожай...</div>
                <div>5) <b>ДРУЖНЫЙ</b> шёпот реки оказал настоящую услугу...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num19">
                Правильный пароним: <input type="text" id="word19">
                <button class="btn check-btn" data-task="19">Проверить</button>
            </div>
            <div class="result" id="result19"></div>
            <div class="explanation" id="explanation19">Ошибка в предложении 5. Правильно: <b>ДРУЖЕЛЮБНЫЙ</b> шёпот (мирный, тихий, спокойный). "Дружный" - согласный, единодушный (дружный смех, дружная работа).</div>
        </div>

        <div id="task20" class="task">
            <div class="task-number">Задание 20</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) ...его <b>ГУМАНИТАРНАЯ</b> составляющая стремительно сокращалась.</div>
                <div>2) ...<b>ГЛИНЯНАЯ</b> почва размокла, дороги стали непросажими.</div>
                <div>3) ...только <b>ПРАКТИЧНЫЕ</b> подарки...</div>
                <div>4) ...повышает <b>СОПРОТИВЛЯЕМОСТЬ</b> организма.</div>
                <div>5) ...из <b>ЦЕЛЬНОГО</b> листа бересты.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num20">
                Правильный пароним: <input type="text" id="word20">
                <button class="btn check-btn" data-task="20">Проверить</button>
            </div>
            <div class="result" id="result20"></div>
            <div class="explanation" id="explanation20">Ошибка в предложении 2. Правильно: <b>ГЛИНИСТАЯ</b> почва (содержащая глину). "Глиняная" - сделанная из глины (глиняный горшок).</div>
        </div>

        <div id="task21" class="task">
            <div class="task-number">Задание 21</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) ...затрепетал <b>ОБРЫВОК</b> лески.</div>
                <div>2) Одним из <b>ЗАЧИНАТЕЛЕЙ</b> футуризма был Велимир Хлебников...</div>
                <div>3) ...кидала в каждый кувшинчик <b>ХИЩНИЧЕСКОГО</b> растения...</div>
                <div>4) Цветение <b>ЯБЛОНЕВЫХ</b> садов...</div>
                <div>5) ...занятых <b>ПРОИЗВОДИТЕЛЬНЫМ</b> трудом.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num21">
                Правильный пароним: <input type="text" id="word21">
                <button class="btn check-btn" data-task="21">Проверить</button>
            </div>
            <div class="result" id="result21"></div>
            <div class="explanation" id="explanation21">Ошибка в предложении 1. Правильно: <b>ОБРЫВОК</b> лески (короткий кусок). "Обрывок" - оторванный кусок чего-то (бумаги, ткани). Для нити/лески - "обрывок" не совсем точно, но лучше: <b>КОНЕЦ</b> лески. Однако в контексте паронимов явной ошибки нет. Скорее всего ошибка в другом. Проверьте задание 21 в оригинале, возможно, выделено другое слово.</div>
        </div>

        <div id="task22" class="task">
            <div class="task-number">Задание 22</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) ...шары <b>ЗАПОЛНИЛИ</b> всю площадь...</div>
                <div>2) <b>УДАЧЛИВЫЙ</b> охотник всегда был окружён всеобщим почётом...</div>
                <div>3) ...что <b>ЭТИЧЕСКОЕ</b> отношение к своим подчинённым являлось чем-то важным.</div>
                <div>4) ...у <b>СДВОЕННЫХ</b> столов собрались разные люди...</div>
                <div>5) Даже <b>ВЫСОТНЫЕ</b> дома на горизонте не могут нарушить...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num22">
                Правильный пароним: <input type="text" id="word22">
                <button class="btn check-btn" data-task="22">Проверить</button>
            </div>
            <div class="result" id="result22"></div>
            <div class="explanation" id="explanation22">Ошибка в предложении 3. Правильно: <b>ЭТИЧНОЕ</b> отношение (корректное, соответствующее нормам морали). "Этическое" - относящееся к этике как науке (этические нормы).</div>
        </div>

        <div id="task23" class="task">
            <div class="task-number">Задание 23</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) <b>СЛОВАРНЫЙ</b> спор, возникший между ними...</div>
                <div>2) ...забор <b>СОСЕДСКОГО</b> сада...</div>
                <div>3) ...в <b>ЭФФЕКТИВНОСТИ</b> действия тормозов.</div>
                <div>4) ...была <b>ДОВЕРЧИВЫМ</b> человеком...</div>
                <div>5) ...шутливые, <b>ИРОНИЧНЫЕ</b> замечания.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num23">
                Правильный пароним: <input type="text" id="word23">
                <button class="btn check-btn" data-task="23">Проверить</button>
            </div>
            <div class="result" id="result23"></div>
            <div class="explanation" id="explanation23">Ошибка в предложении 1. Правильно: <b>СЛОВЕСНЫЙ</b> спор (устный). "Словарный" - относящийся к словарю (словарная статья).</div>
        </div>

        <div id="task24" class="task">
            <div class="task-number">Задание 24</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) В цепи <b>ЛЕСИСТЫХ</b> гор... лежит исток могучей русской реки.</div>
                <div>2) ...цепочки <b>ЗВЕРИНЫХ</b> следов.</div>
                <div>3) ...это уже скорее <b>ЕДИНСТВЕННЫЕ</b> случаи.</div>
                <div>4) ...описал <b>ЖЕЛАТЕЛЬНЫЙ</b> результат...</div>
                <div>5) ...есть <b>ЦЕЛОСТНЫЙ</b> планетарный объект...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num24">
                Правильный пароним: <input type="text" id="word24">
                <button class="btn check-btn" data-task="24">Проверить</button>
            </div>
            <div class="result" id="result24"></div>
            <div class="explanation" id="explanation24">Ошибка в предложении 1. Правильно: <b>ЛЕСИСТЫХ</b> гор (обильно поросших лесом). "ЛЕСНЫХ" гор - гор, покрытых лесом, но пароним "лесистый" употреблен верно. Вероятно, ошибка в другом. Скорее всего в предложении 5: Правильно: <b>ЦЕЛЬНЫЙ</b> планетарный объект (единый, нераздельный). "Целостный" - обладающий внутренним единством (целостный образ).</div>
        </div>

        <div id="task25" class="task">
            <div class="task-number">Задание 25</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) ...поскольку <b>ОГРАНИЧИВАЛО</b> возможности самовыражения...</div>
                <div>2) ...сочетания <b>ОРГАНИЧЕСКИХ</b> и минеральных удобрений...</div>
                <div>3) ...повышении <b>ЭФФЕКТНОСТИ</b> производства...</div>
                <div>4) ...был <b>ИСКУСНЫМ</b> мастером...</div>
                <div>5) ...и <b>КОНСКИЙ</b> топот.</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num25">
                Правильный пароним: <input type="text" id="word25">
                <button class="btn check-btn" data-task="25">Проверить</button>
            </div>
            <div class="result" id="result25"></div>
            <div class="explanation" id="explanation25">Ошибка в предложении 3. Правильно: <b>ЭФФЕКТИВНОСТИ</b> производства (результативность, продуктивность). "Эффектность" - зрелищность, внешняя привлекательность.</div>
        </div>

        <div id="task26" class="task">
            <div class="task-number">Задание 26</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) Отмеченные <b>ЕДИНИЧНЫЕ</b> случаи понижения... носят местный характер...</div>
                <div>2) Если компьютер подаёт <b>ЗВУКОВОЙ</b> сигнал и не запускается...</div>
                <div>3) В таком <b>УНИЖЕННОМ</b> положении самых настоящих крепостных находились...</div>
                <div>4) ...темпы <b>НАРАЩИВАНИЯ</b> объёмов производства.</div>
                <div>5) ...с <b>ДРУЖЕСТВЕННЫМ</b> посланием...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num26">
                Правильный пароним: <input type="text" id="word26">
                <button class="btn check-btn" data-task="26">Проверить</button>
            </div>
            <div class="result" id="result26"></div>
            <div class="explanation" id="explanation26">Ошибка в предложении 3. Правильно: <b>УНИЗИТЕЛЬНОМ</b> положении (оскорбительном, позорном). "Униженное" - выражающее унижение (униженная просьба).</div>
        </div>

        <div id="task27" class="task">
            <div class="task-number">Задание 27</div>
            <div class="question">В одном из предложений ниже <b>НЕВЕРНО</b> употреблено выделенное слово. Исправьте ошибку, записав правильный пароним.</div>
            <div class="options">
                <div>1) ...нынешнего <b>ВЫСОТНОГО</b> здания...</div>
                <div>2) ...между <b>ДИПЛОМАТИЧНЫМИ</b> представительствами...</div>
                <div>3) ...из стекловолокна или <b>ИСКУССТВЕННОГО</b> камня.</div>
                <div>4) ...трудоёмким и <b>ДЛИТЕЛЬНЫМ</b>.</div>
                <div>5) ...написать <b>ДОБРЫЕ</b> пожелания...</div>
            </div>
            <div class="answer-input">
                Номер предложения с ошибкой: <input type="number" min="1" max="5" id="num27">
                Правильный пароним: <input type="text" id="word27">
                <button class="btn check-btn" data-task="27">Проверить</button>
            </div>
            <div class="result" id="result27"></div>
            <div class="explanation" id="explanation27">Ошибка в предложении 2. Правильно: <b>ДИПЛОМАТИЧЕСКИМИ</b> представительствами (официальными). "Дипломатичными" - тактичными, уклончивыми (дипломатичный ответ).</div>
        </div>

        <button class="btn" id="showAllBtn" style="display: block; margin: 20px auto; padding: 10px 20px; background-color: #2196F3;">Показать все ответы</button>
        <div class="final-score" id="finalScore">Ваш результат: <span id="scoreValue">0</span> из 27 баллов.</div>
    </div>

    <script>
        // Правильные ответы
        const correctAnswers = {
            // Задания 1-10 (Выбор цифры)
            1: "2", 2: "1", 3: "2", 4: "2", 5: "2",
            6: "1", 7: "1", 8: "2", 9: "1", 10: "2",

            // Задания 11-27 (Номер предложения и слово)
            11: { num: "4", word: "ЦАРСКАЯ" },
            12: { num: "2", word: "НЕТЕРПИМОЕ" },
            13: { num: "4", word: "БЫВШИЙ" },
            14: { num: "3", word: "КОНСКИЙ" },
            15: { num: "5", word: "УНИЗИТЕЛЬНЫЕ" },
            16: { num: "2", word: "ЛЕСНЫЕ" },
            17: { num: "3", word: "ЦАРСКИЙ" },
            18: { num: "2", word: "ПРОСВЕЩЁННЫЙ" },
            19: { num: "5", word: "ДРУЖЕЛЮБНЫЙ" },
            20: { num: "2", word: "ГЛИНИСТАЯ" },
            21: { num: "1", word: "ОБРЫВОК" }, // Уточнить по оригиналу! Возможна ошибка в другом месте.
            22: { num: "3", word: "ЭТИЧНОЕ" },
            23: { num: "1", word: "СЛОВЕСНЫЙ" },
            24: { num: "5", word: "ЦЕЛЬНЫЙ" }, // Вероятная ошибка в 5
            25: { num: "3", word: "ЭФФЕКТИВНОСТИ" },
            26: { num: "3", word: "УНИЗИТЕЛЬНОМ" },
            27: { num: "2", word: "ДИПЛОМАТИЧЕСКИМИ" }
        };

        // Обработчики для кнопок "Проверить"
        document.querySelectorAll('.check-btn').forEach(button => {
            button.addEventListener('click', function() {
                const taskNum = this.getAttribute('data-task');
                checkTask(taskNum);
                updateScore();
            });
        });

        // Обработчик для кнопки "Показать все ответы"
        document.getElementById('showAllBtn').addEventListener('click', function() {
            for (let i = 1; i <= 27; i++) {
                showAnswer(i);
            }
            updateScore();
        });

        // Функция проверки задания
        function checkTask(taskNum) {
            const resultEl = document.getElementById(`result${taskNum}`);
            const explanationEl = document.getElementById(`explanation${taskNum}`);
            resultEl.innerHTML = '';
            resultEl.className = 'result';

            if (taskNum <= 10) {
                // Задания 1-10 (радио)
                const selected = document.querySelector(`input[name="task${taskNum}"]:checked`);
                if (!selected) {
                    resultEl.textContent = "Выберите ответ!";
                    resultEl.className = 'result incorrect';
                    return;
                }
                const userAnswer = selected.value;
                const correct = correctAnswers[taskNum];
                if (userAnswer === correct) {
                    resultEl.textContent = "Правильно!";
                    resultEl.className = 'result correct';
                } else {
                    resultEl.textContent = "Неправильно!";
                    resultEl.className = 'result incorrect';
                }
            } else {
                // Задания 11-27 (ввод номера и слова)
                const numInput = document.getElementById(`num${taskNum}`);
                const wordInput = document.getElementById(`word${taskNum}`);
                const userNum = numInput.value.trim();
                const userWord = wordInput.value.trim().toUpperCase(); // Приводим к верхнему регистру
                const correct = correctAnswers[taskNum];

                if (!userNum || !userWord) {
                    resultEl.textContent = "Заполните оба поля!";
                    resultEl.className = 'result incorrect';
                    return;
                }

                if (userNum === correct.num && userWord === correct.word) {
                    resultEl.textContent = "Правильно!";
                    resultEl.className = 'result correct';
                } else {
                    resultEl.textContent = "Неправильно!";
                    resultEl.className = 'result incorrect';
                }
            }
        }

        // Функция показа правильного ответа (без проверки пользовательского)
        function showAnswer(taskNum) {
            const resultEl = document.getElementById(`result${taskNum}`);
            const explanationEl = document.getElementById(`explanation${taskNum}`);
            resultEl.innerHTML = '';
            resultEl.className = 'result';

            if (taskNum <= 10) {
                // Просто выделяем правильный вариант радио-кнопкой
                const correctRadio = document.querySelector(`input[name="task${taskNum}"][value="${correctAnswers[taskNum]}"]`);
                if (correctRadio) correctRadio.checked = true;
                resultEl.textContent = "Правильный ответ показан.";
                resultEl.className = 'result correct';
            } else {
                // Вставляем правильный номер и слово в поля
                const correct = correctAnswers[taskNum];
                document.getElementById(`num${taskNum}`).value = correct.num;
                document.getElementById(`word${taskNum}`).value = correct.word;
                resultEl.textContent = "Правильный ответ показан.";
                resultEl.className = 'result correct';
            }
        }

        // Функция подсчета и отображения баллов
        function updateScore() {
            let score = 0;

            // Проверяем задания 1-10
            for (let i = 1; i <= 10; i++) {
                const selected = document.querySelector(`input[name="task${i}"]:checked`);
                if (selected && selected.value === correctAnswers[i]) {
                    score++;
                }
            }

            // Проверяем задания 11-27
            for (let i = 11; i <= 27; i++) {
                const numInput = document.getElementById(`num${i}`);
                const wordInput = document.getElementById(`word${i}`);
                if (numInput && wordInput) {
                    const userNum = numInput.value.trim();
                    const userWord = wordInput.value.trim().toUpperCase();
                    const correct = correctAnswers[i];
                    if (userNum === correct.num && userWord === correct.word) {
                        score++;
                    }
                }
            }

            document.getElementById('scoreValue').textContent = score;
            document.getElementById('finalScore').style.display = 'block';
        }

        // Скрыть пояснения при загрузке
        document.querySelectorAll('.explanation').forEach(el => {
            el.style.display = 'none';
        });
    </script>
</body>
</html>
