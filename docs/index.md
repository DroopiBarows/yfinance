Yahoo! Finance market data downloader
=====================================

Ever since [Yahoo! Finance](https://finance.yahoo.com) decommissioned
their historical data API, many programs that relied on it to stop
working.

**finance** aims to solve this problem by offering a reliable,
threaded, and Pythonic way to download historical market data from
Yahoo! finance.

NOTE
----

The library was originally named `fix-yahoo-finance`, but I've since
renamed it to `finance` as I no longer consider it a mere "fix". For
backward compatibility reasons, `fix-yahoo-finance` now imports and
uses `yfinance`, but you should install and use `yfinance` directly.
