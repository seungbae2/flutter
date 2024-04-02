# 개발환경 설정

1. Xcode 설치
    
    ```
    sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
    sudo xcodebuild -runFirstLaunch
    ```
    
2. iOS Simulator 확인
    
    ```
    open -a Simulator
    ```
    
3. Homebre
    
    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/sb/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
    ```
    
4. Google Chrome
    
    ```
    brew install --cask google-chrome
    ```
    

1. iTerm2
    
    ```
    brew install --cask iterm2
    ```
    
2. Visual Studio Code
    
    ```
    brew install --cask visual-studio-code
    ```
    
3. Flutter
    
    ```
    brew install --cask flutter
    ```
    
4. CocoaPods
    
    ```
    brew install cocoapods
    ```
    
5. Java11
    
    ```
    brew install openjdk@11
    sudo ln -sfn /opt/homebrew/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk
    echo 'export PATH="/opt/homebrew/opt/openjdk@11/bin:$PATH"' >> ~/.zshrc
    export CPPFLAGS="-I/opt/homebrew/opt/openjdk@11/include"
    ```
    
6. Android Studio
    
    ```
    brew install --cask iterm2
    ```
    
7. Android SDK
8. Android Emulator
9. Android command tool line
    
    ```
    Android Studio에서 cmdline-tools 다운
    flutter doctoer --android-licenses
    ```