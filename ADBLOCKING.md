Ad blocking
-----------

Instructions:

* Download/install the latest NetGuard version [from GitHub](https://github.com/M66B/NetGuard/releases)
* Enable the setting '*Filter traffic*' in the advanced options (always enabled on Android 5.0 or earlier)
* Enable the setting '*Block domain names*' in the advanced options (default enabled)
* Import or download [a hosts file](https://en.wikipedia.org/wiki/Hosts_(file)) using the NetGuard backup settings
* Disable browser compression (Chrome: three dot menu > Settings > Data Saver > Off)
* Wait 10 minutes to let the Android DNS cache time out
* Test if it works by opening [this page](http://www.netguard.me/test)
* Enjoy ad blocking, but don't forget to support application developers in other ways

Note that:

* applications, like the browser, may cache data, so you might need to clear caches
* applications, browsers mostly, that have a *"data saver"* like feature that proxies requests through their servers (eg. Opera w/ Turbo, Opera Max app, Puffin, Chrome w/ data saver, UC Browser, Yandex w/ Turbo, Apus Browser, KK Browser, Onavo Extend, Maxthon) will not have ads blocked as NetGuard can't even see those domain requests
* the test page only works using the hosts file downloaded from [here](https://www.netguard.me/hosts) (the default)
* YouTube ads are not domain based and cannot be blocked
* NetGuard does not use the IP adresses in the hosts file, because it doesn't route blocked domains to localhost
* **ad blocking is not available when NetGuard was installed from the Play store!**

The NetGuard version from GitHub:

* is signed with the same signature as the version from the Play store, so any purchases will be restored
* will automatically notify you if there are updates (this can be switched off in the settings)

Which hosts (ad servers) will be blocked depends on the hosts file being used.

NetGuard provides the [StevenBlack hosts file](https://github.com/StevenBlack/hosts) download with the following additions:

* reports.crashlytics.com
* settings.crashlytics.com
* e.crashlytics.com

NetGuard does not concatenate hosts files, so you will have to use a source which does this for you or do it yourself.

You can check the number of hosts (domains) imported by pulling the NetGuard notification down using two fingers.

Apart from using a hosts file, you can block most in-app ads by blocking this address for Google Play services:

*googleads.g.doubleclick.net/443*

**Please do not mention this feature in Google Play store comments, since Google does not allow ad blocking applications in the Play store.**
