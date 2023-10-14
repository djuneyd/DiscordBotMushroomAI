# DiscordBotMushroomAI
1. в файле main.py прописан сам код ИИ, чтобы его применить должен присутствовать ИИ с 20-ю классами такими как:
- I. 0 шампиньон
- II. 1 лисичка обыкновенная
- III. 2 опята
- IV. 3 груздь
- V. 4 белый гриб (боровик)
- VI. 5 подберёзовик
- VII. 6 подосиновик
- VIII. 7 рыжик
- IX. 8 сыроежка
- X. 9 маслёнок
- XI. 10 мухомор
- XII. 11 бледная поганка
- XIII. 12 сатанинский гриб
- XIV. 13 лепиота коричнево-красная
- XV. 14 галерина окаймлённая
- XVI. 15 паутинник красивейший
- XVII. 16 желчный гриб
- XVIII. 17 ложная лисичка
- XIX. 18 ложный опёнок
- XX. 19 мицена

Следовательно после обработки фотографии, функция выдаёт список со всей информацией.

2. В файле names.py прописаны все переменные с информациями о грибах, следовательно у вас ещё должны присутствовать 20 текстовых файлов где в каждом имеется информация об одном определённом грибе.

3. В файле mushroom_bot.py прописан собственно сам бот. Чтобы увидеть все инструкции как им пользоваться, после запуска напишите команду $hello и он вам всё подробно расскажет

4. КАК РАБОТАЕТ БОТ? 

Чтобы получить информацию о грибе нужно, прикрепить картинку и написать команду $check. Бот сохранит картинку на ваш компьютер, обработает её, а затем после обработки он её благополучно удалит. После обработки картинки вы получите:
- Съедобный ли гриб или нет.
- Название гриба.
- Шанс совпадения данного гриба с одним из грибов из дата сета ИИ.
- Несколько примеров картинок гриба из дата сета ИИ.
- Просто интересная информация, история и факты о грибе.
- И если гриб Съедобный то вы получите ссылку на сайт с кучей рецептов из ввашего гриба.