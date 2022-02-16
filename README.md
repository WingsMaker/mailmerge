# mailmerge ( using your own gmail engine )
To perform simple mailmerge using googlesheet with macro (written in google app script).

Example:

![image](https://user-images.githubusercontent.com/32192638/154191271-8fcd843f-9023-4e8b-849e-10d14a1f634a.png)





Steps
[1] Creates your google sheet with 2 worksheets like this

Sheet1
![image](https://user-images.githubusercontent.com/32192638/154187943-ca819511-4098-4194-89f5-cb6c462c27dc.png)



Sheet2
![image](https://user-images.githubusercontent.com/32192638/154188041-c5501599-6cfc-4e10-ad48-a6fddca1e326.png)




[2] Create a macro named mailmerge

Click "Extensions => Macros => Record macro"
![image](https://user-images.githubusercontent.com/32192638/154188793-b95ac6ac-021c-40c9-83c2-d551f79a1028.png)



![image](https://user-images.githubusercontent.com/32192638/154188872-0a264675-f2fc-4739-af8f-e98f20ccf7a3.png)




Name change to mailmerge and click "Save"

![image](https://user-images.githubusercontent.com/32192638/154189042-603fc942-6ad3-4ff2-b2ee-1001d75150c7.png)




Click "Edit Script"

![image](https://user-images.githubusercontent.com/32192638/154189106-5a670feb-e2c2-4d1a-9286-5ce84c9cf6e4.png)





[3] Copy and paste the source code 

Find the google app script editor and empty the scripts area

![image](https://user-images.githubusercontent.com/32192638/154189961-82b9022a-1a8b-400c-bb5e-3074fed3d18c.png)





Find my source code form this github link 
https://raw.githubusercontent.com/WingsMaker/mailmerge/main/mailmerge_gs.txt


and paste the 52 lines of code into the app script editor. 

![image](https://user-images.githubusercontent.com/32192638/154190064-d0341089-7cab-4443-aad3-a033b37e88d9.png)






Click the Save icon ( yellow ) and this editor app. 

Go back to the google sheet. Find the "mailmerge" macro function that you can created.

![image](https://user-images.githubusercontent.com/32192638/154190325-a4af0fca-29b1-49e8-b642-7533254d4bfd.png)






All you need to click and this mailmerge macro.


The test results shows

![image](https://user-images.githubusercontent.com/32192638/154190578-0d9ed623-cfb1-42c8-ab80-ebc17717d6ab.png)





Note that you are sending from your gmail address, you can't use non-gmail to perform mail merge.

Lazy to hands-on ? make a copy from below
https://docs.google.com/spreadsheets/d/17ujNIUMpGWJlrUR9vkc5YGnU8ufKNwr6puz09mmLnlo/edit?usp=sharing

