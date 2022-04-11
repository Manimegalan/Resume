<---------------------------- Regex explanation ---------------------------->  
/^/$|/index(.html)?/  

^/ ---> Starts with slash  
/$ ---> Ends with slash  
| ---> Or  
()? ---> Optional  

<---------------------------- Username Regex ---------------------------->  
/^[a-zA-Z][a-za-z0-9-_]{3,23}$/  
[a-zA-Z] ---> First charater between small/capital alphabets  
[a-zA-Z0-9-_] ---> Second charater between small/capital/numbers/Underscore  
{3,23} ---> Total length between 3 to 23 characters  

<---------------------------- Password Regex ---------------------------->  
/^(?=.*[a-z])(?=.*[A-Z])(?=.*[0-9])(?=.*[!@#$%]).{8,24}$/  
Password between small/capital alphabets/numbers/special characters(!@#$%) and lenght should be 8 to 24 characters.  
