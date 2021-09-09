instala com isso ai

![image](https://user-images.githubusercontent.com/58860863/132764390-a83e2871-c3d1-430d-8479-fd406492c23d.png)

Em seguida cria esse middleware aqui

![image](https://user-images.githubusercontent.com/58860863/132764407-6f99f239-81bf-4c13-be08-7845e2523221.png)

No kernel.php, nomeia o middleware

![image](https://user-images.githubusercontent.com/58860863/132764427-748a52fe-ff86-4dc8-945a-dfe817163430.png)

De forma resumida, a rota de login te retorna um token jwt e voce precisa dele pra acessar rotas autenticadas.

Na model de user, que será o fato de autenticação, coloque essas informações:

![image](https://user-images.githubusercontent.com/58860863/132764443-a4235dcc-176c-4d82-a41b-e9df2c332653.png)

E também esse outros dois métodos

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/63dc7e20-2b21-4f77-b318-755947207462/Untitled.png)

A sua rota de API ficará assim:

![image](https://user-images.githubusercontent.com/58860863/132764455-f682c2b6-a9b0-41e4-ba62-6201a48f1243.png)
