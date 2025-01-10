# SVN_Searcher

Для работы необходимо при установке TortoiseSVN любой версии (можно не обновлять сам Tortoise, просто через Modify) выставить галочку "command line tools" и закончить установку.
Сама программа из серии Portable (скачиваешь и запускаешь).

# v1.0.0

Добавлены поля аутентификации и способ вводить адрес svn и искать файл по имени.

# v2.0.0 

Как пользоваться и какие возможности:

В "Authentication" части программы в поля "Enter Login" и "Enter Password" необходимо ввести данные для входа на SVN ресурс. 

Эти данные вводятся один раз при первом запуске программы, дальше они сохраняются автоматически в памяти программы. Не бойтесь ввести что-то не то, вы всегда сможете отредактировать его. Через каждые 3 месяца, когда сбрасывается пароль, просто обновляете его и работаете дальше. 

Галочка справа от пароля дает возможность показать пароль, чтобы убедиться в верности написания (по дефолту скрыто).

В "Search settings" части программы в поле "Enter SVN Repository Path" необходимо ввести ссылку на репозиторий, на котором необходимо совершить поиск. Можно указывать как общий корневой путь, так и конкретно в какую-то папку на ресурсе.

В поле "Enter File Name" вводится название искомого файла, либо формат, либо можно написать просто символ точки "." без кавычек, что позволит показать в списке все файлы, которые находятся по указанному пути.

После заполнения этих полей можно нажимать кнопку "Search" и, если все вышеуказанные шаги сделаны верно и у вас есть доступ к репозиторию, вы увидите процесс добавления файлов в окошке программы.
Чтобы прекратить поиск на любом этапе нажмите кнопку "Stop".

Работа со списком файлов:

После того, как вам выдался список из файлов, вы можете: 
	- отсортировать по алфавиту и формату, нажав на кнопку "Name+Type" рядом с надписью Sort by;
	- сделать более точный поиск по уже найденным файлам. Рядом с надписью "Filter" вы вводите слова или часть слов, по которым необходимо найти файл среди уже найденных;
	- перейти сразу на закачку файла (для этого нужно кликнуть два раза по необходимому файлу, после чего у вас откроется ссылка в браузере по умолчанию);
	- скопировать полный путь к файлу или только к папке, в которой он лежит (для этого нужно нажать правую кнопку мыши на необходимом файле, после чего у вас появится всплывающее окно с двумя выборами: "Copy Full Path" - скопировать прямую ссылку на файл; "Copy Directory Path" - скопировать прямую ссылку на папку).

Рядом с надписью Last File можно отслеживать процесс поиска.




# v2.0.1 (hotfix)

Исправлено: 

- была ошибка сортировки по введенной информации в поле "Enter File Name". Введенные данные не учитывались при поиске, процесс поиска запускался по всему указанному пути "Enter SVN Repository Path";

- внизу в строке "Last File" отображался только последний добавленный в список файл, тогда как должен показываться процесс перебирания файлов;

- подкорректирован фильтр (была ошибка, когда он учитывал буквы и части слов, что находятся в расширении файла); 

- в окошко с найденными элементами добавлен горизонтальный скролл;




# v2.1

Удалено:

1) Поля аутентификации с главного рабочего окна. Теперь они находятся в верхнем меню во вкладке "Login".

Добавлено: 

1) Верхнее меню с двумя вкладками - "Login" и "About". Ввод логина и пароля теперь проводится в окне, которое открывается после нажатия на вкладку "Login". Сама процедура осталась неизменной. Сделано это для того, чтобы скрыть постоянные не нужные поля от своих глаз или чужих.  

2) Во вкладке "About" вы можете узнать какая версия программы у вас на данный момент и есть ли новое обновление. Если обновление есть, то вам будет предложено его загрузить. Так же, уведомление о наличии новой версии теперь появляется при запуске программы.

3) Чекбоксы переключения чуствительности к регистру:

	- справа от основного поискового поля есть переключаемый чекбокс, который позволяет учитывать или не учитывать регистр в запросе;

	- справа от текстового поля фильтра есть переключаемый чекбокс, который позволяет учитывать или не учитывать регистр в уточненном тексте;

4) Теперь появилась возможность предпросмотра изображений. Это поле находится справа от списка элементов. Достаточно один раз нажать на желаемый файл. На данный момент формат .PSD и .TGA не поддерживается. С новым обновлением эта проблема будет решена.

5) Если нажать на изображение, то его можно приблизить. Закрыть окно можно нажав ещё один раз либо крестиком в правом верхнем углу.

6) Во вкладке "About" есть ссылки на GitHub, где можно ознакомиться со всеми обновлениеями, а также моя почта для предложений по улучшению софта.


ВАЖНО!!!

Хочу поблагодарить всех, кто активно пользуется программой и помогает её улучшить!




