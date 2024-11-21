# BRANCH-REPOSITORY
## INFORMATION
# Репозиторий: что это и как с ним работать?
### Репозиторий — часть системы Git, которая позволяет программистам совместно работать над проектами. Этот инструмент облегчает жизнь IT-специалистам: с ним можно безопасно вносить изменения в программный код.

<img src="https://storage.nic.ru/ru/images/png/1.blog-repository-950-1.png">

---

# Что такое репозиторий простыми словами?
#### Репозиторий — это хранилище всех версий кода. Он бывает трех видов:

#### Локальный — расположен на одном компьютере, и работать с ним может только один человек.
##### Централизованный — расположен на сервере, куда имеют доступ сразу несколько программистов.
##### Распределенный — самый удобный вариант с облачным хранилищем. Главный репозиторий хранится в облаке, а его локальные копии — у разработчиков на компьютерах. Когда программист вносит правки в локальную версию, ее можно синхронизировать с удаленной. Получается, что в облаке всегда актуальный код.
#####  Для работы с распределенными репозиториями нужен удобный сервис. Самые популярные — GitHub, GitLab и Bitbucket. У них понятный интерфейс, в котором можно управлять проектом, добавлять новые объекты и искать общедоступные репозитории.

##### Git — это система, которая позволяет контролировать версии приложения. Она сохраняет все подтвержденные изменения кода. Поэтому в любой момент можно отменить правки или исключить ненужные части кода.

##### Git-сервисы позволяют переключаться между ветками кода и просматривать коммиты. 

<img src="https://storage.nic.ru/ru/images/png/1.blog-repository-1.png">

---

#### В репозиториях существуют «ветки» — это важная особенность Git-систем. Ветка позволяет менять отдельные элементы кода, не вмешиваясь в основной код. Главная ветка называется master, дополнительные можно называть по-своему.


<img src="https://storage.nic.ru/ru/images/png/1.blog-repository-3.png">

---

## Так выглядит раздел с ветками в GitLab — они разделяются на активные и устаревшие. В меню можно посмотреть название, скачать или удалить всю ветку

# Внутри ветки видно весь ход изменений. Например, что конкретно и в каких файлах изменили

<img src="https://storage.nic.ru/ru/images/png/1.blog-repository-4.png">

---

# Выводы
### Репозиторий — функциональное средство для работы с кодом. Работа с Git-репозиторием в программировании не позволит потерять или безвозвратно испортить код. Любые правки всегда можно отменить.

---

### Для работы с системой контроля репозиториев потребуется Git-клиент на компьютере — через него отправляют пакеты с кодом в облачное хранилище. Он бесплатный и доступен для разных операционных систем: Windows, Linux и macOS. Также во всех современных редакторах кода типа VS Code или Atom есть инструменты для работы с репозиториями и Git-платформами. Это может быть встроенная возможность или плагины.

---



---


# Ветви в Git
### Ветка в Git — это набор коммитов, расположенных в хронологическом порядке. У каждой ветки есть свое название. Основная ветка чаще всего называется master, она появляется при инициализации репозитория и считается главной веткой проекта. Другим веткам вы даете имена самостоятельно. Дополнительные ветки используются для создания нового функционала и исправления ошибок. То есть все изменения в проекте создаются в отдельной ветке, а затем эта ветка сливается с основной.
# Что такое бранч в Git
### Команда git branch нужна для работы с ветвлением в Git. При помощи нее можно создавать новые ветки, а также просматривать, переименовывать и удалять существующие.
## Слияние веток
##### Ветвление позволяет отделить готовый код проекта от функционала, который находится в стадии разработки и тестирования. Когда разработчик завершил задачу, ветку с новым кодом необходимо слить с основной. Сделать это можно с помощью команды git merge.
# Перейдите к ветке master:
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAToAAAChCAMAAABgSoNaAAABelBMVEX///8AsgAAAAAAgf//jwBdXV3Y2Nj/iAAAtQAAuAAAg///hwD/iwAAhv8AtABnZ2cArgAAev+lpaXq6uo5OTnExMQAe//R0dEAdv+enp6RkZG9vb3i4uL/gwD09PQAf/+Ghob/+/Nvb296enoAfwD/4cf/uHP/rl0vLy9UVFQWFhYAdQD1+/8+Pj6wsLDV1dUAIQAAOwAAnAAAVwAApwAAlACTv/9JnP8AaM5KSkojIyMASAAAjAAAHQAAXwDz+/N2znb/vYH/x5X/nkL/nSqz0v8AV6wAEiQaGhoALgAAJwAAaAAAFwDn+OfV8NVIKAD/w47/3Lz/8eTR5P/n8/90sP++2v/Y6f89lf9hpf9Alv8AYb8ARYgAUJ4AHz0AMF8Acd8AOnMACgCR1pEuvC5Gvka+5r5dx104HwC8aQB0QQD/qmBxrP+gxP+y0/8ACxej3aN80Hyz4LOI0ojK68qYVQDIcADnggAlFQBfNQDYeQD/0af/qk3/37/IMvaZAAASoklEQVR4nO1di18S2RcfLqODMOAggoCAgIJAPrJMRW19gGm1uoqP1LayFG3XLHPb+u3C/u+/cwbFedyBAU1B5/v5xChzvOfe75zHfU4MY+DOY3P81W1X4Zaw7RmHz3HPtrbIZ6d3nWHsPc4N+HSOyW8OePHmvcQ6Nn29Yvs3PM4FZsNrFj+VgveYOmbHs8vsOncYZmtzZwzsav1kgWEWTtaZrbHPJzsiLdueTWbB2dOzw2x5exjm1ebOJjjpxsnYq51NBqnbWjgZuO123AI2nM4xJ/jiphfgfMWMITt27xiz67V7vVsoMubcZj45Nz125sS7wyygoHcBaTR7d4G6V2CLY9XU3ElsejyeMfBZz+cNDHljTnsppI33OD+hGaJTexird8Pu3djxngw4PWMDm56egS1nj/3kM+N1rm+j0d5HDJh7zAPA2C5w5PRKqPN8Kks4t+DbT96Fbe/GltNZinBbTs8G/tSzWynH3G3seMBoNp2QaV95vQMiddtI3WUyHffgLwvecasdgx58g9R5ewbOqbPfx0iH2EF/W/CaN5gxjxX+mTc27B6kbvNC4sTT41zHJNvzCendgv6Kc+OCOue63fmpUvl3GDteDFV2CF1O72eI/maPtwetzlum7pW3x8tgpoXsAN97QHATBD0idd5X65g17iU2d5GjgU893m1MqJte++ft7QX4+qQsMj6OIie7u5g2xuxeO9xa3x1H6rZ3ISuLPxowYMCAAQMGDBgwYOC+IOBr75xMJP3uSkKhod7BRGIwPBSqIOTyJZcISSV6KxZ1Z+AeJGX4tIRc7ZdCvVrkBVouhVJDP6m6jYMQNvf9s4m9ide/Y5O7qFJ+uPP2zcTe3sSbt/BjB1XIB3fePdszW/cmsKh0JfO8A3BBG9+Y7VaE3f76C52WJHCyVxKy2vfeEdJOEQK7fGdFITMIWZ9BwYGfXfvbRIiQReDEfA6r9T0hak9LE/JaImR/RuMuKhOCpwHm6bqJNtwSOsmi+bK52GJwtVaFUJiQPbtMaEIdFYcImZAJWYG7xE214+YBIcwqYw5oea9s8LCSFBB6pvRGMN9nCiGr+Yt22ml2QHtfK5gDY/micNk0ea8gBbh7R6IyoTB5qxKyvibkrqYKH6W9aFGdUqFWtWUCK3uKQAaWqRIy299q5OLmx6Da6NDs5M7opxidaHZSVtxkkSIEaTZ50226GYC/mtXUIStSj6Xyi6xIk6yf/E6jDmzzpht1MwiQtxRSzNY3JCyRSpE9GnV7Mrdup/JrhkRxt4Jdl699sBOQIO8opoIGlRLvlwCmSRMCg7qUGUzRQp0Y7BKd6aiPPkRpNrRGL8eZmtTJoUWdDHTqFsvj3qYfWbhgSEWSPnfABXBrOOwzEg25LhCgJViRusmyjAsGwloO2+oKuP0wHCHtze26HTg5Um6CVpp4L0ueCapBQZ+tRSJULU2EcP6g+2Ya+VMAA/Sw9PdJOiuLsumTXiorwK9fIlS9cxKKKpQ3FdqVU0phWpfNOkFSUiE3+ULv/MmGutRgB6NYSTenGyLeT2zdz0RUNZMBcUzd8YCs6JdJpVSjU3GWYFAmpGcgBuMSecnNgiHK/Fm7usE4sg8p/1CZKDCIyafQacN/q3J+ZVhrJrWxEVI2FuEi4LLySacJ9YRdGjKxTMhqXlRN2A3hdJ1c6K18MMyIaeo623RD6FVMdZTgBu4ktFjt4GMqOWD9rVVCi31vkUyquhpRtDvJVOcebaoz3YQu69KY/wFjeStOnZvFafHfiazPcfnH0G8rC4FLq5krTbCXZ+HN9An2QBOanU8ru3XhoOL1Hi5PiIsxYZqQaxBXdfaQlL03MEJIUh/D+bLOHi7rfNFY1mmhzN83OCZV0+YXCPWKI6XFL/iZHtaQ6igJLVZcJwxIVhwn6UJukq616rcMVyVHcfmSYmsTvVrEIYZKvKTaKw0KXL6WJXwCvZqZtOkmjrur9UZh0Fq9FF1CVZDUNP8Gha9hFljCzRbs/JRO3e2gcR6iTjQOdUMGdfWi26CuXhjU1Q2DurphUFc3DOrqhkFd3TCoqxsGdXXDoK5uGNTVDYO6umFQVzeajrqwQV29iDbM2nF3sy0nDjbMyRk39aTPjSIUcHcP614hqWX5MzTc7Q5UKxnUu1vrWaBxVTiH4ur29Ub9Q/U8ZV2VFgU7zk8TJsK69LQqNtdoIxBOlEpOd2hXJOS7UO+vfZ1nSev4U3f6YiEyUWM41FXpEnCfH3k4MvIcr1EdXPt1BpiQuGD4fGTkKV61GlCzehl66WcpAvg0Rn7p63s5RWrbxhiKnlf6YaVKi3B1gmDfqKOtzSJMo57qGSClL9S5obCpacHS1uYY7XtByCCNFlcC1Qu1qJehS7WJB9ENBb0chTJBuanvYQ3bGLuklYan2an9LAMgOt1mcZgADkvboxe0LUxydOg7+TEEnDy6LLmPkJS6Gi61+ho3uiYo9QXVU0KbWCgWa3lJ2TVER7eq0prnIUOEvBi1mMqwWKbUZwlVf1JpWf8C8PgeX9Qe0Tb6kEzS1Au1qVeimywpv2pVqHa0TVdxvUqVXtKwuxbyVJCIopqpKvmzRdcTDGElpAWbLMIHVU8iSZ6aVOpT1AI1kVZtRVgiU3LVJjQfPUEGrLVNXh/hV43uD4SjRxa5FoflacXI4Ne3zaOXvJBXArh7pIxk4B6jCiGH49cae7ku5VFvH/lgUZRqgieiI8qEyUPlX2KlqRFskLxUPB8QflKJHL8+h3KpnwnU/xdF/RPkgVr9dK1bcNyKnaOE9KlUO0Z1mB14yhN1pV9Sd1NBjhCUzweEn2sfnozqDOM+MqIiRay/NOhCTDJR1de4j6RDlkEhXqlVo9lVNeYOaqUFKuk+VVAQn/sDLePuWtLbeUhTnjzUf0TGil8ZDi/UU7aCVgQ4fmfZF/zkF1qp09RejAxJeqWnaJbUTpV1PKInCndaawOmCiF1EDtnRZpi6FUF9TUmCnAf6Jy2dFUsdbT66DGlVWlKokiQRxRZUxtExlYpht3dvpbSsbZWXXBTXREfffqyhECCPKEIYSOH9amRICruc+yAoeckvVTTB0Wjaqm0mrpJTequjIe0gh1PFFK0p+ww/XpF3fRG6Sj1A406qDTF1bWpS7ZcCUl6LSB5L0mkUlT1GJfL5XSKTRqM1qA7RUmT8lJFRCdLRVetNFBHme1IkmkNLdXCQhWEqKnbZOmThY00Xb0sKoW628ETa3ldgkYAV8Y63C4e7pKFbs1KU9JWmNKtE537yi9jSVAffdtjWQ+hV0u9PLa4emt6o5OPnrf7ZKVCv0g9NOukPkrojYbVWtzkKa0L9Pjq5yV7aT0EHClI+zbdMOKoyq/Y0BRJ6Z7KA1YclN7iiJQqN/VhhOmkP6UOJwiFZ/TXK28L76IZPzx5ebeD1nun9/vTNQwxqGOUR9LeeBd9Fope6Wl6+PKrB2341PVOAldAp9rs0OjkThKmmB2op3XIk/orRRsZW55LJglcWsdB02qzwyE9XZioWogTNNdwFqEL5+FUpCj7uhT1WnMcCf1RJE1eKFwW4pXEatNacz/D1Epr5Exw+peyGQ5k7lrW5yC2P5FWwwHjaNUoDtQ/0Kk+oP8FdpDfR0wWqepfpNMfQ+p5wwuEaZXWmvr1EfLYVHZaS9sD6mHCepAkpK/NUq6DaYr2LjtU75Cr11od9OtfNwSaf31yMdfraBsdkc1LpSqMw1tklbaYHmu90xHRAWr6TG0WQJtj+rnuqejqgGqMPLGUSjY9+EBjTuROp/pQDe/+CyzhCoOpDWB6BCYnne4Zqjhz146VdpxXuu9DJeYgKmG3eupBX1/fY1y5usaXdeGxzIePoeAHuF6ToE/Ld6Vk6ivMN4VriSTiAcmRqakRaD1JSl09WXnxBQ9NPi1XerLKWkJHojyKC1/rQT9XuFxwQpuTS/UpfyX1rdWnjWS6L4qNyvwzVG2oFJJUWocdtXb0tiR/ysuS3L5osqW3yhK8TvVLNU4fu9xDQ91KzXq2WnSJle5olN0h14DkdewS8t3Z9wdWgv86XkYUbZgNbjcJ33Ucfm3XtYp819BxHfsQ2xtmb+BNwqCubjQCdcvLy3iZOb82CxqAuuVRYXQfrnlBMKlvflu5QtE/FQ1A3YpgMuXhCpcD1c390dkrFP1T0RDUHZiEGeYbXEzMzOnRQf7rDMMc4nV5JW/K7x8Cg/mD2WVm5uvRYT4/c/UKXwsagLpvQv5IOGT+Er6Cw56NCiZByDOHo6a8MPotD7+BN4MvHwiOmWUwTIpT3xIag7ozYZYxCd8E08zM/gxzKgjMLNDHrDAreWH2cPlQAE8+EA6BuoOzs6vX93rQANSdCUczgmlZyAMz4Iyns3nw32+QM/LgqUcCZJBZ4eDoyDEK1AkNlDQagro8mNRX4RSpWzYJs2B1M8zK7IEgnIGrnorUne6fnS0b1CmA1O1DTFtZAcr2hSMGr8sraHGzQN3s8swZGCXIMQZ1CiB1K6MQ36CDt3wK4cwhCH/tj5oOIE0wXwUBXBYMENLFjEGdAt9mIZydnh4yM7OzM8z+wezMaf5s5WvedPQN7n49OIDEAF2Wo30UaKDxRgNQ16y4FupaGuZo4E1i6DreHZ6+0/+nlha6ruMEZ9O9ovJaUPEVobgVrze9lEq0+Cvt+wjUtKx2d5CoEKcka4CkU3sNo6OJ/8OAq8Cv3W48i/jx7+8/fvz7x5+kwk77wXuZYMW9JBqU+An57V/2An8TkqLb57D2Vp07jnaNvRM+Qv5mJfjxUWODyuC9XIVFaOwUcyuYA3ykpoMK+8PuPPzUtqfInwrm2B+0E7CB6uek7zAGKUdnfOR/SuZY9g91XHQ18//Hc3WEUupNxZPkDzV14LKKsBa4tl2XTYoQUR6gbyWEwhyYndw+h+47c4x4ECAqTZ8d6kh3Hu0kHts1eL+99Ry48bKlu8xLL9VfWfZ/5f5JoKOTkKV7nCEucT7oSrcjovRQx7K/kaQoIL67Z+m+9ufU6D4/WShCi7ryxtbw/Rx9acIVEOFq16DuI3GXJO7jLJM++PSkCQM0dNF6xCz7/TqOut11EPKdQt0/zfZCxdtAmPymZu7fGg733F+EaDn2Y9P+H6g3iiG1y/5jJAl9iCrt7h99b4ozIJ6ClPRQvpPm/K9jbwf4xs8/v//A/PDHR82lCQM0tKYvB2ZGt6RGtIbFd/GkWoaMBFEHXC6DNgMGDBgwYMCAgUZAJBbLXbWIEphCtl95K9c/JxdUfEpvFtnYFStys1gN2mxBbv4qRfwXtAUBLBO3qajrD9pWL38rBIM5JgLSESYSDBbkojnO1lTUxYJ8tsgG41cqg8O5Ez7LxDkVdcycTVJ2zsatMTEby/0Hn7zC2HN8c1G3yrPwiS4bmctk5sCHCvG1QqY/lzvOoCnm5jLFiyuaD9xdKxaxiWv9meNS42OcreR7InWFYua4AL/PF8XiisEYlhxfEyVYsG9Qyc8xBS4rltEfw8Lj/2XiEaSuMDdHq2YjomDj+9fE0MNyPM+xESbDsUGOz/JBPriGlgA/zeGV57CxWS4btPF8hJkDc+U4kbsYx8VyuVyJuniQhb+IMNkgy9qywFwB+GKzwYyoLs4VQcEqlBS3zWGwYDkQANPng/1AXS6mcuMGRtHG2fh4BBqVjeRYbpXJ8P25OM8VcmgbRW4OmOGZfq4Id23zTJbP5ArQRnC9HNNvE2MkOCwGuxJ1LAdt/4+ZtwFXbDDG5JhcEFwzUvLFNVs2wrMRPshkbbFcENx3lbehhuJaLMJzMZZrGqMDxOIsf9HkOS4DRjGPdsQwx9AMli/G+202MMk1ZOYYrG4e4rwtV+DYeDwbFFMAthxwbnU2LhvPMcd8Nh7ngyJhYJ2Z8zwU4fgC5JKibY3jI2scW4pwUEAEfwJ7zdweEXVhjucV1Nm4yDl18dX5AvqcmrrVuUJBpEYZ68Dxgbri6mqhIH4fWc3w3DknGT4DiiDQAUkidRGROgy4OZ4vgkXeDgV1YK24BhkBckU/n41EsuiwUuoyXBx7fkyRv3DYc+ogQQJtMbGhYDSFNYBIHX4FbEA4i6DjivdRJFjSt8qDt0M/hOfnGdFh50WHLVHHxbK8Okc3KuLQrbNhqM5xF2kiCNRhz+sY0kPMZhNDPHAJbcY0AXcj2DvrB8dkSw4JUd5W6tcF0fGzWfC/CGvDVIO3I5BQWFuxpA87Q3BhRV8G575IEwz2XIK5XBOlicj8cTZ7jAzk4tks9ibmoB+Ri4OxzccLpW+P18RrBgMb3o30QzBjCv3Z4pyYYUEaAR2O+DxTgPLwNnhptl+McJHV/my23C+OY6lQttjbKxSzYudE/C0Sh78rxOPN47IG7iL+D40znvkTU8q1AAAAAElFTkSuQmCC">
## git checkout master
# Обновите локальную ветку с сервера:

## git pull origin master

# Выполните команду:

## git merge merged-branch
# Для работы с конфликтами используются опции:

## --continue — позволяет продолжить слияние после разрешения конфликта,
## --abort — прерывает процесс слияния и возвращает ветку к начальному состоянию.
### Чтобы решить конфликт слияния при изменении строк, необходимо отредактировать файл, в котором возник конфликт. В нем нужно удалить маркеры конфликта и оставить те изменения, которые должны быть в итоговой версии. Чтобы решить конфликт с удалением файлов, нужно решить, вернуть ли удаленный файл в репозиторий или окончательно удалить его.

# Чтобы вывести список существующих веток, используйте команду:
## git branch
# Чтобы увидеть последний сохраненный коммит в каждой ветке, введите команду:

## git branch -v

# Чтобы вывести ветки, которые были слиты с текущей, используйте команду:

## git branch --merged

# Чтобы вывести ветки, которые еще не были слиты с текущей, используйте команду:

## git branch --no-merged
# Как закоммитить изменения в новую ветку
## После внесения изменений в новой ветке необходимо сделать коммит, чтобы сохранить код. Для этого используйте команды:

### git add .
### git commit -m "<комментарий>"
# Как отправить изменения в удаленный репозиторий
## Чтобы отправить локальную ветку в удаленный репозиторий, используем команду:
### git push origin your-branch
### где your-branch — имя ветки, которую хотите отправить.
# Чтобы переименовать ветку, на которой вы находитесь, используйте команду:

## git branch -m new-name
### где new-name — новое имя ветки.

## Если нам необходимо переименовать другую ветку, воспользуем командой:

## git branch -m old-name new-name
### где:

### old-name — старое имя ветки,
### new-name — новое имя ветки.
# Если отправить переименованную ветку в удаленный репозиторий, то появится ветка с новым именем, при этом ветка со старым именем не пропадет. Поэтому ветку со старым именем нужно удалить из удаленного репозитория:

## git push origin :old-name
# где old-name — старое имя ветки.

## Затем необходимо отправить новую ветку в удаленный репозиторий и настроить локальную ветку для отслеживания удаленной ветки:

## git push --set-upstream origin new-name
# где new-name — новое имя ветки.

## Как удалить ветку в Git
## Чтобы удалить локальную ветку в Git, используем команду:
## git branch -d your-branch
# если перейти на другую ветку, предварительно не сделав коммит, то все незакоммиченные изменения перенесутся на ветку, на которую вы перешли. Поэтому перед переходом необходимо проверять, закоммитили ли вы изменения в текущей ветке. Сделать это можно с помощью команды:

# Чтобы получить более конкретный вывод, можно использовать опции:

--author="your-name" — показывает коммиты, созданные заданным пользователем;
--after="date" — показывает коммиты, созданные после указанной даты;
--before="date" — показывает коммиты, созданные до указанной даты;
-n — показывает последние n коммитов;
--oneline — показывает укороченный вывод коммитов (в одну строку). Выводит только хэш и заголовок;
-p — выводит изменения, содержащиеся в коммите.
Это лишь часть опций. Полный список можно посмотреть с помощью команды:

## git log --help
## git status



## Для просмотра истории коммитов используйте команду:
# git log



