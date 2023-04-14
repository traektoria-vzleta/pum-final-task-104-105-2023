# ПУМ Задание 10-4/10-5

| Дедлайн | 13.05.2023 |
|---------|------------|

Дорогие ученики 10 класса! В качестве итогового проекта вам предлагается создать увлекательную однопользовательскую аркадную гонку в Unity. 

Игра состоит из уровней, каждый из которых включает различные препятствия и ситуации на дороге. Цель игрока - пройти уровень за не менее чем 30 секунд. Для помощи в прохождении уровней доступны различные бустеры и объекты, к примеру:  турбо-ускоритель, щит, бомба, и другие. В игре доступно не менее четырех видов различных бустеров.

На уровнях расположены монеты, которые игрок может собрать, чтобы улучшить свой рекорд и открыть новые уровни. Монеты также могут быть использованы для покупки дополнительных бустеров и улучшений для автомобиля.

Игрок может управлять своим автомобилем с помощью клавиш AD, при желании могут быть добавлены альтернативные способы управления. К примеру поддержка управления на мобильных устройствах.

## Регламент оценивания

Требования к проекту были разбиты на группы и каждой группе была присвоена соответствующая оценка, которая будет выставлена при сдаче проекта. При выставлении оценки действует следующая логика:

- Для оценки "3" нужно выполнить все требования на "3".
- Для получения оценки "4" нужно выполнить все требования, относящиеся не только к оценке "4", но и к оценке "3".
- Для получения оценки "5" нужно выполнить все требования, относящиеся к оценкам "3", "4" и "5".

Дополнительные баллы будут выставлены за:
- Высокую степень самостоятельности, креативности и оригинальности работы
- Правильное использование инструментов Git
- Реализацию дополнительной функциональности, не предусмотренной в задании
- Отсутствие ошибок и багов в работе
- Качество кода и его оформление
- Проявленный интерес и усердие в работе над проектом

Для успешной реализации проекта рекомендуется начать с MVP — минимального работающего прототипа и далее улучшать его до состояния готового продукта.

Уверены, что ваша гонка будет настолько захватывающей, что никто не сможет устоять перед соблазном сыграть еще раз! 💀

## Требования

### __на оценку "3"__

- Необходимо реализовать базовый функционал игры. Игра состоит из уровней, который игрок должен проходит за время. Уровень можно пройти на некоторое количество звезд в зависимости от времени прохождения (например, 1 минута - 3 звезды, 2 минуты - 2 звезды, 1 минута - 1 звезда). Уровень считается пройденным, если игрок прошел хотя бы на 1 звезду.

- В игре должно быть меню, через которое игрок сможет выбирать уровень для прохождения. Все уровни можно разделить на 2 типа: открытые и заблокированные. Уровень считается открытым, если пройден прошлый уровень. По умолчанию открыт 1-й уровень. Заблокированные уровни, очевидно, недоступны для прохождения. Также, должна отображаться информация о том, на сколько звезд игрок прошел уровень. Например, меню игры Angry Birds тлично подходит под это описание.

- Необходимо, чтобы игра содержала как минимум 5 уникальных уровней

### __на оценку "4"__

- Необходимо добавить в игру систему штрафов, добавляющих к времени прохождения дополнительные секунды.

    1. Если игрок выехал за пределы трасы, его возвращают на трассу и добавляют штрафное время (например, 3 секунды). 
    
    2. Если игрок столкнулся с препятствием, то ему также добавляют штрафное время.
    
- Необходимо реализовать систему бонусов. Бонусы встречаются на трассе и могут представлять собой плиточки, при наезде на которые игроку даются некоторые положительные эффекты. Необходимо реализовать не менне 2-х бонусов. Ниже приведены примеры бонусов, которые могут быть реализованы:

    1. Например, одним из таких бонусов может быть ускорение или заморозка времени.
    
    2. "Дополнительная жизнь". При использовании такого бонуса не начисляется штрафное время при столкновении с препятствием или выезде за трассу.

### __на оценку "5"__

Необходимо реализовать __одну__ из следующих механик:

#### __Система монеток__

- На каждом уровне генерируются монетки, которые игрок может собирать. Собранные монетки добавляются к балансу игрока. Баланс игрока сохраняется и при выходе из игры.

- Необходимо добавить функционал покупки новых скинов для машины за имеющиеся монетки

- Необходимо добавить функционал по улучшению характеристик уже имеющейся машины. Такими характеристиками могут быть скорость, маневренность etc.

- Необходимо добавить меню, поддерживающее весь выше перечисленный функционал. Примером такого меню может быть меню из игры Hill Climb Racing.

#### __Система боссов__

Необходимо добавить 1-2 уровня в игру, где игроку теперь нужно сразиться с боссом. На таких уровнях вместе с игроком также проезжает трассу бот. Задача игрока - проехать быстрее босса. Боссы могут мешать игроку каким-нибудь особенным образом: например, ставить на ходу препятствия или ускоряться.

## Регламент сдачи работы

При сдаче проекта необходимо учитывать следующие требования:

- Работа должна быть загружена в ваш репозиторий на Github Classroom.

- В репозиторий должен быть загружен исходный код игры.

- Не следует добавлять в репозиторий генерируемые файлы, такие как кэш сборки приложения, кэш операционной системы, служебные файлы, относящиеся только к вашему рабочему месту, а также генерируемые исполняемые файлы.

- Настоятельно рекомендуется после создания проекта вести разработку не в главной ветке. Лучше после создания игры создать отдельную ветку, например `dev`. При выполнении пункта создаете отдельную ветку, вносите изменения, и потом сливаете с веткой `dev`.

- В ветку `main` настоятельно рекомендуется делать Pull Request с указанием преподавателя в качестве проверяющего (reviwer). Так, вы облегчите работу как преподавателю, так как он будет знать, что вашу работу необходимо проверить, так и вам, так как преподаватель может отклонить запрос и написать по пунктом, что необходимо исправить.

- В сдаваемом на проверку репозитории не должно быть посторонних файлов или кусков кода, не относящихся к проекту.

- Работы, содержащие вредоносные файлы или каким-либо образом наносящие вред, будут оцениваться в оценку "**2**" 😋.

Также разработку игры можно вести по частям, создавая pull request-ы после написания каких-либо смысловых частей проекта. Так можно получить обратную связь на по вашей разработке, а также сократить время проверки итоговой работы, количество недочётов к исправлению работы в конце.

Рекомендуется не затягивать со сдачей проекта. Сдать работу необходимо не позже **13 мая 2023 года**, чтобы оставить время на доработку проекта. После сдачи проекта могут быть озвучены недочеты и рекомендации по их исправлению.


## Рекомендации и дополнительная информация

<aside>
⚠️ Этот файл может быть дополнен или изменён после выдачи задания. Рекомендуется переодически проверять его изменения или подписаться на уведомления об изменениях.

Актуальная версия задания будет выкладываться по этому адресу: https://github.com/traektoria-vzleta/pum-final-task-104-105-2023

</aside>

---

<aside>
⚠️ Обратите внимание, что при создании репозитория в GitHub, автоматически создается два коммита от имени бота GitHub. Чтобы избежать ошибок при работе с репозиторием, рекомендуется сначала выполнить `git clone` проекта на свое устройство, а затем добавлять свой проект в клонированную папку. В противном случае может возникнуть конфликт веток. Все ветки должны происходить от первого стартового коммита репозитория.

</aside>

---

Информацию, которой вы хотите сопроводить свой проект, к примеру скриншоты, чек-лист выполнения задания, видео с прохождением игры, загружайте в файл `README.md` (также в нём можно ссылаться на другие файлы), это поможет при проверке, а также дополнит ваш проект.

Также, по возможности, добавляйте туда поверхностное описание проекта. Например, в файле `README.md` вы можете добавить придуманные вами типы бонусов или описания боссов. Вы, также, можете туда добавить интересные архитектурные решения, которые вы применили в проекте.

---

В случае, если у вас появятся вопросы по содержанию задания, особенностям его выполнения или возникнут какие-либо трудности, вы можете в любое время задать вопрос в Github или в Telegram вашему преподавателю. Мы будем рады ответить на ваши вопросы или проконсультировать вас.

## Полезные материалы

Для вашего удобства в этом репозитории содержится список полезных материалов, которые могут помочь вам в успешной разработке проекта.

- [Краткое объяснение — что такое Git](https://youtu.be/Rke_Z1-nvUM)
- [Официальный сайт Git](https://git-scm.com)
- [Fork](https://git-fork.com) — удобный GUI для Git с наглядной визуализацией и поддержкой 2-х платформ (Windows, macOS). Распространяется бесплатно на сайте разработчика, хоть и на сайте присутствует цена рекомендуемого доната.
- [Rider](https://www.jetbrains.com/ru-ru/rider/) — Быстрая и мощная кросс-платформенная IDE для .NET c поддержкой Unity. Имеет trial на 30 дней.
- [Официальный сайт Unity](https://unity.com/ru)
- [Документация Unity](https://docs.unity3d.com/Manual/index.html)
- [Документация GitHub](https://docs.github.com/ru)
- Туториалы по работе с Git — [1](https://youtu.be/6sqKN2iofmo)    [2](https://youtu.be/fSFqNwczjrg)    [3](https://youtu.be/f9U53MllK10)
- [Советы по форматированию `README.md` от GitHub](https://docs.github.com/ru/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
