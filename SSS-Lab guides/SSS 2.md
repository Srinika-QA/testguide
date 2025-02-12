Inject Keys : 

Tag 1 : <inject key="AzureAdUserEmail">

Tag 2 : <inject key="AzureAdUserEmail" />

Tag 3 : <inject key="AzureAdUserEmail"></inject>

Inject Keys With Static Values : <br>
<inject key="testKey2" value="StaticValue2" key="testkay1"  value="StaticValue1" /> <br>
         //Output should include value+value with copy icon <br>
<inject key="AzureAdUserPassword" value="StaticValue3" key="testkay2"  value="StaticValue2" /> <br>
        //Output should include azure password+value+key+value with copy icon <br>
<inject key="AzureAdUserPassword" value="StaticValue2" key="AzureAdUserEmail" value="StaticValue1" enableCopy="false" /> <br>
        //Output should include azure password+value+azure email+value without copy icon <br>
        
Image Syntax Test :

![Image Title](Images/image%20(88).png)

![Image Title](image%20(88).png)




- For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="true" />.

- For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="true" />.
