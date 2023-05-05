# ZerotoHero

### 1 день обучения

```python
model = keras.Sequential([keras.layers.Dense(units=1, input_shape=[1])])
```
Опредляет саму модель,это обучающие нероная сеть.

Это дает вызов:
```python
([keras.layers.Dense(units=1, input_shape=[1])])
```
В этом слои находится нейрон:
```python
units=1
```

Так же даем сеть значения  переменый Х
```python
input_shape=[1]
```

Передаем функции: 
```python
model.compile(optimizer = 'sgd', loss ='mean_squared_error')
```
Функция потерь и оптимизации
