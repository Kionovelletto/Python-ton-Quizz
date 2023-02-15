# Simple-Python-Quizz

Sistema simplório de quizz, utilizado em estudos.

![image](https://user-images.githubusercontent.com/15057595/218906163-e54d400e-179c-459f-8f80-ff49525c4db9.png)

## Build image container 🐋

- ⚙️ Primeiramente construa a imagem do sistema quizz:
```container
docker build -t simple-python-quizz:0.0.1 .
```

- ⚙️ Após o build, execute o container e reponda ao quizz:
```container
docker run -it simple-python-quizz:0.0.1
```
