<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <!-- UIkit CSS -->
    <link rel="stylesheet" href="./css/uikit.min.css" />

    <!-- UIkit JS -->
    <script src="./js/uikit.min.js"></script>
    <script src="./js/uikit-icons.min.js"></script>
    <link rel="icon" href="./favicon.ico" type="image/x-icon">
    <title>Веб-аналитика</title>
</head>
<body class="uk-text-justify">    

    <!--<a href="#offcanvas-slide"  uk-icon="icon: menu"  uk-sticky uk-padding></a>-->
    <div uk-sticky>
        <button class="uk-button uk-button-text uk-padding-small uk-button-large uk-position-top-right" type="button" uk-toggle="target: #offcanvas-slide" uk-icon="icon: menu;  ratio: 1.5"></button>
    </div>    

    <nav id="offcanvas-slide" uk-offcanvas="flip: true; overlay: true">
        <div class="uk-offcanvas-bar">
            <button class="uk-offcanvas-close" type="button" uk-close></button>
            <ul class="uk-nav uk-nav-default">
                <li><a href="#link-main-points">Общие положения</a></li>
                <li><a href="#link-usage">Использование веб-аналитики</a></li>
                <li><a href="#link-methods">Методы веб-аналитики</a></li>
                <li><a href="#link-main-instruments">Инструменты веб-аналитики</a></li>
                <li><a href="#link-main-exmpl">Примеры инструментов веб-аналитики</a></li>
                <li><a href="#link-main-res">Выводы</a></li>
                <li class="uk-nav-divider"></li>
                <li><a href="#link-main-difinitions">Основные термины веб-аналитики</a></li>
            </ul>
    
        </div>
    </nav>        
    <header>
        <h2 class="uk-heading-divider uk-padding"><a class="uk-link-text" uk-tooltip="title: (англ. Web analytics); pos: bottom">Веб-аналитика</a></h2>
    </header>
    <div class="uk-padding-large uk-padding-remove-bottom uk-padding-remove-top">       
        <h3 id="link-main-points" class="uk-heading-bullet">Общие положения</h3>
        <div class="uk-child-width-1-2@m uk-grid-match" uk-grid>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-def; mode: click">
                    <h3 class="uk-card-title uk-text-light">Определение</h3>
                    <p>Система измерения, сбора, анализа, представления и интерпретации информации о посетителях веб-сайтов с целью их улучшения и оптимизации. </p>
                    <p class="toggle-hover-def" hidden>Основной задачей веб-аналитики является мониторинг посещаемости веб-сайтов, на основании данных которого определяется аудитория сайта и изучается поведение посетителей для принятия решений по развитию и расширению функциональных возможностей веб-ресурса. Веб-аналитика позволяет не только работать над улучшением сайтов, но и проводить работы по оптимизации бюджета на онлайн-продвижение.</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-sphere; mode: click">
                    <h3 class="uk-card-title uk-text-light">Область применения</h3>
                    <p>
                        Веб-аналитика помогает во многих аспектах развития сайта и онлайн-продвижения. <span class="toggle-hover-sphere" hidden> Вот основные из них: </span>                         
                    </p>
                    <ul class="uk-list uk-list-divider uk-padding uk-padding-remove-bottom uk-padding-remove-top toggle-hover-sphere" hidden>
                        <li>Развитие функциональности сайта на основании тенденций в поведении посетителей</li>
                        <li>Оценка эффективности рекламных кампаний и поискового продвижения в интернете</li>
                        <li>Выявление проблемных мест в структуре, навигации и контенте сайта</li>
                        <li>Оптимизация продуктовой линейки, представленной на сайте</li>
                    </ul>   
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-dim; mode: click">
                    <h3 class="uk-card-title uk-text-light">Показатели веб-аналитики </h3>
                    <p>
                        Статистика посещаемости разделов и веб-страниц сайта позволяет проанализировать большое количество параметров сайта. <span class="toggle-hover-dim" hidden>К примеру:</span>                          
                    </p>
                    <ul class="uk-list uk-list-divider uk-padding uk-padding-remove-bottom uk-padding-remove-top toggle-hover-dim" hidden>
                        <li>Глубина просмотров (то есть, сколько страниц было просмотрено пользователем)</li>
                        <li>Ключевые слова и фразы, по которым посетители находят сайт в поисковых системах</li>
                        <li>Географию посетителей</li>
                        <li>Время, проведенное на веб-странице </li>
                        <li>Переходы между веб-страницами</li>
                        <li>Демографические и социальные признаки посетителей</li>
                        <li>Удобство навигации сайта для посетителей</li>
                        <li>Источник перехода (с какого сайта, по какому объявлению, запросу и т. д.)</li>
                        <li>Выполнение целевых действий (например, нажатие кнопок или посещение страниц)</li>
                    </ul>   
                </div>
            </div>
        </div>
    </div>
    <hr class="uk-divider-icon">
    <div class="uk-padding-large uk-padding-remove-bottom uk-padding-remove-top">
        <h3 id="link-usage" class="uk-heading-bullet">Использование веб-аналитики</h3>
        <div class="uk-card uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
            <ul uk-tab="connect: .switcher-container; animation: uk-animation-fade">
                <li class="uk-active"><a href="">Анализ аудитории</a></li>
                <li><a href="">Анализ контента</a></li>
            </ul>
            <ul class="uk-switcher switcher-container uk-margin">
                <li>
                    <div class="uk-child-width-1-2@m uk-grid-match" uk-grid>
                        <div>
                            <div class="uk-card uk-card-body uk-card-secondary">
                                <h3 class="uk-card-title uk-text-light">Выявление целевой аудитории</h3>
                                <p>Если проект находится на ранее стадии продвижения, и точный портрет потенциального клиента еще не составлен, то полученные с помощью web-анализа данные помогут в этом. Изучая интересы, демографические и социальные особенности существующих клиентов и их поведения в сети, можно более точно определить целевую аудиторию.</p>
                            </div> 
                        </div>
                        <div>
                            <div class="uk-card uk-card-body uk-card-secondary">
                                <h3 class="uk-card-title uk-text-light">Разделение аудитории на сегменты</h3>
                                <p>Статистика и анализ позволяют сегментировать аудиторию по разным признакам, к примеру, по среднему чеку. Изучив особенности каждого сегмента, появялется возможность подобрать наиболее эффективные объявления, сделать более качественное и индивидуальное предложение каждой категории людей.</p>
                            </div> 
                        </div>
                    </div>
                </li>
                <li>
                    <div class="uk-child-width-1-2@m uk-grid-match" uk-grid>
                        <div>
                            <div class="uk-card uk-card-body uk-card-secondary">
                                <h3 class="uk-card-title uk-text-light">Оптимизация рекламного бюджета</h3>
                                <p>Существующие компании не обладают неисчерпаемыми ресурсами. Изучение и анализ данных по рекламным кампаниям позволяют выявить наиболее эффективные площадки и стратегии и отказаться от неэффективных показов, которые впустую тратят бюджет.</p>
                            </div> 
                        </div>
                        <div>
                            <div class="uk-card uk-card-body uk-card-secondary">
                                <h3 class="uk-card-title uk-text-light">Оптимизация контента</h3>
                                <p>Изучая трафик и источники переходов, можно понять, соответствует ли содержимое страниц сайта тому, что искал пользователь, какими потребностями обладает целевая аудитория, и что она ищет. На основе этих данных оптимизируется контент на сайте. </p>
                            </div> 
                        </div>
                        <div>
                            <div class="uk-card uk-card-body uk-card-secondary">
                                <h3 class="uk-card-title uk-text-light">Подбор оптимальных стратегий</h3>
                                <p>Изучение аналитических и статистических данных позволяет находить и использовать наиболее эффективные стратегии показов, продвижения и рекламы.</p>
                            </div> 
                        </div>
                    </div>
                </li>
            </ul>   
        </div>
    </div>
    <hr class="uk-divider-icon">
    <div class="uk-padding-large uk-padding-remove-bottom uk-padding-remove-top uk-text-left">
        <h3 id="link-methods" class="uk-heading-bullet">Методы веб-аналитики</h3>
        <div class="uk-child-width-1-3@s uk-grid-match" uk-grid>
            <div>
                <div class="uk-card uk-card-default uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p><span class="uk-text-bold">Анализ посещаемости сайта:</span> статистика, тенденции, абсолютные и относительные показатели.</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p><span class="uk-text-bold">Анализ данных из электронной торговли:</span> средний чек, популярные товары, доход в разрезе каналов привлечения трафика.</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p><span class="uk-text-bold">Анализ юзабилити:</span> анализ плотности щелчков, конверсионных путей посетителей по сайту, анализ скроллинга.</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p><span class="uk-text-bold">Анализ поведения посетителей на странице:</span> взаимодействие с формами, совершение микро и макро конверсий.</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p><span class="uk-text-bold">Бенчмаркинг.</span> Сравнение с общими тенденциями и с конкурентами с помощью независимых платформ (Alexa, GemiusAudience, Google Trends).</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p><span class="uk-text-bold">Сквозная аналитика.</span> Отслеживание полного пути пользователя от просмотра рекламы и до завершения сделки, а также повторных продаж.</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p><span class="uk-text-bold">Сбор cookies.</span> Это позволяет аналитическим сервисам сопоставлять активность пользователя на веб-ресурсах, где он предоставлял личную информацию.</p>
                </div>
            </div>
        </div>
    </div>
    <hr class="uk-divider-icon">
    <div class="uk-padding-large uk-padding-remove-bottom uk-padding-remove-top">       
        <h3 id="link-main-instruments" class="uk-heading-bullet">Инструменты веб-аналитики</h3>
        <div class="uk-child-width-1-2@m uk-grid-match" uk-grid>
            <div>
                <div class="uk-card uk-card-secondary uk-card-body" uk-scrollspy="cls: uk-animation-slide-left; repeat: true">
                    <h3 class="uk-card-title uk-text-light">Счетчики</h3>
                    <p><span class="uk-text-bold">Счетчики</span> — это внешние программы. Для получения статистики на веб-страницы сайта устанавливается небольшой фрагмент кода (обычно 1-2 килобайт). Счетчики засчитывают открытие страницы только после её загрузки. Благодаря этому они могут учитывать посещение кешированных страниц, что невозможно осуществить с помощью лог-анализаторов. Можно получить доступ не только к стандартной информации по посещениям, но и к числу покупок, кликам по определённым кнопкам и тому подобное. Компании, у которых нет в наличие серверов, могут хранить информацию для веб-аналитики, если используют счетчики. Счетчики в настоящий момент являются стандартом веб-аналитики.</p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-secondary uk-card-body" uk-scrollspy="cls: uk-animation-slide-right; repeat: true">
                    <h3 class="uk-card-title uk-text-light">Лог-анализаторы</h3>
                    <p><span class="uk-text-bold">Лог-анализаторы</span> — внутренние программы, собирающие накопленные сервером данные. Лог-анализаторы позволяют собирать статистику ничего не меняя на сайте. Веб-сервер самостоятельно создает лог-файлы и сохраняет их на сервер. Данные хранятся на серверах компании в стандартном формате. Это позволяет компаниям создавать свои программы для анализа данных, переходить на обновления именно в тот момент, когда им это необходимо. В лог-файлах содержится информация о поведении поисковых роботов, что позволяет грамотно оценить работы по SЕО оптимизации.
                </div>
            </div>
        </div>
    </div>
    <hr class="uk-divider-icon">
    <div class="uk-padding-large uk-padding-remove-bottom uk-padding-remove-top uk-text-left">       
        <h3 id="link-main-exmpl" class="uk-heading-bullet">Примеры инструментов веб-аналитики</h3>
        <h3 class="uk-heading-line uk-text-center"><span>Анализаторы логов</span></h3>
        <table class="uk-table uk-table-divider" uk-scrollspy="cls: uk-animation-slide-left; repeat: true">
            <thead>
                <tr>
                    <th>Инструмент</th>
                    <th>Определение</th>                    
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Webtrends</td>
                    <td>Обеспечивает цифровую аналитику, оптимизацию и программное обеспечение, связанное с цифровым маркетингом и электронной коммерцией.</td>
                <tr>
                    <td>Webalizer</td>
                    <td>Прикладная программа генерирующая HTML-страницы со статистикой о работе веб-сайта на основе файлов регистрации (access.log) событий веб-сервера.</td>                    
                </tr>
                <tr>
                    <td>AWStats</td>
                    <td>Обеспечивает цифровую аналитику, оптимизацию и программное обеспечение, связанное с цифровым маркетингом и электронной коммерцией.</td>                    
                </tr>
        </table>
        <h3 class="uk-heading-line uk-text-center"><span>Системы веб-аналитики</span></h3>
        <table class="uk-table uk-table-divider" uk-scrollspy="cls: uk-animation-slide-right; repeat: true">
            <thead>
                <tr>
                    <th>Инструмент</th>
                    <th>Определение</th>                    
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Google Analytics</td>
                    <td>Бесплатный сервис, предоставляемый Google для создания детальной статистики посетителей веб-сайтов.</td>
                <tr>
                    <td>Matomo</td>
                    <td>Cистема веб-аналитики с открытым исходным кодом.</td>                    
                </tr>
                <tr>
                    <td>Яндекс.Метрика</td>
                    <td>Бесплатный интернет-сервис компании Яндекс, предназначенный для оценки посещаемости веб-сайтов и анализа поведения пользователей.</td>                    
                </tr>
                <tr>
                    <td>Рейтинг@Mail.ru</td>
                    <td>Система веб-аналитики, собирающая данные о посетителях веб-сайтов и их устройствах.</td>                    
                </tr>
        </table>
    </div>
    <hr class="uk-divider-icon">
    <div class="uk-padding-large uk-padding-remove-bottom uk-padding-remove-top uk-text-left">       
        <h3 id="link-main-res" class="uk-heading-bullet">Выводы</h3>
        <div class="uk-card uk-card-secondary uk-card-body" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
            <p>
                Без периодического проведения анализа и просмотра статистики невозможно дальнейшее успешное развитие проекта. Каждый аналитический цикл позволяет выявить недостатки, указать на сильные стороны веб-ресурса и проводимой рекламной кампании, а также помогает принимать дальнейшие решения. Веб аналитика – это основа, на которую опирается веб-мастер для принятия дальнейших решений. 
            </p>
        </div>
    </div>
    <hr class="uk-divider-icon">
    <div class="uk-padding-large uk-padding-remove-bottom uk-padding-remove-top uk-text-left">       
        <h3 id="link-main-difinitions" class="uk-heading-bullet">Основные термины веб-аналитики</h3>
        <div class="uk-child-width-1-3@m uk-grid-match" uk-grid>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-1; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Показатель отказов </span>(англ. Bounce rate)
                        <span class="toggle-hover-definition-1" hidden> 
                            — процент посещений одной страницы без каких-либо других действий на этой ней, или сеанс, в котором был только один запрос к серверу.
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-2; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Путь клика </span>(англ. Click path)
                        <span class="toggle-hover-definition-2" hidden> 
                            — хронологическая последовательность просмотров страниц в рамках посещения или сеанса.
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-3; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Хит</span> (англ. Hit)
                        <span class="toggle-hover-definition-3" hidden> 
                            — процент посещений одной страницы без каких-либо других действий на этой ней, или сеанс, в котором был только один запрос к серверу.
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-4; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Путь клика</span> (англ. Click path)
                        <span class="toggle-hover-definition-4" hidden> 
                            — запрос файла с веб-сервера (например, веб-страница, изображение, JavaScript или каскадная таблица стилей).
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-5; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true"
                    <p>
                        <span class="uk-text-bold">Показ страницы</span> (англ. Pageview) 
                        <span class="toggle-hover-definition-5" hidden> 
                            — показ одной страницы сайта, другими словами, запрос на загрузку одного HTML-файла (веб-страницы) интернет-сайта. Один показ страницы может генерировать несколько просмотров, поскольку все файлы изображений, .js и .css также запрашиваются с веб-сервера. 
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-6; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Уникальный посетитель / Уникальный пользователь </span>(англ. Unique Visitor / Unique User ) 
                        <span class="toggle-hover-definition-6" hidden> 
                            — клиент с уникальной идентификацией, который генерирует просмотры страниц или посещений в течение определенного периода времени (например, дня, недели или месяца). Идентификация обычно осуществляется с помощью постоянного файла cookie, который был размещен на компьютере с помощью кода страницы сайта. 
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-7; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Посещение / сеанс</span> (англ. Visit / Session)
                        <span class="toggle-hover-definition-7" hidden> 
                            — период времени, в течение которого пользователь активно работает с веб-сайтом или приложением. К сеансу привязываются все данные об использовании сайта или приложения: просмотры страниц, события, транзакции электронной торговли и т.д. 
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-8; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Активное время / Время взаимодействия </span>(англ. Active Time / Engagement Time)
                        <span class="toggle-hover-definition-8" hidden> 
                            — среднее количество времени, которое посетители тратят, фактически взаимодействуя с контентом на веб-странице, рассчитывается на основе движений мыши, щелчков, зависаний и прокрутки. 
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-9; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Клик</span>
                        <span class="toggle-hover-definition-9" hidden> 
                            — событие, которое происходит, когда пользователь щелкает по элементу управления.
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-10; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Событие</span>
                        <span class="toggle-hover-definition-10" hidden> 
                            — это отдельное действие или цепочка действий, которые происходят на веб-сайте. Просмотр страницы — это тип события. 
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-11; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Первый визит</span> (англ. First Visit)
                        <span class="toggle-hover-definition-11" hidden> 
                            — посещение сайта уникально идентифицированным клиентом, который теоретически не совершал ранее переходов на этот веб-ресурс. 
                        </span>
                    </p>
                </div>
            </div>
            <div>
                <div class="uk-card uk-card-default uk-card-body uk-card-hover" uk-toggle="target: .toggle-hover-definition-12; mode: hover" uk-scrollspy="cls: uk-animation-slide-bottom; repeat: true">
                    <p>
                        <span class="uk-text-bold">Тепловая карта</span> (англ. Site Overlay)
                        <span class="toggle-hover-definition-12" hidden> 
                            — это метод отчета, при котором статистика (клики) или «горячие точки» накладываются по физическому расположению на визуальный снимок веб-страницы, тепловая карта отображает активность пользователей на сайте.
                        </span>
                    </p>
                </div>
            </div>
        </div>
    </div>
    <footer class="uk-section uk-section-secondary uk-margin-large uk-margin-remove-bottom uk-padding-large">
            
        <div class="uk-container">
    
            <h3>Доклад по веб-аналитике</h3>
    
            <div class="uk-grid-match uk-child-width-1-5@m" uk-grid>
                <div>
                    <p>Группа Р42622</p>
                </div>
                <div>
                    <p>Демашов Д.</p>
                </div>
            </div>
    
        </div>
    </footer>
</body>
</html>
