---
title: DB::Q
position_number: 1.1
type: function
description: Отправляет запрос к базе данных
parameters:
  - name: string
    content: Запрос на MySQL
right_code_blocks:
  - code_block: |-
      // Добавит в users запись test 
      DB::Q("INSERT INTO `users` VALUES('test')");
    title: PHP
    language: php
---


