const devices = [] - const devices = new Set(); // для хранения списка девайсов можно использовать множество вместо массива

const groupId = groupResponse.data.value[0].id; 

|
v

const groups = groupResponse.data.value.values();

const firstGroup = groups.next();

// здесь происходит обращение к элементу массива по индексу, что не является правильным подходом. Если использовать множества, то можно получить первый элемент путем последовательного перебора элементов множества.

if (!response || response[0].statusCode != 202) {
    ...
}

|
v

const responses = response[Symbol.iterator]();

const firstResponse = responses.next();

if (!response || firstResponse.statusCode != 202) {
    ...
}

// здесь происходит обращение к элементу массива по индексу, что не является правильным подходом. Для более безопасной работы с массивом, можно получить его итератор и при помощи свойства next получить первый элемент массива.

const data = [1, 2, 3, 4, 5];

for (let i = 0; i < data.length; i =+ 1) {
    const item = data[i];
    ...
}

|
v

const iterator = data[Symbol.iterator]();

while (true) {
  const item = iterator.next();

  if (item.done) break;

  ...
}

// также вместо прямого доступа по индексу можно воспользоваться перебором при помощи итератора
