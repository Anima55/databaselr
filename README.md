# Структура GitHub
```
Datbaselr/
├── lr1/
├── lr2/
├── lr3/
├── lr4/
├── lr5/
├── lr6/
├── lr7/
└── README.md
```

## Структура лабораторних робіт
### Лабораторна робота 1 Робота з СУБД PostgreSQL та основи SQL
https://github.com/Anima55/databaselr/tree/main/lr1
```
lr1/
├── skrin/
|   ├── Screenshot_1.png
|   ├── Screenshot_2.png
|   ├── Screenshot_3.png
|   ├── Screenshot_4.png
|   ├── Screenshot_5.png
|   ├── Screenshot_6.png
|   ├── Screenshot_7.png
|   ├── Screenshot_8.png
|   ├── Screenshot_9.png
|   ├── Screenshot_10.png
|   ├── Screenshot_11.png
|   ├── Screenshot_12.png
|   ├── Screenshot_13.png
|   ├── Screenshot_14.png
|   ├── Screenshot_15.png
|   ├── Screenshot_16.png
|   ├── Screenshot_17.png
|   ├── Screenshot_18.png
|   ├── Screenshot_19.png
|   ├── Screenshot_20.png
|   ├── Screenshot_21.png
|   ├── Screenshot_22.png
|   ├── Screenshot_23.png
|   ├── Screenshot_24.png
|   ├── Screenshot_25.png
|   ├── Screenshot_26.png
|   ├── Screenshot_27.png
|   ├── Screenshot_28.png
|   ├── Screenshot_29.png
|   ├── Screenshot_30.png
|   ├── Screenshot_31.png
|   ├── Screenshot_32.png
|   ├── Screenshot_33.png
|   ├── Screenshot_34.png
|   ├── Screenshot_35.png
|   ├── Screenshot_36.png
|   ├── Screenshot_37.png
|   ├── Screenshot_38.png
|   ├── Screenshot_39.png
|   ├── Screenshot_40.png
|   ├── Screenshot_41.png
|   ├── Screenshot_42.png
|   ├── Screenshot_43.png
|   ├── Screenshot_44.png
|   ├── Screenshot_45.png
|   ├── Screenshot_46.png
|   ├── Screenshot_47.png
|   ├── Screenshot_48.png
|   ├── Screenshot_49.png
|   ├── Screenshot_50.png
|   ├── Screenshot_51.png
|   ├── Screenshot_52.png
|   ├── Screenshot_53.png
|   ├── Screenshot_54.png
|   ├── Screenshot_55.png
|   ├── Screenshot_56.png
|   ├── Screenshot_57.png
|   ├── Screenshot_58.png
|   ├── Screenshot_59.png
|   ├── Screenshot_60.png
|   ├── Screenshot_61.png
|   ├── Screenshot_62.png
|   ├── Screenshot_63.png
|   └── Screenshot_64.png
└── lab01-report.md
```
### Лабораторна робота 2 Створення складних SQL запитів
https://github.com/Anima55/databaselr/tree/main/lr2
```
lr2/
├── skrin/
│   ├── 2_1_1.png
│   ├── 2_1_2.png
│   ├── 2_1_3.png
│   ├── 2_2_1.png
│   ├── 2_2_2.png
│   ├── 2_2_3.png
│   ├── 2_3_1.png
│   ├── 2_3_2.png
│   ├── 2_3_3.png
│   ├── 2_4_1.png
│   ├── 2_4_2.png
│   ├── 2_5_1.png
│   ├── 2_5_2.png
│   ├── 2_6_2.png
│   └── 2_7_1.png
└── lab02-report.md
```
### Лабораторна робота 3 Модифікація даних та транзакції
https://github.com/Anima55/databaselr/tree/main/lr3
```
lr3/
├── lab03-report.md          # Основний звіт з лабораторної роботи
├── lr3.sql                  # SQL-скрипт з дампом бази даних
└── skrin/                   # Директорія зі скріншотами
    ├── 1_1.png              # Створення структури БД
    ├── 1_2.png              # Додавання тестових даних
    ├── 1_3.png              # Безпечне оновлення записів
    ├── 1_4.png              # Транзакція видачі книги
    ├── 1_5.png              # Демонстрація ROLLBACK
    ├── 1_6.png              # Безпечне видалення
    ├── 2_1.png              # Нові таблиці (бронювання та аудит)
    ├── 2_2.png              # Складна транзакція
    ├── 2_3.png              # Використання SAVEPOINT
    ├── 2_4.png              # Каскадні операції
    ├── 2_5.png              # Тригери для аудиту
    ├── 2_6.png              # Блокування записів
    ├── 3_1.png              # Система версіонування
    ├── 3_2.png              # Відкладені операції
    └── 3_3.png              # Складна бізнес-логіка
```
### Лабораторна робота 4 Розробка реляційної бази даних з простою інтеграцією
https://github.com/Anima55/databaselr/tree/main/lr4/webadminpanel-main
```
lr4/webadminpanel-main/
├── app.log                              # Головний файл логу дій
├── ER.pdf                               # Діаграма ER (Entity-Relationship)
├── grud.py                              # Консольний CRUD додаток для HelperInfo
├── lab04-report.md                      # Документація проекту
├── backups/                             # Папка для резервних копій БД
│   └── wdb_backup_20251122_184305.sql   # Резервна копія бази даних
└── www/                                 # Веб-додаток Flask
    ├── wdb.sql                          # База данних Сайту
    ├── app.py                           # Головний файл Flask додатку
    ├── app.log                          # Файл логу веб-додатку
    ├── requirements.txt                 # Залежності Python
    ├── docker-compose.yml               # Docker композиція
    ├── .dockerignore                    # Файл Dockerignore
    ├── Dockerfile                       # Файл Docker 
    ├── static/
    │   └── styles.css                   # CSS стилі
    ├── templates/                       # HTML шаблони
    │   ├── index.html                   # Головна сторінка (HelperInfo)
    │   ├── tickets.html                 # Сторінка тікетів
    │   ├── admin-page.html              # Адмін-панель
    │   ├── login.html                   # Сторінка входу
    │   └── logs.html                    # Сторінка журналу дій
    └── script/                          # JavaScript файли
        ├── helpinfo.js                  # Функціонал для HelperInfo
        ├── webadmin.js                  # Функціонал для адмін-панелі
        ├── filter.js                    # Фільтрація для HelperInfo
        ├── filterticket.js              # Фільтрація для тікетів
        └── excel.js                     # Експорт в Excel
```
# Лабораторна робота №5
```
lr5/
```
# Лабораторна робота №6
```
lr6/
```
# Лабораторна робота №7
```
lr7/
```
