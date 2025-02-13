# Paragraph Test : 

Once you have successfully registered using one of the available methods, you will be redirected to the Launch Lab page. Please click on the **LAUNCH LAB** button to access your Lab environment. Do note, your lab timer will start as soon as you launch the lab. So, if you plan to launch the lab at a later time, you can bookmark this URL and launch it later.
To login to Azure, navigate to **Environment** tab, copy cloud user name **<inject key="AzureAdUserEmail"></inject>** and password **<inject key="AzureAdUserPassword"></inject>**

>Azure Email <inject key="AzureAdUserEmail">

# Inject Keys : 

Option 1 : <inject key="AzureAdUserEmail">

Option 2 : <inject key="AzureAdUserEmail" />

Option 3 : <inject key="AzureAdUserEmail"></inject>

Option 4 : <inject key="DeploymentID" enableCopy="false" />** 

Option 5 : AzureAdUserEmail : <inject key="AzureAdUserEmail"></inject>

Option 6 : AzureAdUserPassword : <inject key="AzureAdUserPassword" style="color:blue"></inject>

Option 7 : Deployment ID : <inject key="Deployment ID"></inject>

Option 8 : Labvm Admin Username : <inject key="Labvm Admin Username"></inject>

Option 9 : Labvm Admin Password : <inject key="Labvm Admin Password"></inject>

Option 10 : Labvm DNS Name : <inject key="Labvm DNS Name"></inject>

# Inject Keys with Default options : 

<inject key="AzureAdUserEmail"  defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<inject key="**AzureAdUserEmail**" defaultvalue="Defaultemail@example.com">   // output shows Key value since its valid

<inject key="Sample" defaultvalue="Defaultemail@example.com">     // output shows default value since key is invalid

<inject key="AzureAdUserEmail" defaultvalue="">     // output shows Key value since its valid  

<inject key="" defaultvalue="Defaultemail@example.com">      // output shows default value since key is blank

<inject key="" defaultvalue="">   // no output as Key and default values are blank 


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
  
  ![Local JPEG Format](Images/Test%20Image%20for%20JPEG.jpg)   // JPEG Format //

  ![Local WEBP Format](Images/Test%20WEBP%20format.webp)   // WEBP Format //

  ![Local TIFF Format](Images/QA%20TIFF%20Img.tiff)   // TIFF Format //

2. Image syntax for Web URL : 
         
<img src="https://spektrasystems.com/wp-content/uploads/2021/02/20748047_909553532535214_5011335614256117284_o-1024x768-2-600x600.jpg" width = "300" height ="300">


3. Drag and Drop Image :

![image](https://github.com/user-attachments/assets/d2fa89dd-3c39-4c01-aabc-6a3987a02d5d)   //Copy pasted a screen from Snagit 

# Hyperlink Syntax :


1. Direct web URL :

Passing a URL directly in the Lab guide. **Ex** : https://www.youtube.com/watch?v=TYtcpdMelYA 

2. Adding a URL within a word. As if when you click on the underlined word, it navigates to the link associated to it

[Click Here to check](https://www.notion.so/wizio/f9e7ee31bac441368956856e5a2d0221?v=c19b50b29381493ebda0e48051552337)   

3. Web link within a code block :

```
https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.istockphoto.com%2Fphotos%2Fnature&psig=AOvVaw06TzaQHiuxybkRlLJLvfxo&ust=1739343936597000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCMiox56Hu4sDFQAAAAAdAAAAABAE
```

# Code block syntax :

1. Any sentence starts with space or Tab key shows as code block

         Example for code block using space or Tab key//
   
2. Code block using Backticks

```
public class PrimeExample
{    
 public static void main(String args[])
{    
  int i,m=0,flag=0;      
  int n=3;//it is the number to be checked    
  m=n/2;      
  if(n==0||n==1){  
   System.out.println(n+" is not prime number");      
  }else{  
   for(i=2;i<=m;i++){      
    if(n%i==0){      
     System.out.println(n+" is not prime number");      
     flag=1;      
     break;      
    }      
   }      
   if(flag==0)  { System.out.println(n+" is prime number"); }  
  }//end of else  
}    
}   
```
3. Code block without copy icon

```
<inject key="DeploymentID" enableCopy="false" />** 

```

4. code block with coloured content
   ```
   AzureAdUserPassword : <inject key="AzureAdUserPassword" style="color:blue"></inject>
   ```

5. odl_user_38925@nikunjgadhesariya.onmicrosoft.com</inject>
	wrhg06EGZ*8d</inject>
   Dep ID:</inject>


# Color Content :

<span style="color: green"> ->Navigate to https://admin.cloudlabs.ai/ and Login to the Admin Centre or follow this detailed guide [click here](https://docs.cloudlabs.ai/Instructor/GettingStarted) </span>

<span style="color: Blue"> ->Select your Tenant </span>

<span style="color: Yellow"> ->Click on **On Demand** Labs from the left navigation pane. </span>

<span style="color: Pink"> ->Click on **+ ADD ON DEMAND LAB** and fill up the required information. </span>


# Emojis : 
🙏

👍✌️🎶🪶🪽🚫⛔🔇❓❗⬇️⬆️🔽➡️⬅️


# GIF Trail : 

![HappyMondayGIF](https://github.com/user-attachments/assets/da4d8630-48cf-43a2-a7c3-aa33b0c7edd5)

// Right click, Open desired GIF, drag and drop here 

