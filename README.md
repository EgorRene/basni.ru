<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Боярский гнев | Летопись 1418 года</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            user-select: text;
        }

        body {
            background: #4a3628;
            background-image: radial-gradient(circle at 20% 35%, #5f4534 2%, #2f221a 80%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 2rem 1rem;
            font-family: 'Georgia', 'Times New Roman', 'Book Antiqua', serif;
        }

        /* КНИГА — переплёт + три страницы */
        .book {
            max-width: 1100px;
            width: 100%;
            background: #ecd9b4;
            background: linear-gradient(145deg, #f3e5ce 0%, #e2cfaa 100%);
            border-radius: 18px 12px 12px 18px;
            box-shadow: 20px 20px 35px rgba(0,0,0,0.5), inset 0 1px 2px rgba(255,245,210,0.8);
            padding: 1.8rem 1.2rem 2rem 1.2rem;
            transition: all 0.2s;
        }

        /* Имитация старинного фолианта */
        .manuscript-header {
            text-align: center;
            border-bottom: 2px solid #b4916b;
            margin-bottom: 2rem;
            padding-bottom: 0.8rem;
        }

        .rubric {
            font-size: 0.7rem;
            letter-spacing: 4px;
            text-transform: uppercase;
            color: #7c5d3c;
            background: #e7d5bb;
            display: inline-block;
            padding: 0.2rem 1.2rem;
            border-radius: 30px;
            font-family: 'Courier New', monospace;
        }

        h1 {
            font-size: 2.6rem;
            color: #3b2a1c;
            text-shadow: 2px 2px 0 #bd9a6a;
            letter-spacing: 2px;
            margin-top: 0.5rem;
            font-weight: 800;
        }

        .year-stamp {
            font-size: 1.3rem;
            font-style: italic;
            color: #8b6948;
            border-top: 1px solid #dbbc8e;
            display: inline-block;
            padding-top: 0.4rem;
            margin-top: 0.3rem;
        }

        /* три колонки — три страницы книги */
        .book-pages {
            display: flex;
            flex-wrap: wrap;
            gap: 1.8rem;
            margin: 2rem 0 1rem;
        }

        .page {
            flex: 1;
            min-width: 240px;
            background: #fef7e8;
            background: linear-gradient(165deg, #fff6ea, #fef0df);
            padding: 1.5rem 1.3rem;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0,0,0,0.2), inset 0 0 0 1px rgba(255,245,215,0.8);
            border-left: 4px solid #dbb47a;
            transition: 0.15s linear;
            font-size: 0.96rem;
            line-height: 1.5;
            color: #2f241b;
        }

        .page:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 25px -8px black;
        }

        .page-title {
            font-family: 'Times New Roman', serif;
            font-size: 1.35rem;
            font-weight: bold;
            border-bottom: 1px solid #e2c29b;
            margin-bottom: 1rem;
            padding-bottom: 0.3rem;
            color: #764b28;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .page-number {
            font-size: 0.7rem;
            background: #cfb587;
            color: #2d2116;
            padding: 0 8px;
            border-radius: 20px;
            font-family: monospace;
        }

        .initial {
            font-size: 2.2rem;
            font-weight: bold;
            float: left;
            line-height: 0.8;
            padding-right: 6px;
            color: #a56b35;
            font-family: 'Georgia', serif;
        }

        p {
            margin-bottom: 0.9rem;
            text-align: justify;
        }

        .quote-dialog {
            background: #e9dac8;
            padding: 0.5rem 0.9rem;
            border-radius: 20px;
            font-style: italic;
            margin: 0.8rem 0;
            border-left: 5px solid #b36f38;
            font-family: monospace;
            font-size: 0.9rem;
        }

        hr {
            margin: 1rem 0;
            border: 0;
            height: 1px;
            background: linear-gradient(90deg, #dabb8a, #b38042, #dabb8a);
        }

        .signature-line {
            margin-top: 1.5rem;
            text-align: right;
            font-family: 'Segoe Script', cursive;
            font-size: 0.85rem;
            color: #7d623c;
            border-top: 1px dashed #c8ab7e;
            padding-top: 0.8rem;
        }

        @media (max-width: 850px) {
            .book-pages {
                flex-direction: column;
            }
            h1 {
                font-size: 1.9rem;
            }
        }
    </style>
</head>
<body>
<div class="book">
    <div class="manuscript-header">
        <div class="rubric">📜 Свиток гнева и посмешища 📜</div>
        <h1>Как башкир-шут рассердил бояр</h1>
        <div class="year-stamp">Лето 6926‑е от Сотворения мира • 1418 год от Рождества Христова</div>
    </div>

    <div class="book-pages">
        <!-- СТРАНИЦА 1: ЗНАКОМСТВО И НАЧАЛО СВАРЫ -->
        <div class="page">
            <div class="page-title">
                <span class="page-number">Лист 1</span> 
                <span>📖 О боярах и пришлом шуте</span>
            </div>
            <p><span class="initial">В</span> лето 1418 от Рождества, в пору, когда на Руси князья меж собой грызлись, да ордынцы набегами баловали, сидели в высоком тереме два знатных боярина: <strong>Макс Бизарыч</strong> — нравом крут, борода лопатой, кулак — в два пуда, и <strong>Давид Гостов</strong> — хитёр, как лис, на язык остер, на расправу скор. Пили они мёд ставленный и толковали о делах ратных.</p>
            <p>И вдруг, откуда ни возьмись, в горницу вваливается <strong>башкир-шут</strong>, аки озорной бес. Звали его Елмай — хохотун, шаровары полосаты, колпак с бубенцами. Пришёл он к боярам не дань просить, не милость, а <span class="italic-grit">«смеху ради»</span>, как сам молвил.</p>
            <div class="quote-dialog">
                ⚔️ «Слышал я, бояре, что вы сильны да мудры. А ну скажите: от чего боярская шапка тяжёлой бывает? От ума аль от глупости?» — молвил башкир и подмигнул.
            </div>
            <p>Макс Бизарыч аж побагровел. Давид Гостов пальцы в кулак сжал. Шут не унимался, начал передразнивать их походку, кривляться и называть бояр «пузатыми тетеревами». С того самого часа и заварилась каша...</p>
            <div class="signature-line">✍️ Начало смуты, писано дьяком Нежданом</div>
        </div>

        <!-- СТРАНИЦА 2: ГНЕВ, УГРОЗЫ И БЕЗУМНАЯ ПОГОНЯ -->
        <div class="page">
            <div class="page-title">
                <span class="page-number">Лист 2</span> 
                <span>🔥 Ярость боярская и пляска шута</span>
            </div>
            <p><span class="initial">И</span> тогда Макс Бизарыч встал во весь рост. Тень его легла на всю светлицу. «Ах ты, долбаеб, — рыкнул он так, что блюда на столе подпрыгнули. — Мы с Давидом Гостовым под Азовом хазар крошили, а ты, смерд колпачный, смеешь нас шутами называть?»</p>
            <p>Башкир же ничуть не испугался. Вскочил на лавку, колпак набекрень и давай плясать вприсядку да приговаривать: «А бояре-то дурни! Бородатые бабы! Войной похваляются, а как до дела — так у них поясница прихватит!» <strong>Давид Гостов</strong> побелел от злобы. Схватил со стены шестопёр и крикнул: «Казнить на месте!»</p>
            <div class="quote-dialog">
                🎭 Шут Елмай, прыгая под потолок: «Казнить?! Да вы меня сперва поймайте, кикиморы заднеприводные!» 
            </div>
            <p>И началась погоня. Бояре гоняли башкира по всему терему: через поварню, в сенях, на гульбище. Шут уворачивался, кидался капустой, опрокинул квашню на голову Макса Бизарыча. Тот взревел. Давид Гостов запутался ногой в ковре и грохнулся, обложив шута последними словами.</p>
            <p>А башкир, гад, ещё и высунулся в волоковое окно, заорал на всю округу: «Бояре позорные! Ниже травы, тише воды! Ха-ха!» — и были таков.</p>
            <div class="signature-line">📜 Летописец: «Сего дни позор велик боярам был»</div>
        </div>

        <!-- СТРАНИЦА 3: ПОСЛЕДСТВИЯ, ПОМИРИЛИСЬ, НО ОСАДОК ОСТАЛСЯ -->
        <div class="page">
            <div class="page-title">
                <span class="page-number">Лист 3</span> 
                <span>⚔️ Исход и мудрость поздняя</span>
            </div>
            <p><span class="initial">Н</span>еделю спустя башкир-шут явился сам с повинной. Приволок мешок кумыса, жеребятины вяленой и пояс с серебром. Поклонился в ноги: «Простите, бояре. Дурак я, долбаеб, не со зла — с перепою да для смеха». Макс Бизарыч долго буравил его взглядом, квашеной капустой пропахший, а потом как засмеётся!</p>
            <div class="quote-dialog">
                💢 Давид Гостов сквозь зубы: «За такое и четвертовать мало. Но коль ты, шут, пойдёшь с нами на вылазку против татар — и покажешь пути через дубраву — жить оставим. И не смей больше боярскую честь задевать!»
            </div>
            <p>Башкир согласился. И повёл их тайными тропами. Тот поход удачным был — двух мурз в полон взяли. Но с того дня бояре Макс и Давид, чуть слышали слово «колпак» или «плясун», сразу мрачнели, как осенняя туча. А в народе сложили поговорку: <strong>«Не дразни боярина, коли сам шут — нарвёшься на шестопёр».</strong></p>
            <p>Что до башкира — он сделался придворным скоморохом, но боярам всегда кланялся в пояс, а прилюдно уже не кривлялся. Говорят, сам Макс Бизарыч иногда ему подмигивал и бросал краюху хлеба: «На, дурень, помни — в другой раз уши откручу». И ржали оба, а Давид Гостов ворчал, но в глазах его тоже играл смех.</p>
            <hr>
            <p><em>Так закончилась распря. А башкир тот, по прозвищу «Шут Елмай», до старости рассказывал внукам, как разозлил двух свирепых бояр и остался жив. И заканчивал всегда: «Главное — не бояться, но и глупость не заигрывай. Смех с добром — сила, а со злобой — беда».</em></p>
            <div class="signature-line">🔖 Конец летописи. Писано в городе Муроме, при свечах.</div>
        </div>
    </div>

    <div style="text-align: center; margin-top: 2rem; font-family: monospace; color: #6b4e30; font-size: 0.7rem; border-top: 1px dashed #c9aa78; padding-top: 1rem;">
        📚 Древняя книга «Боярские глумления» — полный список событий 1418 года. Ни одно слово не выдумано, кроме самой правды 📚
    </div>
</div>
</body>
</html>
