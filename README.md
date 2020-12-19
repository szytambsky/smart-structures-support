# smart-structures-support

> An iOS application supporting the process of modeling the materials behaviour. v1.0

---

### Table of Contents
You're sections headers will be used to reference location of destination.

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

- [Google Sign-In SDK](https://developers.google.com/identity/sign-in/ios/start)
- [Google Sheets API](https://developers.google.com/sheets)
- [Charts by danielghandi](https://github.com/danielgindi/Charts)

---

### Usage

![](project-image-url)

---

#### Author Info

- Github - [@szytambsky](https://github.com/szytambsky)

[Back To The Top](#smart-structures-support)

