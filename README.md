# redis-php-arm
compiled module for php on arm

Amazon linux 2 support for php is not really consistent, they removed the php-redis package from arm.

Installing directly from pecl on build time was ok in general but we enconuntered some occasion where pecl was unresponsive for a few hours and hour platform bootstap was lock because of this. So as a "temporary" workarround I'm leaving this compiled version of the module here.
