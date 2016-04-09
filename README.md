Welcome to weather.

This produces a simple listing of several hours of forecast.

Feel free to give me feedback and/or fork and pull requests and/or report
issues.

If you find this is useful and you wish to donate, I accept donations:

BTC: <a href="bitcoin:12NpeRCdSrYrHPha7eHqKsJHvi7d6RHKod">12NpeRCdSrYrHPha7eHqKsJHvi7d6RHKod</a>

DCR: <a href="decred:DsUGaQSZFcjzbbhBrKBQdm8mTyAjPQa3ZTJ">DsUGaQSZFcjzbbhBrKBQdm8mTyAjPQa3ZTJ</a>


Random blathering follows...

I note there is an App::Wu available from CPAN, but I intend to take this
in a different direction.

This was created because my son, Charlie, has been asking about weather info
so frequently, he should be able to go look it up himself.

This presents a simple output initially designed by myself, and I hope with
feedback and/or guidance from Charlie, will present more info and/or different
bits of info.

Note this requires a key.  Unlike many other consumers of the Wunderground api,
I check for a conf file to contain the key.  In UNIX and perhaps other
opearting systems, the environment is visible to other users.

A sample output is as follows:

<code>
Date         Time      F  Rain%   Conditions          
Apr  8, 2016 23:00   60       0  Clear
Apr  9, 2016 00:00   58       0  Clear
Apr  9, 2016 01:00   57       0  Clear
Apr  9, 2016 02:00   57       0  Clear, Mostly Clear
Apr  9, 2016 03:00   56       0  Clear, Mostly Clear
Apr  9, 2016 04:00   55       0  Clear, Mostly Clear
Apr  9, 2016 05:00   54       0  Partly Cloudy
Apr  9, 2016 06:00   53       0  Partly Cloudy
Apr  9, 2016 07:00   51       0  Partly Cloudy
Apr  9, 2016 08:00   51       0  Partly Cloudy
Apr  9, 2016 09:00   58       0  Partly Cloudy
Apr  9, 2016 10:00   64       0  Partly Cloudy
Apr  9, 2016 11:00   69       0  Partly Cloudy
Apr  9, 2016 12:00   72       0  Partly Cloudy
Apr  9, 2016 13:00   72       0  Partly Cloudy, Cloudy/Wind
Apr  9, 2016 14:00   72       0  Partly Cloudy, Mostly Cloudy/Wind
Apr  9, 2016 15:00   73      15  Partly Cloudy, Cloudy/Wind
Apr  9, 2016 16:00   74      15  Partly Cloudy, Cloudy/Wind
Apr  9, 2016 17:00   73      15  Partly Cloudy, Cloudy/Wind
Apr  9, 2016 18:00   70      14  Partly Cloudy, Cloudy/Wind
Apr  9, 2016 19:00   67      14  Partly Cloudy, Cloudy/Wind
Apr  9, 2016 20:00   65       5  Mostly Cloudy
Apr  9, 2016 21:00   63       5  Partly Cloudy, Partly Cloudy/Wind
Apr  9, 2016 22:00   62      15  Partly Cloudy, Mostly Cloudy/Wind
Apr  9, 2016 23:00   61      15  Partly Cloudy, Mostly Cloudy/Wind
Apr 10, 2016 00:00   60      15  Partly Cloudy, Mostly Cloudy/Wind
Apr 10, 2016 01:00   60      15  Partly Cloudy, Mostly Cloudy/Wind
Apr 10, 2016 02:00   60      24  Partly Cloudy, Partly Cloudy/Wind
Apr 10, 2016 03:00   59      24  Partly Cloudy, Partly Cloudy/Wind
Apr 10, 2016 04:00   59      24  Partly Cloudy, Clear/Wind
Apr 10, 2016 05:00   59      18  Partly Cloudy, Clear/Wind
Apr 10, 2016 06:00   60      18  Partly Cloudy, Mostly Clear/Wind
Apr 10, 2016 07:00   60      19  Partly Cloudy, Partly Cloudy/Wind
Apr 10, 2016 08:00   61       3  Partly Cloudy, Partly Cloudy/Wind
Apr 10, 2016 09:00   64       3  Partly Cloudy, Partly Cloudy/Wind
Apr 10, 2016 10:00   68       2  Partly Cloudy, Partly Cloudy/Wind
</code>
