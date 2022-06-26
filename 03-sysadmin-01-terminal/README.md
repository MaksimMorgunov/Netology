# Домашнее задание к занятию "3.1. Работа в терминале, лекция 1"

1. Уставнока виртуальной машины Debian 11.3 на HYPER-V
2. Включение вложенной виртуализиции Hyper-v
3. 
![2022-06-21_22-27-43](https://user-images.githubusercontent.com/106722971/175811993-6b8581b6-dc94-4131-887f-2287f68e695c.jpg)

3. Установка vagranta через предварительно подготовленный впн wireguard 

![2022-06-21_23-30-28](https://user-images.githubusercontent.com/106722971/175812171-4fc2a7c1-c6d6-4b72-b54f-04c9d742ea43.png)

4. ![2022-06-26_20-50-11](https://user-images.githubusercontent.com/106722971/175815090-cd164934-8b20-423c-8421-a9d9eede5b94.png)

5.  v.memory = 1024
    v.cpus = 2

5. HISTFILESIZE - максимальное количество строк

![2022-06-26_15-19-05](https://user-images.githubusercontent.com/106722971/175812211-54748f69-e825-4e1b-b7c9-11a48300174a.png)

6. ignoreboth — использовать обе опции ‘ignorespace’ и ‘ignoredu
 - ignorespace — не сохранять строки начинающиеся с символа <пробел>
 - ignoredups — не сохранять строки, совпадающие с последней выполненной командой

7. {} - зарезервированные слова, список - 
 ![2022-06-26_20-56-50](https://user-images.githubusercontent.com/106722971/175815238-40cf07e2-fb4f-40cc-ac2a-7ad6a96119cc.png)
 
8. touch {000001..100000}.file
  - root@vagrant:/home/vagrant/1# touch {000001..300000}.txt
    bash: /usr/bin/touch: Argument list too long <-- почему не хватает аргументов не разобался 
9. "-d" file - True if file exists and is a directory. 

10. at - команда запускается в указанное время
    batch - запускается когда уровень загрузки системы снизится ниже 1.5 или указаное в сервисе atd
    
11. root@debian:/home/firewall/1# vagrant suspend
    ==> default: Saving VM state and suspending execution...

