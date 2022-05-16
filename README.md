# System Setup
1. [Homebrew](https://brew.sh/)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
2. git
```
brew install git
git config --global user.name "Your Name"
git config --global user.email "Your Email"
```
3. GitHub
- Generate token [Github->Settings->Developer Settings->Personal access token](https://github.com/settings/tokens)
```   
brew install gh
gh auth setup-git-credential-helper
```
4. [Android Studio](https://developer.android.com/studio)
