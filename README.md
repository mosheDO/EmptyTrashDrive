# Empty entire trash from google drive


The Empty trash in google drive doesnt work for all the trash it delete only for the curretn window,
[HERE](https://support.google.com/drive/thread/25660013?hl=en)
[They just locked the question without answring](https://support.google.com/drive/thread/22907755?hl=en)
The trash folder is taking space from your storage plan

So I create this script that request via API endpoint for empting the trash, if we run this script multiple times (like 100) 
and wait for a night the google drive will sync and in the mornining u will see that the trash is  empty


U will need a token for the requst and u can generate that [oauthplayground](https://developers.google.com/oauthplayground/)


and run from terminal or cmd (need curl instslled) the file with a loop
