# gitClass2023

1.  Das novidades que estou vendo, a primeira que mais me chamou a atenç©ão foi a possibilidade de abrir o VS CODE no navegador, simplesment apertando . (ponto) em um projeto aberto no github. 

2.  A segunda é algo que tinha visto as pessoas utilizando porém o receio me impedia de estudar, o commit e push a partir do source control do giyhub é realmente eficiente. 

3. O comando `git log` serve para demonstrar o histórico dos commits feitos no projeto 

4. aparentemente não é necessario utilizar o `git add` nem o `-u` no git push, o flow demonstrado seria: 
```
git commit src/components -m "comitando sem o add"
git push
```
desta forma ficaria menos verboso, mas não sei se é mais seguro do que a maneira que geralmente uso

neste link eu vejo novidades a serem aprendidas: https://www.youtube.com/watch?v=ecK3EnyGD8o

5. para restaurar um commit anterior podemos fazer o seguinte: 
```
git logs --oneline
git restore --source 8d55591 .
``` 

esse id utilizado no restore aparecerá no logs