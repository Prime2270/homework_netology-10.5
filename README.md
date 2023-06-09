# Домашнее задание к занятию "`10.5 «Балансировка нагрузки. HAProxy/Nginx»`" - `Яковлев Константин`

### Задание 1 `Что такое балансировка нагрузки и зачем она нужна?`

```
Балансировщик нагрузки — это
сервис, который занимается
распределением нагрузки между
пулом приложений, которые
находятся за ним, стараясь
максимизировать скорость и
утилизировать ресурсы приложений.
Также, гарантирует, что приложения
не будут перегружены.
```

### Задание 2 `Чем отличаются алгоритмы балансировки Round Robin и Weighted Round Robin? В каких случаях каждый из них лучше применять?`

```
- в алгоритме Round Robin используеться принцип "полседовательно всем", 
что означает что нагрузка будет распределена последовательно
и равномерно между всеми узлами. Хорошо когда конфигурации оборудывания идентичны.

- в алгоритме Weighted Round Robin используеться тот же принцип что и в Round Robin,
 но у него есть дополнительное свойство, так называемый "вес сервера",
с его помощью можно указать балансировщику сколько трафика отпарвлять на сервер.
```

### Задание 3 `Установите и запустите Haproxy.`

![job3](https://github.com/Prime2270/homework_netology-10.5/blob/main/screenshots/job3.png)

### Задание 4 `Установите и запустите Nginx.`

![job4](https://github.com/Prime2270/homework_netology-10.5/blob/main/screenshots/job4.png)

### Задание 5 `Настройте Nginx на виртуальной машине таким образом, чтобы при запросе:

curl http://localhost:8088/ping

он возвращал в ответе строчку:

"nginx is configured correctly".`


![job5.1](https://github.com/Prime2270/homework_netology-10.5/blob/main/screenshots/job5.1.png)

![job5.2](https://github.com/Prime2270/homework_netology-10.5/blob/main/screenshots/job5.2.png)
