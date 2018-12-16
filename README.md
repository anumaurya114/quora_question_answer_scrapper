### Quora_question_answer_scrapper  
Run the bat file run_it.bat ( if OS is windows.) Otherwise run the first install  
requirements. Then run scrap_quora.py  
Something like this will print on the console.

---
    Instructions for user.
    You will be asked for three inputs.
    base_url : default set (need not to change)
    topics   : topics mentioned on quora related to that exam : Please enter comma seperated topic names.
    file_name: File name (csv file) in which the all data will be stored.
    Exam_name: exam name i.e. CAT or GRE,  to which exam given topics are related to. examples- CAT or GRE
    default values are below....
    base_url='https://www.quora.com/',topics=['Common-Admission-Test-CAT'],file_name="quora_question_answer_cat.csv",Exam_name='CAT'
    Enter the topic names as mentioned on quora.
    example
    Common-Admission-Test-CAT,Common-Admission-Test-CAT-2018
    if do not want to change press enter
    
---
Enter the topics you wanted to scrap from quora. Enter the topics without removing hyphen as it is taken from quora.  
Two topics should be seperated with ','. Examples we have two topics from quora.  
1 Common-Admission-Test-CAT  
2 Common-Admission-Test-CAT-2018  
Thus our input will be:  Common-Admission-Test-CAT, Common-Admission-Test-CAT-2018  
After this something like this will print on console.

----
    Enter the file name in which data will be stored. examples
    quora_question_answer_cat.csv
    press enter for default value
    
---
Simply enter the file name (csv file name) in which you want to save your data. example: quora_question_answer_cat.csv  
After this something like this will print.

---
    Enter the central topic name.
    example
    CAT
    press enter for default value.

------
Now enter the central topic. Like all the topics I entered are related to Cat exam. So 'CAT' will be input.  
After this press enter to continue. Your scrapper will start scrapping.

