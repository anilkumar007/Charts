# Charts
1) create a project from termainal as ionic start Charts blank <br/>
2)cd Charts project <br/>
3)Add the required platform in terminal as ionic add platform **** <br/>
4)Add the ng-cordova.min.js file above the cordova.ja file in our project <br/>
5)Insert that 'ngCordova' dependency in app.js file <br/>
6)Add the library to display the charts, In cmd prompt type the cmd as bower install angular-chart.js --save <br/>
  NOTE:<br/>
  In app.js don't forget to include the module as 'chart.js'<br/>
7)In Index.html you have to include 3 file's to work with your chart's the file path will be like this  <br/>
 *****************************************************************************<br/>
   <link rel="stylesheet" href="lib/angular-chart.js/dist/angular-chart.css"><br/>
    <script src="lib/Chart.js/Chart.min.js"></script><br/>
    <script src="lib/angular-chart.js/dist/angular-chart.min.js"></script><br/>
  ***************************************************************************************<br/>
8)In app.js I wrote an Controller to display the status of charts and it's functionality please have a look <br/>
9)Please update your cordova platform if the above plugin doesn't work
