# Build status - [![Build Status](https://travis-ci.org/DeanCoulstockTW/Together_App.svg?branch=master)](https://travis-ci.org/DeanCoulstockTW/Together_App)

# Instructions

### Recommended: Pre-commit/Pre-push hook
1. For the pre-commit/pre-push hook,ensure you have already set `$TALISMAN_HOME` to `$PATH`

2. Make sure your Talisman hook is installed with the following commands.

    ```sh
    # Download the talisman installer script
    curl https://thoughtworks.github.io/talisman/install.sh > ~/install-talisman.sh
    chmod +x ~/install-talisman.sh
    
    # Install to a single project
    cd my-git-project
    
    # as a pre-push hook
    ~/install-talisman.sh
    
    # or as a pre-commit hook
    ~/install-talisman.sh pre-commit
    ```

### Technologies

- iOS:  - React Native, Babel, CocoaPods
- Android:  - Gradle, Babel
### Testing

- Jest testing framework
