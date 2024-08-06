# Exercicio1
Exercicio aula ci / cd 


b) Adicionar o arquivo no staging e conferir o status
git add arquivo.tx
git status 
![image](https://github.com/user-attachments/assets/91438d92-b7b1-4085-928d-4cd2a4b87dd6)

c) Commitar o arquivo do staging com a descrição "git add example - arquivo.txt“
git commit -m "git add example - arquivo.txt"
![image](https://github.com/user-attachments/assets/d3766db1-1b3d-4783-abd7-f34b8e1e9d54)

d) Sobrescrever o conteúdo do arquivo.txt:
![image](https://github.com/user-attachments/assets/4f17e7e1-a0a1-4543-9757-1e363684ab5b)

e) Verificar o diffing no arquivo
git diff 
![image](https://github.com/user-attachments/assets/0c7491a3-9a35-4114-bfd6-8086750371c5)

f) Adicionar novamente o arquivo no staging e conferir o status
![image](https://github.com/user-attachments/assets/067d9017-dbd9-4e83-ac43-a155bda684ec)
OBS: neste momento aproveitei e corrigi o nome do arquivo que estava errado 

g) Verificar o diffing no arquivo
git diff  
![image](https://github.com/user-attachments/assets/091a946d-4fc7-499a-ba83-bc88b9ceac77)

h) Sobrescrever o conteúdo do arquivo.txt:
echo 03 > arquivo.txt

i) Verificar o diffing no arquivo,
git diff
![image](https://github.com/user-attachments/assets/9afd1d98-4624-49c3-9a8a-3934888bda7e)

j) Fazer o restore do arquivo da área de staging e verificar o status
git restore arquivo.txt
![image](https://github.com/user-attachments/assets/69520241-b918-45d6-918a-bb7750f7dfb7)

k) Realizar o commit do arquivo e verificar o log
git commit -m "commit arquivo.txt"
![image](https://github.com/user-attachments/assets/1c4756e5-4d5b-4d9a-a51c-877c18b3a8e8)

git log 
![image](https://github.com/user-attachments/assets/d2ef6d7e-a7f5-49b1-a596-563845758082)

l) Adicionar um arquivo gitignore com o seguinte conteúdo:
echo *.txt > .gitignore

m) Criar um arquivo novo.txt e verificar o status
git status
![image](https://github.com/user-attachments/assets/2262102d-b3bf-4947-84d0-ac55e855e2f9)










