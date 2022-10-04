## 1.0.0

- Initial version.


## 1.0.1
- Add the ability to manually load the library.


## 1.0.2
- Fix unable to use user-define loader to load library in worker isolate.
- Refactor library loading system, user should derive `LameLibraryLoader` class to load library from different location. 