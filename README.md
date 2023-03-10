# 10.3 «Pacemaker» - НиконоровДА FOPS-6

## Задание 1

*Опишите основные функции и назначение Pacemaker.*

*Приведите ответ в свободной форме.*

**Pacemaker позволяет:**
* мониторить статус приложений;
* оповещать приложения о смене активной ноды в кластере;
* отправлять идентичные сообщения процессам на всех нодах;
* предоставлять доступ к общей базе данных с конфигурацией и статистикой;
* отправлять уведомления об изменениях, произведенных в базе.

**Pacemaker — мозг и менеджер ресурсов кластера (скриптов на любом языке, обычно на bash),  отвечающий за доступность ресурсов и их защиту от сбоев. Pacemaker реагирует на события,  происходящие в кластере, и выполняет определенные действия: остановку, запуск, перенос ресурсов и др.**

## Задание 2

*Опишите основные функции и назначение Corosync.*

*Приведите ответ в свободной форме.*

**Corosync - программный продукт, позволяющий реализовать кластер серверов.  Его основное назначение — знать и передавать состояние всех участников кластера.**

**В него заложены следующие функции:**

* Отслеживание состояния приложений.
* Оповещение приложений о смене активной ноды кластера.
* Отправка одинаковых сообщений процессам на всех узлах кластера.
* Предоставление доступа к базе данных с конфигурацией и статистикой, а также отправка уведомлений о ее изменениях.

## Задание 3

*Соберите модель, состоящую из двух виртуальных машин.  Установите Pacemaker, Corosync, Pcs. Настройте HA кластер.*

*Пришлите скриншот рабочей конфигурации и состояния сервиса для каждого нода.*

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/9.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/10.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/7.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/8.png)

## Задание 4

*Установите и настройте DRBD-сервис для настроенного кластера.*

*Пришлите скриншот рабочей конфигурации и состояние сервиса для каждого нода.*

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/1.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/2.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/3.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/4.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/5.png)

![alt text](https://github.com/mxssclxck/hw-10.3/blob/main/img/6.png)
