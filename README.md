Project My Cafe

Order subsystem.
The order subsystem is clearly not very complicated. The user goes to the ordering
page, selects the products they want, and then places the order. Users can add drinks
to their order, remove them, and change the quantity desired for each. The order
subsystem can also place the order, triggering the payment process; after that, it will
communicate the order to the shop.

setup:
  - git clone git@github.com:viktordanch/mycafe.git
  - cd mycafe
  - npm install

run tests:
  - npm test

