# Changelog
All notable changes to this project will be documented in this file.

## [3.0.1] - 2018-03-31
- Add actions arguments to the log (as `action.args`)
- Depend (peer) on react-waterfall 3.0.1 making dispatcher be always supported

## [3.0.0] - 2018-03-30
- First version
- Mocks the protocol of the redux-devtools-extension
- Time travel support
- Future support for dispatcher (depends on react-waterfall v3.0.1)
- Queue actions when the extension has not yet initialized for later logging