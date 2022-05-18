---
title: DB::F
position_number: 1.2
type: function
description: Выбирает следующую строку из набора результатов и помещает её в ассоциативный массив
parameters:
  - name: String
    content: SQL запрос
right_code_blocks:
  - code_block: |-
      // Вернёт массив с записью test
      $array = DB::QF("SELECT * FROM `users` WHERE `username` = 'test'");
      echo($array["username"]); // test
    title: PHP
    language: php
---


