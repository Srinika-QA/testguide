# Inject Keys : 

Tag 1 : <inject key="AzureAdUserEmail">

Tag 2 : <inject key="AzureAdUserEmail" />

Tag 3 : <inject key="AzureAdUserEmail"></inject>

// All the above tags have same output even though there is a change in syntax 

# Inject Keys With Static Values :

<inject key="testKey2" value="StaticValue2" key="testkay1"  value="StaticValue1" />  //Output should include value+value with copy icon

<inject key="AzureAdUserPassword" value="StaticValue3" key="testkay2"  value="StaticValue2" />  //Output should include azure password+value+value with copy icon

<inject key="AzureAdUserPassword" value="StaticValue2" key="AzureAdUserEmail" value="StaticValue1" enableCopy="false" /> // Output should include azure password+value+azure email+value without copy icon 

**Inject Keys with and without Copy icons :**

   -> For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="true" />.

   -> For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="true" />.

   -> For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="false" />.

   -> For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="false" />.


**Image Syntax Test :**

1. Image syntax for local repository image : 

  ![Local Image PNG Test](Images/Test%20Image%20for%20PNG.png)    //PNG Format 

  ![Local JPG Format](Images/Test%20Image%20with%20JPG%20format.jpg)   // JPG Format 
  
  ![Local JPEG Format](Images/Test%20Image%20for%20JPEG.jpg)   // JPEG Format 

  ![Local WEBP Format](Images/Test%20WEBP%20format.webp)   // WEBP Format 

  ![Local TIFF Format](Images/QA%20TIFF%20Img.tiff)   // TIFF Format 

2. Image syntax for Web URL : 
         
 <img src ="https://www.slajobs.com/wp-content/uploads/2022/12/azure-training-in-chennai.png" width ="100", height ="100" >


# Hyperlink Syntax :

1. Direct web URL :

Passing a URL directly in the Lab guide. Ex : https://www.youtube.com/watch?v=TYtcpdMelYA 

2. Adding a URL within a word. As if when you click on the underlined word, it navigates to the link associated to it

[Click Here to check](https://www.notion.so/wizio/f9e7ee31bac441368956856e5a2d0221?v=c19b50b29381493ebda0e48051552337)      

# Emojis : 
🙏

👍✌️🎶🪶🪽🚫⛔🔇❓❗⬇️⬆️🔽➡️⬅️


![image](https://github.com/user-attachments/assets/d2fa89dd-3c39-4c01-aabc-6a3987a02d5d)   //Copy pasted a screen from Snagit 

# GIF Trail : 

![HappyMondayGIF](https://github.com/user-attachments/assets/da4d8630-48cf-43a2-a7c3-aa33b0c7edd5)

file:///C:/Users/SambariSrinika/Downloads/MicrosoftWindows.Client.CBS_cw5n1h2txyewy!InputApp/HappyMondayGIF.gif


