# Change Log

The change log describes what is "Added", "Removed", "Changed" or "Fixed" between each release.

## 4.3.0

### Removed

- Drop support for PHP < 7.2

## 4.2.0

## 4.1.0

### Changed

- Refactored `AbstractHttpProvider::getUrlContents` to split it up to different functions. We now
got `AbstractHttpProvider::getUrlContents`, `AbstractHttpProvider::getRequest` and `AbstractHttpProvider::getParsedResponse`.

## 4.0.0

No changes since beta 2. 

## 4.0.0-beta2

- Removed `AbstractHttpProvider::setMessageFactory`.
- Removed `AbstractHttpProvider::getHttpClient`.
- Make sure we have a `MessageFactory` in the constructor of `AbstractHttpProvider`. 

## 4.0.0-beta1

First release of this library. 
