# Тренировочный проект для работы с Git.

---

*README.md* — текстовый файл, который можно создать командой **touch**, а затем редактировать так же, как и любой другой текстовый документ. Например, в блокноте.

Преимущество *README.md* в том, что средства командной работы (такие, как GitHub) могут отображать его содержимое в браузере в виде удобной разметки.

Для этого нужно не просто залить текст, но и настроить шрифт, заголовки и отступы с помощью markdown.

Маркда́ун — это специальный язык разметки.

Он позволяет красиво отформатировать текстовый документ.

---

## Пример вставки кода в файл

```JavaScript
function closure () {
	let count = 0; 
	return () => count++
};

let counter = closure()
let counter1 = closure()

console.log(counter()) //0
console.log(counter()) //1
console.log(counter()) //2
console.log(counter()) //3
console.log(counter()) //4
console.log(counter1()) //0
console.log(counter1()) //1
console.log(counter()) //5
```