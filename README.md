<!DOCTYPE html> 
<html><head><title> 
String functions 
</title></head><body> 
<form name="frm1"> 
Enter Your Name 
<input type="text" name="t1"><br><br> 
<input type="button" name="btncheck" value="Count Vowels" onClick="cnt()"> 
</form></body> 
<script type="text/javascript"> 
function cnt() 
{ 
var s,i,ch,c; 
c=0; 
s=frm1.t1.value; 
for(i=0;i<=s.length;i++) 
{ 
ch=s.charAt(i); 
if(ch=="A"||ch=="a"||ch=="E"||ch=="e"||ch=="I"||ch=="i"||ch=="O"||ch=="o"||ch=="U"||ch=="u")  
c++; 
} 
alert("Number of Vowels in string are "+c); 
} 
</script></html>
