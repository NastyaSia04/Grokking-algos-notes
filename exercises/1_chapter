// Реализация бинарного поиска на JavaScript:

function binarySearch(arr, target) {
  let left = 0;
  let right = arr.length - 1;

  while (left <= right) {
    let mid = Math.floor((left + right) / 2);

    if (arr[mid] === target) {
      return mid; // нашли элемент, возвращаем его индекс
    } else if (arr[mid] < target) {
      left = mid + 1; // ищем в правой половине
    } else {
      right = mid - 1; // ищем в левой половине
    }
  }

  return -1; // если элемент не найден
}