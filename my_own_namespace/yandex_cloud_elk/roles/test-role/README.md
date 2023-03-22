Role Name
=========

Роль для тестирования модуля, записывающего текст в файл

Requirements
------------

Нет

Role Variables
--------------

Переменные расположены в /defaults/main.yml

file_path: путь к текстовому файлу, который создает модуль
file_content: текст, который модуль записывает в файл

Dependencies
------------

Нет

Example Playbook
----------------

- name: Write test file
  roles: 
    - test-role

License
-------

MIT

Author Information
------------------

Oleg Troitskiy. 2023.
