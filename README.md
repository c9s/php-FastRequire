FastRequire
==================

SPL class loader is slow! Now you can load your minimal class requirements directly, and skip SPL functions to load these class files!

You can also know your minimal class dependencies to reduce the overhead of your application by using `fast_require`.

Usage
---------

    fast_require app.php > loader.php
    php loader.php

