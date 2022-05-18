---
title: DB::QF
position_number: 1.3
type: function
description: Выбирает следующую строку из набора результатов и помещает её в ассоциативный массив
parameters:
  - name: DB::Q
    content: Результат запроса
right_code_blocks:
  - code_block: |-
      // Вернёт массив с записью test
      $q = DB::Q("SELECT * FROM `users` WHERE `username` = 'test'");
      $array = DB::QF($q);
    title: PHP
    language: php
---


