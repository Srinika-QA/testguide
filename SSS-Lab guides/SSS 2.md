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



- For **Username**, enter <inject key="AzureAdUserEmail" enableCopy="true" />.

- For **Password**, enter <inject key="AzureAdUserPassword" enableCopy="true" />.


Image Syntax Test :

![Image Title](Images/image%20(88).png)



# Feedback

As this is a new concept, we are looking for feedback. Anything you think can be improved please let us know on [Notion](https://www.notion.so/wizio/f9e7ee31bac441368956856e5a2d0221?v=c19b50b29381493ebda0e48051552337). 🙏



In the **AWS** console choose **S3** and ensure you are in the **us-east-1** region. https://us-east-1.console.aws.amazon.com/s3/home?region=us-east-1#
