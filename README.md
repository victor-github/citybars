citybars
========

CityBars Sencha Touch 2.0.1 app using Sencha Architect
Fixes some of the bugs in the original tutorial, such as missing 'id' in the MainNav view config

You need to add your own Yelp key in app/controllers/Business.js in the function getBusinesses

 getBusinesses: function(location,callback) {
        var store = Ext.data.StoreManager.lookup('BusinessStore'),
            yelpKey = 'add-your-yelp-key-here', 
