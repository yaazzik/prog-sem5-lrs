
  ### ВСР 1.1 | Глебов М.Д.
  # Использование модуля PyMySQL

  ### **Инструкция по установке:**

   Последняя актуальная версия может быть установлена при помощи `pip`
  > $ python3 -m pip install PyMySQL
  
 ### Системные требования:
  - Python 3.6 или новее
  - MySQL 5.6 / MariaDB 10.0 или новее
  
 ### Пример создания таблицы:
 
  Для выполнения следующего SQL запроса:
>   CREATE TABLE 'users' (<br>
      'id' int(11) NOT NULL AUTO_INCREMENT,<br>
      'email' varchar(255) COLLATE utf8_bin NOT NULL,<br>
      'password' varchar(255) COLLATE utf8_bin NOT NULL,<br>
      PRIMARY KEY ('id')<br>
    ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_bin<br>
    AUTO_INCREMENT=1 ;
