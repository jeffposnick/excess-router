0.9.3
==================
* bugfix: routeparameters reflection

0.9.2
==================
* bugfix: _setRouteFromLocation did not update _destinationPath
* bugfix: excess-route: setting parameter to undefined should not cause navigation

0.9.1
==================
* bugfix: activationModifiers were swapped in excess-route

0.9.0
==================

* Add ability to activate multiple routes at once
  This allows for more 'natural' solutions to common routing problems:

    <excess-route route="/:topmenu">
    <excess-route route="/users">
    <excess-route route="/users/:userId">

* excess-route:
  - rip out old nested route code
  - add activationModifiers property
