FastRequire
==================

SPL class loader is slow! Now you can skip the SPL functions to load your minimal class requirements directly.

You can also know your minimal class dependency to reduce the overhead of your application by using `fast_require`.

Usage
---------

    fast_require app.php > loader.php
    php loader.php

