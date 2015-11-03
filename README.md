![OFBiz](http://ofbiz.apache.org/images/logo.png "Apache OFBiz")&nbsp;![BPost](http://www.bpost.be/_images/logo_bpost.jpg "BPost")

#obpost
3rd party Shipment Provider Integration Solution for BPost&trade; as a separate and optional hot-deploy component. This component enables you to configure your BPost ShippingManager integration and provides templates for inclusion in your OFBiz&trade; web store.

For more information on BPost ShippingManager, visit [their site, here](http://www.bpost.be/site/nl/business/send_post/parcels/shippingmanager.html#).

##Development
Just put the following in the svn:externals properties of the hot-deploy folder of your OFBiz implementation for a checkout:

obpost         https://github.com/ORRTIZ/obpost/trunk

After having updated the hot-deploy folder (to execute the checkout from the repository), you'll need to build OFBiz again (./ant build) and load the seed, seed-initial and  - optionally- demo datasets.

