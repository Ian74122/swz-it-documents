# Download and upload data
  
Index
- [Download 2 data](#download_2_data)
- [Upload 2 data](#upload_2_data)
  
---
### Download 2 data
1. Save the following website as your favorite in chrome:   
[Dowload Data](https://www.dsdfpay.com/html/admin/index.html?1582709924718 "Dowload Data")
1. Log in the above website  
***IF YOU LOG IN DIFFERENT ACCOUNT, YOU WILL GET DIFFERENT DATA  
IF YOU LOG IN DIFFERENT ACCOUNT, YOU WILL GET DIFFERENT DATA  
IF YOU LOG IN DIFFERENT ACCOUNT, YOU WILL GET DIFFERENT DATA***  
(And you will get totally 2 different account, please be aware of that.)  
1. After you log in, click the `English` button and it will translate in English version.  
![image](https://user-images.githubusercontent.com/62477687/77276620-1b0fdb00-6cf6-11ea-9636-7da96c7284f5.png "Change Language")
1. There is a cell named `PlayerIn` which located in the left list and count down for 8 cells. Click it.
1. You would see a time range for today in upcoming page and it shows like this...  
![image](https://user-images.githubusercontent.com/62477687/77276757-5dd1b300-6cf6-11ea-8a07-1bb9dfb6f2ff.png "Change Time Range")  
Just only change the date you want, and...  
***OTHER STAY THE SAME!  
OTHER STAY THE SAME!  
OTHER STAY THE SAME!***  
For example, xxxx-xx-xx 00:00:00 ~ xxxx-xx-xx 23:59:59  
**(“x” is the one you can adjust)**
1. After set done the date, click `Query`
1. After click `Query`, click `Download` 
1. Look for the excel document(data) you just download in Finder, and change the name of it.  
For example, 20200318 or 20200320-20200322
1. Open the excel document(data), and you will see the 2 rows for date (row N & O)
1. Select both N2 and O2
1. Press command+shift+down (keyboard accelerator), to select all the available date data.
1. Click the `number format above` (it will reveal `Date` in the blank) and click `More Number Format`  
![image](https://user-images.githubusercontent.com/62477687/77277392-c2d9d880-6cf7-11ea-99dc-40a38e462cc7.png)
1. Click `Customs` and then copy **yyyy/mm/dd hh:mm:ss** into type.  
![image](https://user-images.githubusercontent.com/62477687/77277266-7ee6d380-6cf7-11ea-9d45-858a03c55f60.png)
1. Click OK.  
(If it’s not changing the first time, then repeat procedure 10 to 14 again)
1. Insert different function in R2 for different data, and then click somewhere else to get the result.  
**HJC account: “=LEN(A2)<>8”  
BJC account: “=LEN(A2)<>7”**  
1. Move your cursor back to the right bottom of R2, and the cursor should be a black cross.
1. When your cursor turned into a black cross, double click it.  
(It will copy the function to all columns down below)
1. Click back in cell R1  
![image](https://user-images.githubusercontent.com/62477687/77277444-e43ac480-6cf7-11ea-8be7-58a6952502c6.png)
![image](https://user-images.githubusercontent.com/62477687/77277455-ec92ff80-6cf7-11ea-82c2-8f7148c4c8ac.png)
1. Click `Sort & Filter` and then click `Filter`.
1. Click R1 for checking if there is category TRUE
   1. If TRUE exists, then only select TRUE, and copy all the content into the excel named `Odd data`.  
   (The one you download in the begining)
   1. If there is no category TRUE, then that represent normal.
1. Click back to `Sort & Filter` and then click `Filter` again (it will make filter disappear)  
![image](https://user-images.githubusercontent.com/62477687/77277725-8c508d80-6cf8-11ea-98d6-4d29403becd2.png)
1. Delete row R.
1. Save the data.
1. Send your supervisor the data which you have already finished all the procedures above.
1. If your supervisor say there’s no problem, you can do the next following step.  
  
---
### Upload 2 data
1. Save the following website as your favorite in chrome:   
[Upload Data](http://financial-analysis.rubyxgem.com/?locale=en "Upload Data")
1. Click it and it will show you the website like this  
![image](https://user-images.githubusercontent.com/62477687/77278103-71324d80-6cf9-11ea-9d2d-de881a271e38.png)
1. Click `Choose File` and select the excel you just sent to your supervisor
1. Click `Upload`
1. When it turns out the result, check if its number is as same as your excel data number.
1. Repeat all the procedures above, until you upload all 2 different data.
1. Final, if the **HJC data number is less than 1300 or BJC data number is less than 600, have to let your supervisor know!**






