# smart-structures-support

> An iOS application supporting the process of modeling the materials behaviour. v1.0

---

### Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [Usage](#usage)
- [Author Info](#author-info)

---

### Description

This app enables selecting parameters for rheological or constitutive models, in particular the modified Bouc-Wen model.  The created mathematical model support analysis of characteristics the force as a function of displacement based on Charts library. User of the presented application has the ability to influence the course of characteristic by changing the selected coefficients of the model in real time.

Data for the program is fetched from private user spreadsheets placed in Google Drive using Google Sheets API. 
Protocol OAuth 2.0 allows to request the user acceptance for application data access. To be precise using this protocol app can get an access to Google signed up profile and generate token that has unique identificator which is further use for authentication and access to private files. Login was created using the Google Sign-In SDK

### Technologies

Written in Swift UIKit in programmatically approach with usage of:
- [Google Sign-In SDK](https://developers.google.com/identity/sign-in/ios/start)
- [Google Sheets API](https://developers.google.com/sheets/api/guides/concepts)
- [Charts by danielghandi](https://github.com/danielgindi/Charts)


### Usage

<!---!![](project-image-url)--->
<!---![GoogleSheets sheet](https://j.gifs.com/QnozZG.gif)--->
<img src="https://j.gifs.com/QnozZG.gif" width="550" height="482"/> 
<div class="row">
  <div class="column">
    <img src="https://j.gifs.com/zvrk6m.gif" width="233" height="481"/>
  </div>
  <div class="column">
    <img src="https://j.gifs.com/vln1Ym.gif" width="233" height="481"/>
  </div>
</div>


#### Code snippets - helpful URLs
```
// To get a list of private files on Google Drive.
let url = "https://www.googleapis.com/drive/v3/files/?access_token=\(token)&q=mimeType='application/vnd.google-apps.spreadsheet'"
// then get id of required file and read from it.
let url = "https://sheets.googleapis.com/v4/spreadsheets/\(sheetId)/values:batchGet/?access_token=\(token)&ranges=\(range)&majorDimension=ROWS"
```


---

#### Author Info

- Github - [@szytambsky](https://github.com/szytambsky)

[Back To The Top](#smart-structures-support)

