---
title: DB::N
position_number: 1.4
type: function
description: Подсчитывает количество записей в таблице
parameters:
  - name: String
    content: SQL запрос
right_code_blocks:
  - code_block: |-
      // Вернёт массив с записью test
      $q = DB::N("SELECT * FROM `users` WHERE `username` = 'test'");
      echo($q); // 1
    title: PHP
    language: php
---


