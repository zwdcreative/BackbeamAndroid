Changelog
=========

**Version 0.12.1 - Feb 21, 2014**

`JoinResult` now is serializable. This prevents the problem of serializating the user session when `Backbeam.login()` is used with a join BQL.

**Version 0.12.0 - Feb 20, 2014**

Renamed social signup methods. `googlePlusLogin` is now `googlePlusSignup`, `facebookLogin` is now `facebookSignup` and `twitterLogin` is now `twitterSignup`. In general changed `login` to `signup`.

Additionally new authentication methods have been added: `linkedInSignup` and `gitHubSignup`