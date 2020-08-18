# Отчёт о тестировании Precision
## Краткое описание
18.08.20 - 18.08.2020 было проведено Sanity Tasting приложения Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

- https://github.com/Shavonsky/Precision/issues/1
## Описание процесса тестирования



В качестве тестовых данных использовались данные https://github.com/netology-code/javaqa-homeworks/tree/master/programming:

```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```

Тестирование производилось в следующем окружении:

- Windows 7, 64-bit
- Java version "11.0.8" 2020-07-14