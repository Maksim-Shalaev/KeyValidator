# Отчёт о тестировании KeyValidator
## Краткое описание
25/03/2021 - 25/03/2021 было проведено функциональное тестирование приложения **KeyValidator**.    
 
На тестирование затрачено: 3 часа    
 
В результате тестирования выявлены следующие дефекты:    

* [Среди валидных значений присутствуют невалидные значения](https://github.com/Maksim-Shalaev/KeyValidator/issues/1)
* [Среди валидных значений присутствует ключ состоящий из 31 знака](https://github.com/Maksim-Shalaev/KeyValidator/issues/2)
* [Среди невалидных значений присутствуют валидные значения](https://github.com/Maksim-Shalaev/KeyValidator/issues/3)
* [Неполное описание по установке руководства использования KeyValidator](https://github.com/Maksim-Shalaev/KeyValidator/issues/4)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:  
 
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались данные:   
  
* **Валидные ключи для проверки:**
 * 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
 * 80b427f8-92cd-3aae-ba04-3927fbe17c6
 * b295bc63-9f03-3b4b-af80-969b39f8c262
 * 3387eedc6-12e9-3b32-9881-63b6b5e85317
 * c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
* **Невалидные ключи для проверки:**
 * 18252235-78e0-44a5-8720-556f0c7da17a
 * e66075b6-ddad-445e-baf6-161b3289522b
 * b6d53250-f07e-4352-a293-6102ddf7f1ca
 * c2bc778a-1cb9-46c6-b435-0489649d2a42
 * 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

   
Тестирование производилось в следующем окружении: 

* Windows 7   
* Java 11.0.10  
* Google Chrome 89.0.4389.90