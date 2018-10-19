# Q2ArrayofdigitsIntoDigitNames
Fikra Camps Assignment
hi fikracamps,
1- build the Html with form of 2 text boxes 1 for array length and 1 for inserting items and 2 commands (insert into array & show array).
2- first assumed the array was of constant numbers
var a = [1, 2, 1, 24];
 
for (var i=0; i< a.length;i++)
     {
       if (myFunction(a[i])) {
         document.write( "'" + myFunction(a[i]) + "'" + " ");}
     else{
          document.write("'" + "more than 2 digit" + "'" );
     }
         
    }
   
   function myFunction(p1) {
     if (p1==1 ) {return ("one")}
     if (p1==2 ) {return ("two")}
     if (p1==3 ) {return ("Three")}
     if (p1==4 ) {return ("Four")}
     if (p1==5 ) {return ("Five")}
     if (p1==6 ) {return ("Six")}
     if (p1==7 ) {return ("Seven")}
     if (p1==8 ) {return ("Eight")}
     if (p1==9 ) {return ("Nine")}
     if (p1==0 ) {return ("zero")}
     
}

3 - Next after success starting looking on how to insert numbers into array and found helpful thread in stackoverflow.
4-after figuring out how to insert array dynamically i merged the two codes and produced my webpage.

