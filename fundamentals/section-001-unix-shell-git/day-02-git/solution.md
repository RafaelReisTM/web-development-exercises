1- 	git checkout -b atualiza-readme

2- 	touch infos.txt 

3- 	git add . && git commit -m 'infos.txt created'

4- 	'Rafael Silva Reis
     srp.rafael@gmail.com'

5-	git add . && git commit -m 'changes in infos.txt'

6-	git checkout -b adiciona-infos 

7-	add infos in README.txt

8-	git add . && git commit -m 'changes in README.txt'

9-	git checkout atualiza-readme
    git merge adiciona-infos

10-	git checkout master
    git merge atualiza-readme

