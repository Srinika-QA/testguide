# Inject Keys : 

Tag 1 : <inject key="AzureAdUserEmail">

Tag 2 : <inject key="AzureAdUserEmail" />

Tag 3 : <inject key="AzureAdUserEmail"></inject>

// All the above tags have same output even though there is a change in syntax 

# Inject Keys With Static Values :

<inject key="testKey2" value="StaticValue2" key="testkay1"  value="StaticValue1" />   [//Output should include value+value with copy icon ]

<inject key="AzureAdUserPassword" value="StaticValue3" key="testkay2"  value="StaticValue2" />   (//Output should include azure password+value+key+value with copy icon )

<inject key="AzureAdUserPassword" value="StaticValue2" key="AzureAdUserEmail" value="StaticValue1" enableCopy="false" /> // Output should include azure password+value+azure email+value without copy icon 

**Inject Keys with and without Copy icons :**

   -> For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="true" />.

   -> For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="true" />.

   -> For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="false" />.

   -> For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="false" />.


**Image Syntax Test :**

1. Image syntax for local repository image : 

  - ![Local Image](Images/image%20(88).png)

2. Image syntax for Web URL : 
         
  -> https://www.slajobs.com/wp-content/uploads/2022/12/azure-training-in-chennai.png

3. TIFF Image test : 

    https://spektrasystems-my.sharepoint.com/:i:/p/murali_ponna/EXk4wDWqi9JJvh3gQfgSvtQB7sJ_aPInAZRCcYmPmLRT5g?e=NSwG0j

4. PNG format image test :

  \ https://people.math.sc.edu/Burkardt/data/tif/board.png
  | https://people.math.sc.edu/Burkardt/data/tif/board.png

**Hyperlink Syntax : **

1. Direct web URL :

Passing a URL directly in the Lab guide. Ex : https://www.youtube.com/watch?v=TYtcpdMelYA 

2. Adding a URL within a word. As if when you click on the underlined word, it navigates to the link associated to it

[Click Here to check](https://www.notion.so/wizio/f9e7ee31bac441368956856e5a2d0221?v=c19b50b29381493ebda0e48051552337)      

# Emojis 
🙏


