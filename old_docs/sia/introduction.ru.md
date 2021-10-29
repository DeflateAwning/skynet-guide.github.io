# Введение в Sia
Sia существует уже несколько лет, показывая медленный, но уверенный рост. Возможно, вы слышали о Sia как о децентрализованной платформе облачного хранения данных и начали наблюдать за ее развитием. Возможно, вы начали торговлю или майнинг Siacoin, а может, слышали о каких-либо форках или противоречиях. А может быть, вы открыли для себя Sia только сейчас.

Что бы ни привело вас сюда, вы, скорее всего, ищете информацию, чтобы понять, что такое Sia на самом деле и как это работает. Вы хотите узнать, какие возможности эта технология дает пользователям и как посредством Skynet она сделала децентрализованный Интернет реальностью. Весь этот веб-сайт призван сопроводить вас в этом увлекательном путешествии.

## Децентрализованная платформа облачного хранения данных
Sia – это **децентрализованная платформа облачного хранения данных**.

**Децентрализованная** означает отсутствие центрального сервера или регулятора, имеющего единоличный контроль над сетью.

Каждый отдельный **узел** *(компьютер, на котором установлено ПО Sia, например, ваш кошелек Sia-UI)* является равноправным участником сети и хранит свою собственную проверенную копию **блокчейна Sia**. Блокчейн можно представить себе так: у вас есть набор информации *(транзакции)*, который надо разослать по сети, и каждые 10 минут эта информация группируется в структуру под названием "блок". Еще через 10 минут генерируется новый блок, и этот блок автоматически присоединяется к предыдущему, так что блоки образуют *(цепочку)*.

Эта цепочка блоков отсортирована в хронологическом порядке и криптографически защищена таким образом, что ее **невозможно изменить**.

>Как мы уже говорили, **блокчейн – это история транзакция**. Это означает, что каждая когда-либо совершенная транзакция окончательна, ее нельзя изменить или вернуть, и поэтому с блокчейном надо соблюдать особую осторожность. Хорошей практикой является перепроверять адреса кошельков после копирования и проверять первые и последние несколько символов, чтобы убедиться, что адрес не был изменен каким-либо вредоносным ПО.

**Платформа облачного хранения данных** означает, что Sia – это платформа, позволяющая арендовать дисковое пространство в другой точке мира для создания своих собственных надежных и всегда доступных резервных копий данных.

Платформа использует **механизм консенсуса** *(способ достижения согласия о состоянии блокчейна)*, основанный на алгоритме **доказательства выполнения работы (PoW)**. Этот протокол был впервые представлен Bitcoin в 2009 году и принес нам процесс, известный как майнинг.

**Доказательство выполнения работы** означает, что майнерам приходится затрачивать значительные ресурсы, заключающиеся в электроэнергии и специальном *(зачастую созданном лишь с одной целью)* оборудовании, чтобы участвовать в поиске решения определенной математической задачи. Этот поиск подразумевает значительную долю *“везения”*, так как майнеры соревнуются между собой за то, кто найдет решение первым. Как только решение найдено, оно используется, чтобы "подписать" новый блок, который затем передается в сеть. Если сеть принимает его, то тот, кто нашел решение, получает **вознаграждение** в форме **Siacoin (SC)**, криптовалюты, используемой в сети Sia. Таким образом новые монеты появляются в сети и распространяются майнерами, чаще всего через многочисленные криптобиржи.

>Поскольку многие майнеры не хотят всецело зависеть от везения, они часто объединяются в **майнинг-пулы**. Если решение находит участник пула, вознаграждение пропорционально распределяется между всеми участниками на основании количества работы, выполненной каждым из них.

Все это означает, что майнеры предоставляют сети услугу. Они являются важной частью сети, но их можно заменить, если их намерения становятся враждебными и начинают угрожать сети. Это, в сочетании с наградой за блок, является хорошей мотивацией для того, чтобы действовать в лучших интересах сети. Быть честными и обеспечивать безопасность, потому что за это они получают награду. Действовать иначе может стоить намного дороже, чем любая возможная выгода.

Если хотите узнать больше, обратитесь к разделу [Руководство по майнингу]().

>Если вам интересно, что случилось бы, если бы абсолютное большинство майнеров потребовало потребовало изменить протокол, ознакомьтесь с историей неудавшегося форка Bitcoin под названием “SegWit2x”. Простыми словами, это была очень важная демонстрация того, что правила создают и охраняют узлы, а не майнеры, даже если за последними стоят крупнейшие компании мира криптовалют.

## Почему стоит использовать Sia?
Sia позволяет создать копию данных, к которой **только вы имеете доступ**. Ни правительства, ни регуляторы, ни даже хосты, хранящие **зашифрованные** фрагменты вашей информации, не могут получить к ней доступ и узнать, что это за информация или кому она принадлежит. Просто не могут. Если вы незнакомы с **шифрованием**, то это метод, использующий цифровой ключ *(вы можете считать его паролем)* для преобразования *(кодирования)* данных во что-то нечитаемое, и единственный способ их прочитать *(декодировать)* – это иметь ключ и знать, каким методом они были зашифрованы.

>Начиная с 2020 года, ПО Sia позволяет загружать данные в **Skynet**, который представляет собой слой публикации данных, использующий Sia в качестве слоя хранения данных. Он позволяет пользователям осуществлять хостинг приложений и делиться контентом без участия какого-либо сервера или иной инфраструктуры, в то же время обеспечивая **устойчивость к цензуре**. Это означает, что если вы хотите сделать вашу информацию общедоступной и позволить другим ее "прикреплять", вы можете это сделать, и в этом случае хост может прочесть информацию, которой вы делитесь (потому что вы сделали ее общедоступной). Чтобы узнать больше, ознакомьтесь с разделом [Введение в Skynet]().

Это свойство уже само по себе достаточно интересно, но есть и другой фактор помимо надежности и приватности. Технология Sia основана на открытых рыночных отношениях, когда **любой может стать хостом или арендатором** и установить свои собственные условия и цены. Благодаря этому, даже если спрос на Siacoin возрастет, и его цена подскочит, естественная конкуренция нормализует цены, и в любой момент времени вы будете платить более или менее постоянную цену по отношению к фиатным валютам (доллар, евро и др.).

>Вам даже не нужно спрашивать для этого разрешение. Sia имеет **открытый исходный код** и **не требует разрешений**. Любой может запустить узел и начать хостинг, аренду или разработку продуктов и сервисов на основе сети Sia. Вы можете найти множество руководств в других разделах этого веб-сайта.

То, что любой может стать хостом и предлагать другим в аренду свое неиспользуемое дисковое пространство, означает, что в мире будут не только датацентры, предлагающие высококачественный сервис по высоким ценам, но и частные лица, предлагающие сервис менее высокого качества (например, с более низкой скоростью доступа), но по более низкой цене. Начиная с октября 2020 года, хосты поддерживают SkyDB, изменяемую децентрализованную базу данных, которую может использовать любое приложение.

Вы можете спросить, где гарантия того, что ваша информация не пропадет, если такой хост вдруг исчезнет? Что ж, **хосты заинтересованы в том, чтобы хранить вашу информацию**, предоставляя залог, который замораживается на период действия ваших файловых контрактов. Если хосты потеряют вашу информацию, они потеряют и залог, который может быть в три раза больше, чем ожидаемое вознаграждение. Кроме того, по умолчанию Sia использует трехкратную **избыточность**. Это означает, что **если ваш файл разбит на 30 фрагментов, вам необходимы лишь любые 10 из них, чтобы восстановить файл**. Эти фрагменты хранятся на разных хостах, поэтому если хост недоступен, показатель избыточности временно уменьшается, и фрагменты автоматически реплицируются на других хостах, чтобы обеспечить трехкратную избыточность.

На практике это означает, что вы платите за хранение файлов втрое большей длины, чем у вас, но это все же значительно дешевле и надежнее, чем любое другое решение (в первую очередь, следует помнить о том, что главное – это децентрализация).

Вы можете задать и ваши собственные условия – например, требовать 16 *(что еще надежнее)* из 40 фрагментов с избыточностью 2.5, но установки по умолчанию уже и так достаточно приемлемы. Со временем, когда сеть разрастется и качество хостов вырастет, ожидается, что Sia перейдет к избыточности 1.5, чего вполне достаточно и что сделает хранение данных еще более доступным.

>Вы когда-нибудь интересовались, **почему существует минимальное вознаграждение за блок** в размере 30,000 SC, и вас беспокоит инфляция, вызываемая неограниченной эмиссией? Это было сделано преднамеренно, потому что в будущем ожидается, что большинство монет будут заморожены в контрактах. **Минимальное вознаграждение за блок гарантирует**, что всегда будет циркулировать достаточное количество монет, **чтобы сеть продолжала бесперебойную работу** и пользователи могли накапливать монеты, чтобы платить за хранение информации.

## Почему технология Sia важна для меня?
Она важна, потому что **вы беспокоитесь о своей информации и своей приватности**. Вы не хотите потерять семейные фотографии или важную информацию из-за того, что какой-то сервис прекратил работать *(помните Megaupload?)* или скомпрометировал себя утечками данных, или просто оказался недоступен в тот момент, когда он нужен вам больше всего. Вы не хотите быть изгнаны с какой-нибудь платформы.

С Sia этого не случится, и если трехкратная избыточность не дает вам спать по ночам, потому что вы боитесь потерять сверхважную информацию, то увеличьте ее, или даже создайте "белый список" конкретных хостов в конкретных регионах *(чтобы всегда иметь доступ к своим данным, даже если целые страны погрузятся во мрак)*. Даже в этом случае это **намного дешевле, чем традиционные решения**, но надежнее, чем все они, вместе взятые.

**У вас может быть неиспользуемое дисковое пространство** на домашнем сервере, работающем круглые сутки. Теперь вы можете начать хостинг и снизить свои операционные затраты, или даже получить прибыль. Если вам интересно, то мы рекомендуем начать с малого и ознакомиться с хостингом. Всегда можно подключить дополнительные объемы, когда вы приближаетесь к лимиту. Чтобы узнать больше, ознакомьтесь с разделом [Руководство по хостингу]().

Возможно, **вы разработчик, и у вас есть отличная идея**, или вы просто готовый учиться энтузиаст. Sia открывает целый мир новых возможностей и приложений, до сегодняшнего дня бывших невозможными, особенно с приходом Skynet, который позволяет разработчикам создавать приложения при помощи простого программного интерфейса, без необходимости в их хостинге. Вы можете найти больше информации в разделах [С чего начать](), [Создавайте с Sia]() и [Создавайте с Skynet]().

Очевидно, что именно разработчики первыми заметят новую возможность и создадут продукты, которые привлекут клиентов. Некоторые из этих продуктов, уже созданные Сообществом, можно увидеть в разделе [Примеры](). Это просто невероятно, потому что сегодня пользователи могут использовать продукты, созданные в децентрализованной сети, даже не зная того, как она работает, и не имея криптовалют. Сервисы могут управлять криптовалютными файловыми контрактами пользователей с оплатой в фиатной валюте. Это открывает миру криптовалют долгожданные возможности для более широкого принятия людьми во всем мире.

## Кто стоит за Sia, и как я могу быть уверен, что это всегда будет работать?
**До 2020 года технология Sia разрабатывалась Nebulous, Inc.**, компанией с венчурным капиталом, которая претворила все это в реальность **меньше, чем за 10 миллионов долларов**, собранных с 2015 года. Технология Sia всегда была более продвинута технически и лидировала в своей сфере, в то же время оставаясь в тени менее продвинутых проектов, воспользовавшихся шансом и собравших огромное количество денег во времена ICO.

**У Sia никогда не было ни ICO, ни премайнинга.** Все монеты были сгенерированы теми майнерами, кто был в этом заинтересован. В 2020 году команда разработчиков владела менее 0.1% всех SC. Разработчики мотивированы за счет владения дополнительным токеном сети, Siafund (больше об этом в разделе [Токеномика]()), который обеспечивает выплату своим владельцам части комиссий успешно завершенного файлового контракта в сети Sia. В то время как большинство других проектов собрали кучу денег в начале своего существования, с фокусом на хайпе и громких словах, и никогда не имели реального стимула когда-либо представить готовый продукт, Sia является полной противоположностью. Для того, чтобы Siafunds стали сколько-нибудь серьезным источником дохода, сеть должна вырасти многократно.

Распространенный повод для беспокойства – когда цена токена стагнирует, проект, вероятно, мертв. Однако цена ничего не говорит об уже достигнутом прогрессе. Кроме того, в разработке такой технологии нет коротких путей, и в первые годы она просто была еще не готова.

Проект Sia мог пойти по тому же пути, что и другие, и сосредоточиться на цене и маркетинге, но тогда в результате не было бы готового продукта. Для такого продукта важно взаимодействие с пользователем, а до 2019 года она не было возможно. Выпуск продукта в широкие массы мог принести непоправимый ущерб, потому что технология не была готова. Сегодня она готова. Пока еще есть что исправить и улучшить, но она вполне стабильна и имеет многообещающие перспективы.

Можете быть уверены: **Sia будет работать, потому что технология не зависит от разработчиков**. Сеть не требует разрешений и имеет открытый исходный код, ее может поддерживать любой. Если бы команда разработчиков вдруг исчезла, сеть продолжила бы работу, и кто-нибудь наверняка принял бы эстафету. По крайней мере, так было до сегодняшнего дня. С начала 2021 года разработка Sia переходит к вновь созданной **некоммерческой организации** под названием [Фонд Sia]().

> Комментарий от Covalent: Фраза "не зависит от разработчиков" может ввести в заблуждение. Разумеется, если разработчики вдруг покинут проект, сама сеть не рухнет. Но как и любая другая экосистема или ПО, системе **нужны** разработчики как клиентской, так и серверной инфраструктуры, иначе она истощится.

**Фонд Sia** будет финансироваться (форк ожидается к концу первого квартала 2021 года) за счет добавления 30,000 SC (тридцати тысяч монет) к награде за блок (более подробно можно прочитать в статье <a href="https://www.reddit.com/r/siacoin/comments/iox6ly/proposal_the_sia_foundation/" target="_blank" rel="noopener noreferrer">Предложение</a>, весьма положительно воспринятой Сообществом). В то время как вызванный этим рост инфляции будет незначительным (особенно по сравнению с большинством других проектов), это позволит Фонду сосредоточиться на разработке тех частей центральной технологии Sia, на которые компании с венчурным капиталом прежде было трудно выделить ресурсы.

Люди часто забывают о том, что все это было сделано командой с очень малым финансированием, и эта команда никогда и ничего за это не получала. И пока что так и есть сейчас. Фонд Sia – некоммерческая организация, которая должна предоставлять полный отчет о расходах. Ее возглавляет соучредитель Sia **Luke Champine**; ожидается, что со временем к нему присоединятся и другие представители.

Фонд будет использовать средства для того, чтобы сделать центральную технологию Sia более стабильной, эффективной и дружественной для пользователя. Наиболее востребованными являются исправления и улучшения **стабильности хоста**, **поддержка малых файлов** и **Utreexo**. Последняя особенность должна радикально сократить размер блокчейна и сделать возможными "облегченные" узлы. Это откроет целый мир новых возможностей для любых типов устройств. Кроме того, Фонд планирует предоставлять узлам, участвующим в сети Sia, **юридические услуги** и сжигать все монеты, которые он не смог потратить на **поддержание роста и благосостояния экосистемы**.

Официальный ресурс для общения с Фондом Sia – <a href="https://forum.sia.tech" target="_blank" rel="noopener noreferrer">Форум</a>.

**Skynet Labs** – новое название **Nebulous, Inc.**, компании, создавшей Sia; ее учредитель и генеральный директор – **David Vorick**. Так как это всего лишь ребрендинг, вся команда разработчиков осталась та же, за исключением Luke, который сосредоточился на ядре Sia.

Большую часть 2020 года Skynet Labs уже работала над решением задач, о которых уже несколько лет говорило Сообщество. Способствуя широкому принятию Sia, Skynet является самым крупным продуктом этой технологии, в которую он встроен напрямую. В то время как Sia стремится конкурировать на рынке децентрализованного облачного хранения информации, Skynet конкурирует со всем централизованным интернетом и предлагает его альтернативу. Мы еще увидим, как будут развиваться дела, но совершенно ясно, что Skynet предлагает **привлекательный простор для разработчиков, создателей контента и их подписчиков**. Он предлагает пользователям совершенно новый способ использования интернета, в котором они сами контролируют свою собственную информацию и решают, какие (клиентские) приложения могут получать к ним доступ.

В конце 2020 года компания взяла на работу еще нескольких сотрудников. Интересный факт – число сотрудников, занятых маркетингом, выросло с нуля до 4 всего лишь за последние два месяца 2020 года, и, согласно ведомой разработчиками статистике, Skynet претерпевает значительный рост, примерно на 40% в месяц.

Но что все это означает? А то, что это разделение хорошо для всех, кто заинтересован в Sia. Это не означает, что проект заброшен, и разработчики из него уходят. Впервые в истории Sia проект сохраняет присутствие сразу на двух полях битвы. Фонд Sia будет действовать в лучших интересах проекта Sia, технологии, экосистемы и участников. А Skynet будет основной движущей силой массового признания.

Так как Skynet основан на Sia, он использует Siacoin (SC). Он повышает осведомленность о токене и спрос на него среди пользователей, которые хотят сохранить информацию, среди хостов, которые используют его в качестве залога и вознаграждения, и среди Порталов Skynet, которые оплачивают действия своих пользователей. И все это помимо той единственной сферы применения, которая есть у большинства проектов – биржевых спекуляций. Чем шире сеть и чем больше объем хранимой и скачиваемой информации, тем больше вознаграждения будут получать держатели Siafund. Это выгода для всех тех, кто вовлечен в проект. Это воспринимается как правильная мотивация, и весь коллектив создателей этого веб-сайта смотрит в будущее с энтузиазмом и предвкушением.

Куда направиться дальше? Попробуйте [Введение в Skynet]().

>Больше информации о первых шагах Sia можно найти в разделе [История]().

*Автор: Danger (9 января 2021 г.)
Обновлено: Covalent (9 марта 2021 г.)*