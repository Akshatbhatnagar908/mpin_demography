Background 
Read about MPIN that is used to access mobile banking apps. Many a times users end up setting an MPIN that is 
guessable because  
1. It is a commonly used MPIN eg 1122  
2. It is a combination of easily known demographics of the user. Eg: if the birthdate is 02 Jan-1998 then MPIN 
could be 0201 or 9802 or 0201 etc. Demographics such as these could be used alone or in a combination  
a. DOB  
b. Wedding Anniversary  
c. Spouse birthday

Expected Outcome 
1. Part A: Assume that the MPIN is 4-digits. Write a program that suggests if the MPIN is a commonly used one. 
Ignore the demographics for this part  
2. Part B: Enhance the above to take user’s demographics as input and provides an output  
a. Strength: WEAK or STRONG  
3. Part C: Enhance the above to provide the following outputs  
a. Strength: WEAK or STRONG  
b. If weak then the reason why was it considered weak: It should give from the following the reasons as an     
array. Array should be empty if Strength is STRONG and non-empty if WEAK  
• COMMONLY_USED  
• DEMOGRAPHIC_DOB_SELF 
• DEMOGRAPHIC_DOB_SPOUSE 
• DEMOGRAPHIC_ANNIVERSARY 
4. Part D: Above with a 6-digit PIN 
5. Write code that tests the above written code using a set of inputs. Write at least 20 test case scenarios 
