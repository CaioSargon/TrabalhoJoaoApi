# TrabalhoJoaoApi

<a href="https://drive.google.com/file/d/1s1skBk_mD48qpY2vsfG6fm9gPSD1_ijl/view?usp=sharing">Link do trabalho </a>


## Documentação da API

#### Retorna todos os itens

```http
  GET /tasks
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `null`   | `null`   | nao precisa passar|



```http
  GET /tasks/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `int` | retorna uma tarefa especifica |





```http
  POST/tasks
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `null`      | `null` | Não precisa passar |





```http
  PUT/tasks/{id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `int` | atualiza uma tarefa especifica |




```http
  DELETE/tasks/{id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `int` | Deleta uma tarefa especifica |
