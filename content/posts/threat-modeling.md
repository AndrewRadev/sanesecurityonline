---
title: "Моделиране на заплахи"
slug: "модерлиране на заплахи"
date: 2018-01-15T20:44:52+02:00
draft: false
---

Моделирането на заплахи е похват при проектирането и одитирането на сигурността
на различни видове (най-често информационни) системи. В общия си вид това е
процес по изследване и описване на възможните заплахи за сигурността на
въпросната система, която може да бъде произволно сложна.

# Как това засяга обикновени потребители?

Опростен вариант на моделиране на заплахи може да бъде приложен към начина, по
който хората използват различни технологии и онлайн системи в ежедневието си.
Най-общо казано, добра идея е човек да си задава следните въпроси относно онлайн
присъствието и поведението си:

 * Според начина ми на живот, контактите ми и начина ми на ползване на онлайн
   услуги, какви възможни заплахи съществуват за сигурността на информацията ми
   онлайн или на различни физически устройства, които ползвам?
 * Има ли разлика между тези опасности що се отнася до разделението им между
   такива засягащи личното ми пространство и личния ми живот и такива засягащи
   служебния ми живот? Има ли друг тип разделение, което може да има смисъл,
   например между различни социални групи, от които съм част?
 * Каква е възможността да се случат различните заплахи? Кои от тях са почти
   неминуеми и кои, макар и теоретично възможни са изключително малко вероятни?
 * Какъв тип (време, пари, учене на нови инструменти, причиняване на неудобство)
   и колко голяма инвестиция е необходима, за да се предпазя от различните
   видове заплахи?
 * Какви биха били щетите при неуспешно предпазване
 * **Къде е границата на допустим риск, който ще приема?**
 * …

Целта на този списък далеч не е да бъде изчерпателен, а по-скоро да даде насока
за това за какво да мислим що се отнася до сигурността ни.

Ще разгледаме примери свързани с отделните въпроси, за да стане малко по-ясно
защо има смисъл да мислим за тях. В бъдещи публикации ще разгледаме в повече
детайли някои видове заплахи, които биха били от по-съществено значение за
повечето хора, както и прости ефективни начини за решаването на проблемите
произтичащи от тях.

### Какви са възможните заплахи?

Няма дефиниция на това какво може или не може да бъде разглеждано като заплаха.
Очаква се, че човек си поставя някакви разумни граници при изграждането на
един модел на заплахи, но тези граници могат да бъдат плаващи.

Ето няколко възможни заплахи, за които може да се мисли (малко по-късно ще се
върнем към тях при избирането на граница за допустим риск):

 * В кратки, но неизбежни периоди е възможно телефона и/или лаптопа ми да бъдат
   включени докато аз не съм наоколо и не знам какво се случва с тях.
 * Някой може да открадне телефона ми в градския транспорт
 * По невнимание или от незнание мога да заразя телефона или лаптопа си с вирус,
   който да даде достъп до устройствата ми на трети лица.
 * Кадърен и силно мотивиран хакер може да се опита да компрометира мое
   устройство, тъй като аз по някаква причина съм важен.
 * Различни държавни и/или международни служби могат да ме таргетират лично, с
   цел да ме компрометират или да разберат информация, до която имам достъп.

Очевидно е, че тези твърдения варират доста и всъщност не е нужно да знаете
какво е моделиране на заплахи, за да се досети човек, че някои от тях заслужават
повече внимание от други.

### Какви контекстуални разлики съществуват?

Лесен за описване и разбиране пример е именно разделението между данни, достъпът
до които е свързан със служебни си задължения и лични данни.

Лични данни могат да бъдат съобщения с членове на семейството или приятели,
лични снимки, видеа, информация за лични финанси, притежавани имоти и прочее.

Служебни данни от друга страна биха били документи за финансови движения на
работодателя, различни договори, документи за собственост или документи за
вътрешна употреба, описания и планове за проекти и бъдещи или текущо развиващи
се начинания.

По различни причини е възможно в един от двата контекста да съществува по-голям
риск от колкото в другия. В общия случай по-вероятна заплаха е някой да цели
достъп до данните на компания от колкото лична информация на даден човек.

Това обаче също е контекстно зависимо само по себе си. В някои случаи личната
информация на обществени личности може да представлява интерес за нападатели,
по ред причини, от обикновени папарашки подбуди до желанието да притежават
информация, която им позволява да изнудват въпросните хора.

В някои случаи атака срещу нечии личен акаунт може да бъде инструмент за
достигане до служебна информация притежавана от въпросния човек. Като
„прескачането“ от личния към служебния контекст може да се случи или с различни
технически средства, или чрез психологически похвати като социално инженерство
или изнудване.

Добре е заплахите да бъдат оценявани като се имат предвид такъв тип различни
контексти.

### Каква е вероятността на различни заплахи?

Всяка една от заплахите, споменати по-горе е реална. Поне до толкова до колкото
съществуват хора, за които тези заплахи са част от ежедневието им и нещо, с
което трябва да се съобразяват, ако искат да не станат техни жертви.

В същото време обаче някои от тези заплахи изглеждат малко вероятни за повечето
хора. Докато несъмнено съществуват хора, които са обект на целенасочен шпионаж
от различни правителствени и международни организации, притежаващи невероятни
ресурси и лостове за упражняване на контрол, то за средно статистически човек
опасността от кражба в градския транспорт е далеч по-реална.

###### Кражба / загуба
За да защити информацията на телефона си в случай на кражба или изгубване човек
може да криптира информацията си на него, така че да се изисква въвеждането на
код или парола, за достъп до нея, дори и запомнящото устройство да бъде извадено
от телефона. Това е бърза процедура, за която популярните съвременни операционни
системи за мобилни телефони имат лесен за използване интерфейс.

Тоест, имаме относително вероятна заплаха, за защита от която е нужно полагането
на доста малко усилие и практически никакви неудобства, допълнителни разходи или
нужда от научаване на нови умения за работа със специфични инструменти за
сигурност.

###### Правителствени служби, огромни организации
Заплахата от такъв тип нападатели е реална, тъй като съществуват хора, на които
това се случва. Както вече отбелязахме обаче, за огромна част от хората тази
заплаха всъщност е доста малко вероятна. В същото време обаче, става въпрос за
потенциални нападатели, които разполагат със завидни средства, както технически
така и финансови. Това ще рече, е за **поне бегло** ефективна защита от такъв
тип заплаха най-вероятно би било нужно сравнимо ниво на техническа експертиза.
Най-вероятно познаването и използването на редица специфични инструменти,
прилагане на определен тип практики по оперативна сигурност, както и сдобиването
с конкретен тип устройства, които позволяват значително по-добри нива на
изолация и контрол над всички аспекти на функционирането им.

Тук имаме точно обратния пример на предишния: доста малко вероятна заплаха,
защитата от която обаче изисква доста големи инвестиции на време и пари,
създаване на ред неудобства с цел по-високо ниво на сигурност, придобиване на
не тривиални умения.

Съвсем съвсем на кратко, може да си мислим за следното онагледяване:

![за какво да ни пука](/images/wtgafa.svg)

### Какви биха били щетите?

За да можем да мислим за това колко си заслужава да вложим в предпазването от
определен вид заплахи е нужно да помислим и колко е важно това, което се
опитваме да предпазваме от тях.

Ето други два относително крайни сценарии, с които може да онагледим идеята:

###### Електронно банкиране
Относително нормална практика вече е хората да използват телефоните или
компютрите си, за да извършват различни банкови операции, били те само проверки
на състояния на сметки или преводи на пари.
Потенциален недобронамерен достъп до система за електронно банкиране може да има
сериозни последици, които буквално да струват на жертвата огромни количества
пари.
Що се отнася до акаунтите в подобни системи за електронно банкиране или всякакъв
друг вид разплащателни системи, които дават възможност за опериране с пари от
нечие име, полагането на усилия за поддържане на добро ниво на сигурност е
безспорна необходимост.


###### Еднократен email акаунт

Нормална, а в някои случаи дори разумна, практика може да бъде създаването на
еднократни email адреси за ползването на някои услуги, които изискват email при
регистрация. Такъв тип еднократни акаунти, често пъти могат да бъдат използвани
в рамките на няколко дена или дори няколко часа, докато е нужна въпросната
услуга. След това никога повече няма да бъдат ползвани, като и самите те нямат
никаква връзка с останалите профили на човека, който ги е създал.
В този случай твърде висока инвестиция в сигурността на нещо краткотрайно, което
няма реална стойност и не е свързано по никакъв смислен начин с личността на
притежателя си, не прави много смисъл.

### Къде е границата на допустим риск?

Този въпрос не е тривиален и отговора на него до голяма степен е въпрос на лична
преценка. Може да се говори за ниво на „санитарен минимум“ по адрес на усилията,
които полагаме за опазване на информацията си в електронна форма, но със
сигурност няма ясен консенсус за това къде точно е това ниво.

Освен за тези, които знаят, че не спадат към средностатистическата категория,
границата на допустим риск за повечето хора (според крайно грубите очертания на
горната графика) логично би била някъде в този диапазон:

![къде да спре да ни пука](/images/wtgafa-boundaries.svg)

## Лесните решения

В днешно време все повече и повече компании предлагащи онлайн услуги или
различни видове персонални устройства, все повече наблягат на имплементирането
на различни видове предпазни мерки срещу най-вероятните видове заплахи. Повечето
съвременни устройства поддържат някакъв тип криптиране на цялото си запаметяващо
устройство (Full Disk Encryption), а онлайн услугите все по-масово имплементират
двуфакторни форми на идентификация (2 Factor Authentication).

Тези инструменти се усъвършенстват непрекъснато и тяхната използваемост се
подобрява постоянно. Това ги прави все по-достъпни и ефективни начини да
защитаваме дигиталната си информация в различни потенциално опасни ситуации и да
гарантираме, че до нея имаме достъп само ние и хората, които искаме да имат
достъп.
