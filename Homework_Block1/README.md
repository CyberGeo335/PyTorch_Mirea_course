Домашнее задание 1: реализуйте XOR с помощью 3 нейронов. Запишите ответ в виде выражения, состоящего из объектов neuron() – моделей нейрона с пороговой функцией активации, внутри скобок может быть что угодно. Входы верхнего уровня называются x1 и x2. Пример фрагмента записи: neuron(1x1 + 5x2 - 0.1) + neuron(x1) (ответ будет выглядеть чуть сложнее, но других символов вроде && не потребуется).

Домашнее задание 2: нарисуйте backward граф для выражения a*b+c*d. Теория и пример оформления. Сравните полученные теоретические значения с аттрибутами grad у исходных тензоров.

Домашнее задание 3: Поэксперементируйте с размером тензоров, которые влезут на видеоркарту в Colab. Найдите максимальный размер тензора для типа данных float32, float64, float16, int32, int64. На сколько они отличаются.

Домашнее задание 4: Напишите хороший пример неэффективного кода для занятия памяти видеокарты, который вызовет ошибку out of memory

Домашнее задание 5: Используя один линейный слой nn.Linear и один входной тензор x подберите подберите размерности так, чтобы занимать всю видеопамять. Попробуйте применить линейный слой к тензору x. Что произойдет? Кратко опишите ваши эксперименты. Что вы поняли?
