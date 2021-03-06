
1.4.2 / 2017-04-13
==================

  * Send `Order Completed` instead of `Placed Order` for event name if you set new option to use Segment Ecommerce Spec 

1.4.1 / 2017-04-12
==================

  * Also remove `id` for enforce email option introduced in 1.4.0 

1.4.0 / 2017-04-05
==================

  * Add new option to only send $email and not $id for dupe reasons with Klaviyo's API

1.3.0 / 2017-01-31
==================

  * Standardize integration (linting, Docker configuration, circle.yml, upgrade
segmentio-integration version, upgrade integration-worker version, etc.)

1.2.1 / 2016-12-08
==================

  * Fix a bug that around properties not being updated for user profiles 

1.2.0 / 2016-11-15
==================

  * Fix List API duplicate profile issue
  * Falling back on anonymousId now gated behind an option
  * Improve logic to use less API calls to Klaviyo per Segment message

1.1.2 / 2016-10-25
==================

  * send userId as $id in listData object for Add to Lists endpoint

1.1.1 / 2016-10-18
==================

  * Ensure unique $event_id for auto-generated  ordered product events

1.1.0 / 2016-09-06
==================

  * support ecom spec v2

1.0.15 / 2016-08-17
===================

  * update ecommerce spec syntax to v2

1.0.14 / 2016-05-24
===================

  * Merge pull request #13 from segment-integrations/add-sku
  * Added SKU for "Ordered Product" event.

1.0.13 / 2016-05-16
===================

  * add back support for looking up product and image urls ;

1.0.12 / 2016-05-13
===================

  * remove look up for product and image urls
  * let custom properties pass

1.0.11 / 2016-04-01
===================

  * add ui default listId support

1.0.10 / 2016-03-22
===================

  * add support for list api

1.0.9 / 2015-09-02
==================

  * map $event_id special prop in conventional track calls

1.0.8 / 2015-08-27
==================

  * Map value to special key $value

1.0.7 / 2015-08-05
==================

  * add support for custom ecommerce

1.0.6 / 2015-06-25
==================

  * deps: bump integration proto
  * Update circle template


1.0.5 / 2014-12-08
==================

 * bump segmentio-integration

1.0.4 / 2014-12-02
==================

 * bump integration proto

1.0.3 / 2014-12-02
==================

 * remove .retries()
 * fix dev deps
 * bump dev deps

1.0.2 / 2014-12-02
==================

 * bump segmentio-integration

1.0.1 / 2014-11-21
==================

 * Bumping segmentio-integration
 * fix build status badge

1.0.0 / 2014-11-14
==================

  * Initial release
