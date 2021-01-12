# Patches for GitQlient  

Url: [GitQlient](https://github.com/francescmm/GitQlient)

Below is information on what each patch fixes  

### Patches for v1.2.0 version

  - Fixes program compilation errors
  - "Set log level" in settings does not limit the log content to the selected option, so "All" has also been added
  - The right-click menu for a project should not be initialized from the main page, so closing and pinning/unpinning of the site is disabled
  - Closing the program window after trying to pin the project from the main window will cause crash, so it's fixed
  - If the cloned repository is empty, it is not possible to commit (the problem was solved by the original author and the solution was taken from him - [see here](https://github.com/francescmm/GitQlient/issues/148))
  - Not all tags are visible to the repository - if no annotated version existed for a given version, then a second version was added
  - Closing tabs in submenu (right-click) prevents the last selected applications from being selected from the list again. Closing tabs by pressing the cross symbol does not cause such problems. Fixed.
  - **it is recommended to use also patch for QLogger submodule, to make logs work correctly after changes**
