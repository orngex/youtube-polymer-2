# Polymer Application: Use App Constants

Github: https://github.com/orngex/youtube-polymer-2/tree/app-constant

May people keep asking over the web how to use app constants in a Polymer web Application.

You can very easily use app constants in a polymer web app by using the iron-meta query element in the polymer application. All you have to do is to first import the iron-meta query in the elements.html file and use the iron-meta query element with attributes key and value to create a constant element as shown in the polymer video tutorial and then you can use those constants throughtout the Polymer App.

   <iron-meta key="APP_NAME" value="OrngeX Polymer App"></iron-meta>

###    var appConstant = new Polymer.IronMetaQuery({key:'APP_NAME'}).value;

You can imagine how a thing like this can greatly simplify your app development especially if you have to port if to different development platforms such as for android app development, ios applications and web app.
