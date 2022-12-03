# Teamscalade [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](../LICENSE)


## Teamscalade is composed of 4 different components:
- A mobile application for users.
- A CMS for our clients to manage their climbing gyms.
- A back-end to link the mobile app and the CMS with our database and algorithm.
- An algorithm to autodetect climbing routes.

<br/>

## Organisation:
- Team leader:
- Mobile application developer:
- CMS developer:
- Back-end developers: @brihoumb, @noe-tiger
- Data scientist: @noe-tiger
- System administrator: @brihoumb
- Database administrator: @brihoumb

<br/>

## Workflow:
User  
├── Login & register  
└── Mobile application  
&nbsp;&nbsp;&nbsp;&nbsp;├── Home  
&nbsp;&nbsp;&nbsp;&nbsp;├── Search  
&nbsp;&nbsp;&nbsp;&nbsp;├── Statistics  
&nbsp;&nbsp;&nbsp;&nbsp;├── Community & events  
&nbsp;&nbsp;&nbsp;&nbsp;├── QR code scanner  
&nbsp;&nbsp;&nbsp;&nbsp;├── Videos  
&nbsp;&nbsp;&nbsp;&nbsp;└── Climbing gym dashboard  
<br/>
Client  
├── Login & register  
└── CMS  
&nbsp;&nbsp;&nbsp;&nbsp;├── Creation of routes  
&nbsp;&nbsp;&nbsp;&nbsp;├── Deletion of routes  
&nbsp;&nbsp;&nbsp;&nbsp;├── Managment of statistics  
&nbsp;&nbsp;&nbsp;&nbsp;├── Managment of community  
&nbsp;&nbsp;&nbsp;&nbsp;├── Highlights for routes openers  
&nbsp;&nbsp;&nbsp;&nbsp;├── Highlights for workers route deletion/creation  
&nbsp;&nbsp;&nbsp;&nbsp;└── Internal communication system  
<br/>
Admin  
├── Back-end  
│&nbsp;&nbsp;&nbsp;├── Internal communication with the algorithm  
│&nbsp;&nbsp;&nbsp;├── Communication with the database via routes  
│&nbsp;&nbsp;&nbsp;├── Communication with the video server  
│&nbsp;&nbsp;&nbsp;└── Commuication with the image server  
├── Algorithm  
│&nbsp;&nbsp;&nbsp;└── Automatic detection of routes  
└── Database  
&nbsp;&nbsp;&nbsp;&nbsp;└── Storage of the datas