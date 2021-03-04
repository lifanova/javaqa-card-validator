# Отчёт о тестировании приложения Credit Card Number Validator #

## Краткое описание ##

4.03.2021 - 4.03.2021 было проведено тестирование установки IDE Intelij IDEA 2020.3.2 x64 в Windows 8 x64 и тестирование работы приложения Credit Card Number Validator на предмет:
- приложение запускается с командной строки и через конечное время завершает работу;
- приложение верно определяет валидные и невалидные номера карт.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
- [Карты с номерами, длина которых меньше или больше 16 цифр, не проходят валидацию](https://github.com/lifanova/javaqa-card-validator/issues/1)

## Описание процесса тестирования ##

В процессе тестирования использовались следующие артефакты:
- [Инструкция по установке Intelij IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
- [Руководство использования Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)



В качестве тестовых данных использовались данные из
[Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):
  
  VISA:

- 4485522667614381 
- 4765644440452417
- 4716547995289868414 

MasterCard:

- 5209390050085821
- 5419378783031820
- 5581780813761569

Maestro:

- 6762718481738773
- 5018047717896153
- 6763905566916338

Visa Electron:

- 4913711699380176
- 4844455370250787
- 4508361723429986 

American Express (AMEX):

- 349879049146506
- 342191061728378
- 341453185925202



Тестирование производилось в следующем окружении:
- Windows 8, x64
- OpenJDK 11
- Intelij IDEA 2020.3.2 x64