# decoding-numbers

### Розпізнавання Чисел

Цей проект є реалізацією програми для розпізнавання чисел. Вона використовує алгоритми машинного навчання для ідентифікації та класифікації чисел у зображеннях.

## Опис

Програма здатна розпізнавати цифри від 0 до 9 на основі зображень. Вона була навчена на наборі даних MNIST, який є стандартом у сфері розпізнавання рукописних цифр.

## Вимоги

- Python 3.8+
- TensorFlow 2.0+
- NumPy
- Matplotlib

## Встановлення

1. Клонуйте репозиторій:

    ```bash
    git clone https://github.com/dimon2202/decoding-numbers.git
    ```

2. Перейдіть у директорію проекту:

    ```bash
    cd number-recognition
    ```

3. Встановіть необхідні залежності:

    ```bash
    pip install -r requirements.txt
    ```

## Використання

Для запуску програми використовуйте наступну команду:

```bash
python recognize.py path_to_image
```

Замініть `path_to_image` на шлях до зображення, яке ви бажаєте розпізнати.

## Структура Проекту

- `recognize.py`: Основний файл для запуску розпізнавання.
- `model.py`: Файл з визначенням моделі нейронної мережі.
- `utils.py`: Допоміжні функції для обробки зображень та передобробки даних.
- `requirements.txt`: Список необхідних залежностей.

## Приклади

```bash
python recognize.py test_images/number1.png
```

 ## Приклад 1
![image](https://github.com/dimon2202/decoding-numbers/assets/114134488/b5efb86f-7303-4789-80c5-23eba32aa987)

![image](https://github.com/dimon2202/decoding-numbers/assets/114134488/f9ecd4cc-110f-4d36-87d4-9e9cf6d9d9d6)

```
Розпізнане число: 5
```
## Приклад 2
![image](https://github.com/dimon2202/decoding-numbers/assets/114134488/1cf1b733-79d2-4ba5-8385-1bfed7ecccc1)
![image](https://github.com/dimon2202/decoding-numbers/assets/114134488/339b50f3-1637-401a-ab00-e4bd34c7c52f)

```
Розпізнане число: 4
```



## Контакти
Для питань чи пропозицій, будь ласка, зв'яжіться за поштою: dmytro.sidenko@kneu.ua.








