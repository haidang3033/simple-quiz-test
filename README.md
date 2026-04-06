
use .xlsx file
| no | group no.  | type | quesion | note | answers | --> | ... |
|--|--|--|--|--|--|--|--|
| 1 |  | 1 | do you like burger | note here | #.no | #.no | ##.yes|


no.    group no.    type    question    note    answers->...
1                    1      buger                #.no    #.no    ##.yes    #.no

- no.: number order
- group no.: for questions that belong in a group with a paragraph or idk...
- type: 
	
	1 - one choice; 2 - multiple choice; 3 - drag and order
- question: the question
- note: will show below the question
 - answers: no limit the amount of answers
 
		#. mean wrong answer
        ##. correct answer
        condition: type 1 question must not have >=2 ##. answer
                   type 3 question only require you to type in the whole sentence then add ##. at the start

you can use markdown
