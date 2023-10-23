# practice2k23
Итак, доброго времени. Я являюсь студентом Стерлитамакского Многопрофильного Профессионального Колледжа, и в дальнейшем в данном каталоге заданий, я буду записывать всю свою информацию здесь.
Вся наша работа начинается с виртуальных машин, у каждого студента есть своя собственная машина, где в дальнейшем проходит вся работа над материалом.
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/0423e75d-467d-4597-94ae-5bd593d14cab)
В дальнейшем для продолжения работы, нам нужно загрузить пакеты для ОС (операционных систем), и далее уже проводить установку.
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/5c280866-047b-40ca-8d43-5670f0f710ee) с помощью данной кнопки, проводиться установка сами ВМ (виртуальных машин), где, как я уже говорил, далее будет проводиться вся работа над материалом.
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/c18a59b6-3135-4e67-ae86-211551e715af) конкретно в таком списке будут показываться виртуальные машины (ВМ), которые были установлены мной.
Кликнув на любую ВМ, будет показана вся статистика по машине, а именно, как она работает, какая нагрузка на данную машину, и все остальные данные, в таком вот виде: ![image](https://github.com/wxxkoos/practice2k23/assets/100823878/5843fbcd-2c1e-4201-8dd5-b6682101828b) ![image](https://github.com/wxxkoos/practice2k23/assets/100823878/d4673f44-2257-4c87-8dd0-07dbff3ab7d6)


На данный момент ведется работа с материалом по задани Demo 2024, в данной работе изначально нужно провести базовую настройку всех сетевых устройств, также собрать всю топологию по данному рисунку, нужно учитывать то что все устройства будут работать на ОС Linux (Debian). Сейчас пойдет этап установки ВМ для работы с данном материалом. Такие действия нужно проделать со всеми машинами, которые мы будем устанавливать. Сейчас я изначально продемонстрирую вам установку одной виртуальной машины, и как я писал ранее, такое нужно будет проделать со всеми остальными машинами.
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/d8a47c5a-738e-4e4a-a113-f673dfcfa4bf) (В данном этапе мы выбираем язык системы, выбираем English (Английский), т.к с ним удобнее работать).
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/f1cce4c4-bd9d-4b12-9acb-526f329251d5) (На данном этапе выбираем выбранный системой, а именно United States).
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/b62a6461-ca88-41f3-b2e2-53ff3cc266bd) (На данном этапе, выбираем также как и на прошлом, выбранный системой).
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/56926ee2-0e25-4330-98b4-f04bca6331dd) **процесс загрузки**
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/af354c63-ab92-4f42-8965-cfaa206e7e99) (Начинается процесс настройки нашей сети).
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/103deb45-2e1e-471d-a3e2-80a7194ebea4) (Прописываем наш пароль, по стандарту пишем - toor)
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/de6dfeb0-6e41-4e22-908d-0cff21d8b373) (Тут мы выбираем наш часовой пояс, выбирайте любой).
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/2fad7762-e432-4d61-9926-d5ea4ba6d141) (На данном этапе нужно выбрать первый пункт).
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/62f0b04b-eb39-4014-83ec-9073a8bcea0d) **процесс установки**
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/532cf551-7dfa-4b06-ad4f-c1be22c347a1) **процесс установки 2.0**
И такие манипуляции мы проводим с остальными машинами.
![image](https://github.com/wxxkoos/practice2k23/assets/100823878/b8176f6e-10a2-4d57-9b4d-3fe75c0f1192)

**| Имя устройства  | Интерфейс     |   IPv4/IPv6   |  Маска/Префикс  |     Шлюз      |**
  | -------------   | ------------- | ------------- | --------------- | ------------- |
  | ISP             | Content Cell  | Content Cell  | Content Cell    | Content Cell  |
  | HQ-R            | Content Cell  | Content Cell  | Content Cell    | Content Cell  |
  | BR-R            | Content Cell  | Content Cell  | Content Cell    | Content Cell  |
  | HQ-SRV          | Content Cell  | Content Cell  | Content Cell    | Content Cell  |
  | BR-SRV          | Content Cell  | Content Cell  | Content Cell    | Content Cell  |








