# Custom-AI-Jeopardy-Games

you can go to Jeopardy.app and do a custom game. it asks you for a .csv file. you can generate the file by prompting chatGPT:

```
replace the questions and answers to one's about [insert categories, show ideas, etc]. its crucial to name the categories. randomize the dd value so there's 1 for jeopardy and 2 for double jeopardy. make sure to include a final jeopardy. keep the x and y values the same. it's crucial to not have spaces after the commas. keep it in a code block:
round,cat,val,q,a,dd,x,y
jeopardy,"A CATEGORY",200,"a question","a answer",true,1,1
jeopardy,"A CATEGORY",400,"a question","a answer",false,1,2
jeopardy,"A CATEGORY",600,"a question","a answer",false,1,3
jeopardy,"A CATEGORY",800,"a question","a answer",false,1,4
jeopardy,"A CATEGORY",1000,"a question","a answer",false,1,5
jeopardy,"ANOTHER CATEGORY",200,"a question","a answer",false,2,1
jeopardy,"ANOTHER CATEGORY",400,"a question","a answer",false,2,2
jeopardy,"ANOTHER CATEGORY",600,"a question","a answer",false,2,3
jeopardy,"ANOTHER CATEGORY",800,"a question","a answer",false,2,4
jeopardy,"ANOTHER CATEGORY",1000,"a question","a answer",false,2,5
jeopardy,"CATEGORY 3",200,"a question","a answer",false,3,1
jeopardy,"CATEGORY 3",400,"a question","a answer",false,3,2
jeopardy,"CATEGORY 3",600,"a question","a answer",false,3,3
jeopardy,"CATEGORY 3",800,"a question","a answer",false,3,4
jeopardy,"CATEGORY 3",1000,"a question","a answer",false,3,5
jeopardy,"CATEGORY 4",200,"a question","a answer",false,4,1
jeopardy,"CATEGORY 4",400,"a question","a answer",false,4,2
jeopardy,"CATEGORY 4",600,"a question","a answer",false,4,3
jeopardy,"CATEGORY 4",800,"a question","a answer",false,4,4
jeopardy,"CATEGORY 4",1000,"a question","a answer",false,4,5
jeopardy,"CATEGORY 5",200,"a question","a answer",false,5,1
jeopardy,"CATEGORY 5",400,"a question","a answer",false,5,2
jeopardy,"CATEGORY 5",600,"a question","a answer",false,5,3
jeopardy,"CATEGORY 5",800,"a question","a answer",false,5,4
jeopardy,"CATEGORY 5",1000,"a question","a answer",false,5,5
jeopardy,"CATEGORY 6",200,"a question","a answer",false,6,1
jeopardy,"CATEGORY 6",400,"a question","a answer",false,6,2
jeopardy,"CATEGORY 6",600,"a question","a answer",false,6,3
jeopardy,"CATEGORY 6",800,"a question","a answer",false,6,4
jeopardy,"CATEGORY 6",1000,"a question","a answer",false,6,5
double,"A CATEGORY",400,"a question","a answer",true,1,1
double,"A CATEGORY",800,"a question","a answer",true,1,2
double,"A CATEGORY",1200,"a question","a answer",false,1,3
double,"A CATEGORY",1600,"a question","a answer",false,1,4
double,"A CATEGORY",2000,"a question","a answer",false,1,5
double,"ANOTHER CATEGORY",400,"a question","a answer",false,2,1
double,"ANOTHER CATEGORY",800,"a question","a answer",false,2,2
double,"ANOTHER CATEGORY",1200,"a question","a answer",false,2,3
double,"ANOTHER CATEGORY",1600,"a question","a answer",false,2,4
double,"ANOTHER CATEGORY",2000,"a question","a answer",false,2,5
double,"CATEGORY 3",400,"a question","a answer",false,3,1
double,"CATEGORY 3",800,"a question","a answer",false,3,2
double,"CATEGORY 3",1200,"a question","a answer",false,3,3
double,"CATEGORY 3",1600,"a question","a answer",false,3,4
double,"CATEGORY 3",2000,"a question","a answer",false,3,5
double,"CATEGORY 4",400,"a question","a answer",false,4,1
double,"CATEGORY 4",800,"a question","a answer",false,4,2
double,"CATEGORY 4",1200,"a question","a answer",false,4,3
double,"CATEGORY 4",1600,"a question","a answer",false,4,4
double,"CATEGORY 4",2000,"a question","a answer",false,4,5
double,"CATEGORY 5",400,"a question","a answer",false,5,1
double,"CATEGORY 5",800,"a question","a answer",false,5,2
double,"CATEGORY 5",1200,"a question","a answer",false,5,3
double,"CATEGORY 5",1600,"a question","a answer",false,5,4
double,"CATEGORY 5",2000,"a question","a answer",false,5,5
double,"CATEGORY 6",400,"a question","a answer",false,6,1
double,"CATEGORY 6",800,"a question","a answer",false,6,2
double,"CATEGORY 6",1200,"a question","a answer",false,6,3
double,"CATEGORY 6",1600,"a question","a answer",false,6,4
double,"CATEGORY 6",2000,"a question","a answer",false,6,5
final,"FINAL CATEGORY",0,"a question","a answer",false,1,1
```
Share your Custom .csv Files to this github!
