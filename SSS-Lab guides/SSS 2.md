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




<style><style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&display=swap');
aside {
   border-left: 4px solid #509128;
   padding-left: 12px;
   font-weight: 300;
   color: #434343;
   text-indent: -2px;
   align-items: center;
   margin-top: 6px;
   margin-bottom: 12px;
   line-height: 22px;
   font-size: 16px;
   letter-spacing: 0px;
}
aside::before {
   content: "💡 Tip";
   font-style: normal;
   margin-left: 2px;
   color: #509128;
   font-weight: 600;
   font-size: 14px;
   display: block;
}
}
details > summary{
    font-weight: 700;
    font-size: 110%;
    color: #0254EC;
    padding: 24px 0px 24px 0px;
}
teams-button[aria-label="change vm 100% selected"] {
display: none;
}
</style>

test
