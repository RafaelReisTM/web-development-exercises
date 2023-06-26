mkdir unix_tests_search && cd unix_tests_search
curl -o countries.txt "https://gist.githubusercontent.com/kalinchernev/486393efcca01623b18d/raw/daa24c9fea66afb7d68f8d69f0c4b8eeb9406e83/countries"

01-	cat countries.txt

02-	less countries.txt

03-	more countries.txt
	/Zambia
	
04- grep Brazil countries.txt

05- grep -i brazil countries.txt

cat > phrases.txt
Aqui nao contem a palavra fox
Haja contradicao
houston, we have a problem

06- grep -v fox phrases.txt

07- wc -w phrases.txt

08- wc -l phrases.txt

09- touch empty.tbt empty.pdf 

10- ls -a

11- ls -a *txt

12- ls -a *t?b

13- man ls