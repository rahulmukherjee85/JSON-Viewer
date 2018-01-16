# JSON-Viewer

Online tool to view ,edit and format JSON Object

It has the flowing feature:

# No Cookie and server side processing : 
Most of the available tool use cookie and server side processing to formate,store,process JSON document. In some project, where we deal with sensitive client data we should not use this type of tools . We use to face a lot of challenges while developing API based projects. I have not used any cookie or server side processing to process the data. Anyone can freely use this tool in any project. Your data will not travel over the network, instead it will process in side the browser on the fly using JavaScript only. You can verify this by using FireFox in built console's network and storage tab.

# Load external JSON file :  
You can load any JSON file from your disk and also the file will not get uploaded into the server. It will get processed only in browser using JavaScript.

# Save loaded JSON file into disk : 
You can download/save the JSON as file into your disk by one click only.

# Different view in a single Editor : 
You can view your data in different mode in a single editor window by clicking the navigation or changing the mode drop-down menu. In the same editor window you can alter the object manually in code editor mode or using  object editor in Tree view.

Please note : It is developed using the flowing open source frameworks:
[AJV](https://github.com/epoberezkin/ajv),
[Bootstrap](http://getbootstrap.com/),
[jQuery](http://jquery.com/),
[Editor](https://github.com/josdejong/jsoneditor/),
[Ace](https://github.com/ajaxorg/ace)

