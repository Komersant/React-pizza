# React-pizza

### В проекте использовались такие технологии
<img src="https://img.shields.io/badge/Sass(Scss)-black?style=for-the-badge&logo=Sass&logoColor=red"/> <img src="https://img.shields.io/badge/JavaScript-black?style=for-the-badge&logo=JavaScript&logoColor=red"/> <img src="https://img.shields.io/badge/React-black?style=for-the-badge&logo=React&logoColor=red"/> <img src="https://img.shields.io/badge/React Router 6-black?style=for-the-badge&logo=React Router&logoColor=red"/> <img src="https://img.shields.io/badge/Redux Toolkit-black?style=for-the-badge&logo=Redux&logoColor=red"/> <img src="https://img.shields.io/badge/Typescript-black?style=for-the-badge&logo=TYpescript&logoColor=red"/> 

1. В качестве сервера использовался сервис mockapi.io
2. Запрос на сервер происходил через createAsyncThunk - Redux Toolkit и с помощью extraReducers передавали в state состояние запроса.
3. Сортировка по категориям: сортировка пицц происходит с помощью метода filter, полученный массив пицц, который приходит из сервера, фильтруеться и возвращает ту категорию(id категории), которая указана с строке запроса с помощью React Router NavLink
4. Поиск: поиск происходит по массиву пиц с помощью метода filter , если title в массиве совпадает с value в input тогда filter вернёт совпадения.
5. Фильтрация: фильтрация происходит с помощью метода sort.  
