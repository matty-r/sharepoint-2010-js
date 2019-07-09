# sharepoint-2010-js
A SharePoint 2010 JavaScript repository with fixes

## sp2010-ie11-fixings.js
This file fixes SharePoint 2010 javascript compatibility errors wich occurs in IE >= 11 browsers.

### Fixed errors
* Datepicker shows **true** after closing
![alt text](https://raw.githubusercontent.com/Jonas-buriti/sharepoint-2010-js/master/dt-error.png)

* Datepicker.js "Document.frames function expected" error:
![alt text](https://raw.githubusercontent.com/Jonas-buriti/sharepoint-2010-js/master/function-error.png)

* sp.ui.rte.js "Unable to get property 'parentElement' of undefined or null reference expected" error:
![alt text](https://raw.githubusercontent.com/Jonas-buriti/sharepoint-2010-js/master/rte-error.png)

* sp.ui.rte.js "Unable to get property 'classname' of undefined or null reference File: sp.ui.rte.js" error
No screenshot atm


## Usage
Link the .js in your page **or** masterpage **or** page layout
```  
<SharePoint:ScriptLink Name="~SiteCollection/style library/js/sp2010-ie11-fixings.js" runat="server"></SharePoint:ScriptLink >
```
