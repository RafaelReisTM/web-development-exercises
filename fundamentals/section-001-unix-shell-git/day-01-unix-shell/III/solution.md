01-	mkdir unix_tests_skills && cd unix_tests_skills

02-	cat > skills2.txt
	Internet
	Unix
	Bash

03-	cat >> skills2.txt
	HTML
	CSS
	JavaScript
	React
	Node.js
	
    cat skills2.txt | sort
	
04- wc -l skills2.txt

05- sort < skills2.txt | head -n 3 > top_skills.txt

06- cat > phrases2.txt      
	Bla Bla Bla
	Qualquer coisa
	estou sem imaginacao
	mas sou espirituoso

07- grep br phrases2.txt | wc -l

08- grep -v br phrases2.txt | wc -l

09- cat >> phrases2.txt 
	Brazil
	USA

10- cat phrases2.txt ../../II/unix_tests_search/countries.txt > bunch_of_things.txt

11- sort bunch_of_things.txt -o bunch_of_things.txt
