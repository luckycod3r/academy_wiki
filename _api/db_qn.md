---
title: DB::QN
position_number: 1.5
type: function
description: Подсчитывает количество записей в таблице
parameters:
  - name: DB::Q
    content: Результат SQL запроса
right_code_blocks:
  - code_block: |-
      // Вернёт массив с записью test
      $q = DB::N("SELECT * FROM `users` WHERE `username` = 'test'");
      $c = DB::QN($q);
      echo($c) // 1
    title: PHP
    language: php
---


