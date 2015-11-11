![OFBiz](http://ofbiz.apache.org/images/logo.png "Apache OFBiz")&nbsp;![BPost](http://www.bpost.be/_images/logo_bpost.jpg "BPost")

#obpost
3rd party Shipment Provider Integration Solution for BPost&trade; as a separate and optional hot-deploy component for an Apache OFBiz&trade; implementation. This component enables you to configure your BPost ShippingManager integration and provides templates for inclusion in your OFBiz web store.

BPost Shipping Manager is a service offered by BPost, allowing your customer to choose their preferred delivery method when ordering in your webshop. The following delivery methods are currently supported:
* Receive your parcel at home or at the office.
* Over 1.250 locations nearby home or the office.
* Pick-up your parcel whenever you want, thanks to the 24/7 service of bpost.

When activated, this module also allows you to fully integrate the bpost administration into your webshop. This means that orders are automatically added to the BPost portal.

Furthermore, if enabled, it is possible to generate your labels and tracking codes directly from within your OFBiz implementation.

No more hassle and 100% transparent!
For more information on BPost ShippingManager, visit [their site, here](http://www.bpost.be/site/nl/business/send_post/parcels/shippingmanager.html#).
For more information on Apache OFBiz&trade;, visit [their site, here](http://ofbiz.apache.org).

##Development
Just put the following in the svn:externals properties of the hot-deploy folder of your OFBiz implementation for a checkout:

obpost         https://github.com/ORRTIZ/obpost/trunk

After having updated the hot-deploy folder (to execute the checkout from the repository), you'll need to build OFBiz again (./ant build) and load the seed, seed-initial and  - optionally- demo datasets.

