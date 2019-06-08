## [0.9.3] - 1 Jun 2019.

Fixed issue with delayed call to searchPlace
 
`searchPlace` was being called (sometimes) after the widget has unmounted.  
This could have been due to some delay caused by the debouncer proceeding after
the widget has unmounted

## [0.9.2] - 1 Jun 2019.

Fixed issue where `setState` from http response callbacks was being called
after widget was disposed/unmounted

## [0.9.1] - 1 Jun 2019.

Updated guidelines to include missing configurations

## [0.9.0] - 1 Jun 2019.

Prepared for usage.

## [0.0.2] - 1 Jun 2019.

Fixes to package publication health. Added example.

## [0.0.1] - 1 Jun 2019.

Initial release.