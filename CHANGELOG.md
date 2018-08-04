Changelog
===

##### 1.0.1 (2018-08-05)

* Fix `try/with`/`try/finally` bug when throwing from within a plain `async` and catching/finalizing in an `asyncResult`. This bug let exceptions ignore `with` or `finally` clauses and potentially crash the application.

##### 1.0.0 (2018-07-05)

* Support Fable
* Add more helper functions

##### 0.5.1 (2018-03-14)

* Fix `use`/`use!` in conjunction with non-nullable `IDisposable` types

##### 0.5.0 (2018-03-14)

* Breaking: Added assembly-level AutoOpen attribute. Importing the library will automatically import the helper methods as well as the builder instances

##### 0.4.0 (2018-03-08)

* Breaking: Rename `orElse` and `orElseWith` to `defaultValue` and `defaultWith` so the names match the functions with similar signatures in the `Option` module
* Add `Result.ignoreError` and `AsyncResult.ignoreError`

##### 0.3.0 (2018-03-08)

* Add `Result.requireNone`, `AsyncResult.requireTrue`, `AsyncResult.requireFalse`, `AsyncResult.requireSome`, `AsyncResult.requireNone`
* Fix package tags

##### 0.2.0 (2018-03-07)

* Add `setError`
* Fix package tags

##### 0.1.1 (2018-03-07)

* Add package metadata

##### 0.1.0 (2018-03-07)

* Initial release
