# Перечень автоматизируемых сценариев.

## Варианты способов перехода на страницу професии "Тестировщик ПО"
*Предусловие:* пользователь находится на главной странице https://netology.ru/

### 1. Переход через "Каталог курсов"

> 1. В верхнем левом углу страницы нажать кнопку "Каталог курсов"
> 2. В появившемся окне "Направления обучения" нажать кнопку "Программирование"
> 3. В списке профессий найти "Тестировщик ПО" и кликнуть по названию

### 2. Переход через "Направления обучения"

> 1. На главной странице найти раздел "Направления обучения"
> 2. В разделе "Направления обучения" нажать кнопку "Программирование"
> 3. В списке профессий найти "Тестировщик ПО" и кликнуть по названию

### 3. Переход через "Направления обучения" (Полный каталог)

> 1. На главной странице найти раздел "Направления обучения"
> 2. Внизу раздела нажать кнопку "Полный каталог"
> 3. В списке профессий найти "Тестировщик ПО" и кликнуть по названию

### 4. Переход через поиск

> 1. В верхнем левом углу страницы нажать кнопку "Каталог курсов"
> 2. Поставить курсор в форму поиска курсов
> 3. Ввести "Тестировщик ПО" в форму поиска
> 4. Кликнуть по найденному курсу "Тестировщик ПО"

### 5. Переход через "Найти курс"

> 1. В верхнем левом углу страницы нажать кнопку "Каталог курсов"
> 2. Нажать кнопку "Найти курс" сбоку от поиска
> 3. В списке профессий найти "Тестировщик ПО" и кликнуть по названию

### 6. Переход через футер сайта

> 1. В нижней части страницы найти колонку "Обучение"
> 2. Кликнуть на "Програмирование"
> 3. В списке профессий найти "Тестировщик ПО" и кликнуть по названию

### 7. Переход через футер сайта "Популярные курсы"

> 1. В нижней части страницы найти колонку "Обучение"
> 2. Кликнуть на "Популярные курсы"
> 3. В списке профессий найти "Тестировщик ПО" и кликнуть по названию

### 8. Переход через футер сайта "Каталог курсов"

> 1. В нижней части страницы найти колонку "Обучение"
> 2. Кликнуть на "Каталог курсов"
> 3. В списке профессий найти "Тестировщик ПО" и кликнуть по названию

## Варианты перехода к записи на курс
*Предусловие:* пользователь находится на странице курса Тестировщик ПО https://netology.ru/programs/qa#/

### 1. Переход через кнопку "Записаться"

> 1. Нажать кнопку "Записаться" чуть ниже описания курса "Тестировщик"

### 2. Переход через кнопку "Записаться" после скролла вниз

> 1. Поскролить страницу вниз до появления фиксированной "шапки" наверху страницы
> 2. Нажать кнопку "Записаться" в правой части "шапки" страницы

## Тестовые сценарии
*Предусловие:* пользователь находится на странице курса Тестировщик ПО https://netology.ru/programs/qa#/ и видит форму записи на курс

### Перечень валидных данных для заполнения поля "Имя"

> - состоит из 2-ух букв, пример: ЯН
> - может быть не ограничено количеству символов, пример: Вольфшлегельштайнхаузенбергедорф
> - содержит пробел, пример: Этьен Морис
> - содержит дефис, пример: Этьен-Морис
> - может состоять больше чем из двух слов через пробел, пример: Ян Ван Ман Ран Тан 
> - может состоять больше чем из двух слов через дефис, пример: Ян-Ван-Ман-Ран-Тан 
> - может содержать букву "ё", пример: Семён
> - содержит латинские буквы, пример: Sam
> - состоит из букв только верхнего регистра, пример: ЕВГЕНИЙ
> - состоит из букв только нижнего регистра, пример: евгений

### Перечень валидных данных для заполнения поля "Телефон"

> - состоит из 10 символов включая "+", пример: +791674887
> - состоит из 15 символов включая "+", пример: +79167488712345
> - состоит из 9 символов не включая код страны, пример: 590554388
> - состоит из 14 символов не включая код страны, пример: 59055438812345
> - состоит из 10 символов не включая код страны, пример: 9055298874
> - состоит из 11 символов не включая код страны, начиная с "8" пример: 89055298874
> - состоит из 12 символов включает код другой страны, пример: +37376721234
> - может содержать скобки, пример: +7(495)1234567
> - может содержать дефис, пример: +7-495-123-45-67
> - может содержать пробел, пример: +7 (495) 123-45-67

### Перечень валидных данных для заполнения поля "Электронная почта"

> - простой email состоит из латиницы, пример: example@email.com
> - содержит цифры в названии, пример: user123@email.com
> - содержит точку в названии, пример: john.deer@email.com
> - содержит "+" в названии, пример: alis+cooper@email.com
> - содержит "_" в названии, пример: alis_cooper@email.com
> - может содержать специальные символы, пример: 'U$e!r!#%^&*_++=?{}/|@email.com
> - может содержать разные домены, пример: user@email.com user@email.org user@email.info

## Позитивный тест-кейс
### Отправка валидных данных при записи на курс.
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"

*Ожидаемый результат:* Появляется сообщение об успешной записи, более подробная информация отправлена на электронную почту

### Перечень невалидных данных для заполнения поля "Имя"
> - содержит цифры, пример: иван123
> - содержит специальные символы, пример: !@#$%Иван^&*()
> - содержит запятые или точки, пример: Ив, ан
> - содержит иероглифы, арабскую вязь и тд, пример: 把这几个字摹下来 اً متساوين في
> - состоит из одной буквы(очень короткое имя), пример: И

### Перечень невалидных данных для заполнения поля "Телефон"
> - неполный или короткий номер телефона, пример: +749545
> - слишком длинный номер телефона, пример: +123456789101112
> - содержит специальные символы, пример: "475@45$1
> - содержит точки или запятые, пример: 7.788.888,88,88
> - содержит буквы, пример: +7четыредевятьпять

### Перечень невалидных данных для заполнения поля "Электронная почта"
> - отсутствие "@", пример: useremail.com
> - отсутствие домена, пример: user@.com
> - содержание пробелов, пример: user @ email.com
> - содержание символов [] <> \ () " ; : "," пример: ;U(s[e<r"a\:s,d@email.com
> - содержание спецсимволов в домене, пример: user@ema#il.com
> - отсутствие точек в домене, пример: user@emailcom
> - отсутствие символов перед и после символа "@", пример: user@ или @email.com
> - более 64 символов перед "@", пример: useruseruseruseruseruseruseruseruseruseruseruseruseruseruseruserr@email.com
> - более 254 символов после "@" в доменной части, пример: user@emailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemaile.com

## Негативные тест-кейсы

- [ ] Попытка записи, оставив пустым поле "Имя"
> 1. Оставить поле "Имя" пустым
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Имя" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Обязательное поле"

- [ ] Попытка записи, оставив пустым поле "Телефон"
> 1. Заполнить поле "Имя" валидным значением
> 2. Оставить поле "Телефон" пустым
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Телефон" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Обязательное поле"

- [ ] Попытка записи, оставив пустым поле "Электронная почта"
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Оставить поле "Электронная почта" пустым
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Обязательное поле"

- [ ] Попытка записи, заполнив поле "Имя", невалидным значением содержащим цифры "иван123"
> 1. Заполнить поле "Имя" невалидным значением с содержанием цифр
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Имя" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Должно состоять из букв"

- [ ] Попытка записи, заполнив поле "Имя", невалидным значением содержащим специальные символы
> 1. Заполнить поле "Имя" невалидным значением с содержанием специальных символов "!@#$%Иван^&*()"
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Имя" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Должно состоять из букв"

- [ ] Попытка записи, заполнив поле "Имя", невалидным значением содержащим запятые или точки
> 1. Заполнить поле "Имя" невалидным значением с содержанием запятых и точек "Ив, ан."
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Имя" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Должно состоять из букв"

- [ ] Попытка записи, заполнив поле "Имя", невалидным значением содержащим иероглифы
> 1. Заполнить поле "Имя" невалидным значением с содержанием иероглифов "把这几个字摹下来"
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Имя" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Должно состоять из букв"

 - [ ] Попытка записи, заполнив поле "Имя", невалидным значением содержащим 1 букву
> 1. Заполнить поле "Имя" невалидным значением с содержанием одной буквы "И"
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Имя" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Должно быть не короче 2 символов"

- [ ] Попытка записи, заполнив поле "Телефон", невалидным значением содержащим короткий номер
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" невалидным значением с содержанием короткого номера "+749545"
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Телефон" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Номер в формате +9 (999) 999-99-99"

- [ ] Попытка записи, заполнив поле "Телефон", невалидным значением содержащим длинный номер
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" невалидным значением с содержанием длинного номера "+123456789101112"
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Телефон" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Номер в формате +9 (999) 999-99-99"

- [ ] Попытка записи, заполнив поле "Телефон", невалидным значением содержащим специальные символы
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" невалидным значением с содержанием специальных символов "475@45$1"
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Телефон" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Номер в формате +9 (999) 999-99-99"

- [ ] Попытка записи, заполнив поле "Телефон", невалидным значением содержащим точки или запятые
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" невалидным значением с содержанием точек и запятых "7.78.88,88,88"
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Телефон" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Номер в формате +9 (999) 999-99-99"

- [ ] Попытка записи, заполнив поле "Телефон", невалидным значением содержащим буквы
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" невалидным значением с содержанием букв "+7четыредевятьпять"
> 3. Заполнить поле "Электронная почта" валидным значением
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Телефон" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Номер в формате +9 (999) 999-99-99"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с отсутствием "@"
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с отсутствием "@" "useremail.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с отсутствием домена
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с отсутствием домена "user@.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с содержанием пробелов
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с содержанием пробелов "user @ email.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с содержанием символов [] <> \ () " ; : ","
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с содержанием пробелов ";U(s[e<r"a:s,d@email.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с содержанием спецсимволов в домене
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с содержанием спецсимволов в домене "user@ema#il.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с отсутствием точек в домене
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с отсутствием точек в домене "user@emailcom"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с отсутствием символов перед и после символа "@"
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с отсутствие символов перед и после символа "@" "user@" или "@email.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением с более 64 символов перед "@"
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с отсутствием точек в домене "useruseruseruseruseruseruseruseruseruseruseruseruseruseruseruserr@email.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"

- [ ] Попытка записи, заполнив поле "Электронная почта", невалидным значением более 254 символов после "@" в доменной части
> 1. Заполнить поле "Имя" валидным значением
> 2. Заполнить поле "Телефон" валидным значением
> 3. Заполнить поле "Электронная почта" невалидным значением с отсутствием точек в домене "user@emailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemailemaile.com"
> 4. Нажать кнопку "Записаться"
>
> *Ожидаемый результат:* Поле "Электронная почта" подсвечивается красным, ниже поля появляется ошибка с красным текстом "Неверный email"
