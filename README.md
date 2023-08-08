# darkness
这不是一个完整的小游戏的代码
导入random模块：在代码中，首先需要导入random模块，以便可以使用它提供的功能。
import random
生成随机数：使用random.random()函数可以生成一个[0, 1)之间的随机浮点数。
random_float = random.random()
print("Random float: ", random_float)
生成指定范围内的随机数：使用random.uniform(a, b)函数可以生成一个[a, b]之间的随机浮点数。
random_float_range = random.uniform(1.0, 10.0)
print("Random float in range: ", random_float_range)
生成指定范围内的随机整数：使用random.randint(a, b)函数可以生成一个[a, b]之间的随机整数。
random_int_range = random.randint(1, 10)
print("Random integer in range: ", random_int_range)
随机选择元素：使用random.choice(seq)函数可以从序列seq中随机选择一个元素返回。
fruits = ["apple", "banana", "orange"]
random_fruit = random.choice(fruits)
print("Random fruit: ", random_fruit)
随机打乱序列：使用random.shuffle(seq)函数可以将序列seq中的元素随机打乱，改变原序列。
numbers = [1, 2, 3, 4, 5]
random.shuffle(numbers)
print("Shuffled numbers: ", numbers)
随机选择多个元素：使用random.sample(population, k)函数可以从population中随机选择k个元素返回，不改变原序列。
letters = ["A", "B", "C", "D", "E"]
random_letters = random.sample(letters, 3)
print("Random letters: ", random_letters)
初始化随机数生成器的种子：使用random.seed(a=None)函数可以初始化随机数生成器的种子，默认使用系统时间作为种子。
random.seed(123)
random_number = random.random()
print("Random number with seed: ", random_number)
