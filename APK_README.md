# Daily Micro Habit - Android APK

A fully offline Android app that helps you build better habits through small, manageable daily actions. Built with Apache Cordova from the original HTML/CSS/JavaScript website.

## 📱 **APK Files**

Two APK versions have been generated:

1. **`app-debug.apk`** (3.4 MB) - Debug version for testing and development
2. **`app-release.aab`** (2.5 MB) - Release bundle for Google Play Store distribution

## 🚀 **App Features**

- **100+ Unique Micro Habits**: A curated collection of simple, actionable habits
- **Motivational Quotes**: Inspirational quotes to keep you motivated
- **7-Step Progress Tracker**: Visual progress bar that resets every 7 habits
- **Dark/Light Mode**: Toggle between themes with persistent preference saving
- **Smooth Animations**: Engaging fade-in and bounce animations
- **Sound Effects**: Audio feedback on button clicks (ding.mp3 included)
- **Fully Offline**: Works completely without internet connection
- **Fullscreen Mode**: No address bar or toolbar - pure app experience
- **Back Button Handling**: Back button closes the app (no navigation history)

## 📋 **Installation Instructions**

### For Testing (Debug APK):

1. **Enable Unknown Sources** on your Android device:
   - Go to Settings → Security → Unknown Sources
   - Or Settings → Apps → Special Access → Install Unknown Apps
   - Enable installation from "Files" or your file manager

2. **Transfer the APK**:
   - Copy `app-debug.apk` to your Android device
   - Use USB transfer, email, cloud storage, or any file transfer method

3. **Install the APK**:
   - Open your file manager on Android
   - Navigate to where you saved the APK
   - Tap on `app-debug.apk`
   - Follow the installation prompts
   - Tap "Install" when prompted

4. **Launch the App**:
   - Find "Daily Micro Habit" in your app drawer
   - Tap to open - the app will launch in fullscreen mode

### For Google Play Store (Release Bundle):

The `app-release.aab` file is for Google Play Store distribution and requires signing with a release key before upload.

## 🔧 **Technical Specifications**

- **Platform**: Android 5.1+ (API Level 22+)
- **Target SDK**: Android 13 (API Level 33)
- **Framework**: Apache Cordova 12.0.0
- **WebView**: System WebView (runs your HTML/CSS/JS)
- **Size**: ~3.4 MB (debug) / ~2.5 MB (release)
- **Permissions**: None required - fully self-contained
- **Network**: No internet connection required

## 🎯 **App Behavior**

### Fullscreen Experience:
- No browser address bar or navigation
- No system toolbar
- Immersive fullscreen mode
- Native app-like experience

### Navigation:
- Pressing Android Back button **closes the app**
- No web navigation history
- Single-screen application

### Data Storage:
- Theme preference saved locally
- Progress counter persisted between sessions
- No data sent to external servers
- Complete privacy - all data stays on device

## 🎨 **Features Overview**

1. **Random Habit Generator**: 
   - Click "Show Another Habit" for a new micro habit
   - Over 100 unique habits covering fitness, mindfulness, productivity, and wellness

2. **Progress Tracking**:
   - Visual 7-step progress bar
   - Fills one step with each habit
   - Celebratory message when completing a cycle
   - Auto-resets after 7 steps

3. **Motivational Quotes**:
   - Random inspirational quotes with each habit
   - 10 carefully selected motivational messages

4. **Theme Toggle**:
   - Light and dark mode support
   - Toggle switch in top-right corner
   - Preference saved automatically

5. **Sound Feedback**:
   - Pleasant "ding" sound on button press
   - Audio files included in APK
   - Graceful handling if audio fails

6. **Smooth Animations**:
   - Fade-in and bounce animations
   - Hover effects on buttons
   - Professional UI transitions

## 🛠️ **Development Details**

### Built With:
- **Cordova CLI**: 12.0.0
- **cordova-android**: 12.0.1
- **Target SDK**: Android 13 (API 33)
- **Java**: OpenJDK 17
- **Gradle**: 7.6

### Cordova Plugins Used:
- Core Cordova plugins (built-in)
- No external dependencies
- Pure HTML/CSS/JavaScript implementation

### Build Configuration:
- **Fullscreen**: Enabled in config.xml
- **Orientation**: Portrait mode
- **Splash Screen**: Disabled for instant loading
- **Back Button**: Configured to exit app
- **StatusBar**: Hidden for fullscreen experience

## 📝 **Usage Tips**

1. **Starting Out**: Click "Show Another Habit" to begin
2. **Building Momentum**: Try to complete at least one habit daily
3. **Progress Tracking**: Watch your progress bar fill up
4. **Theme Switching**: Use the toggle for comfortable viewing
5. **Completing Cycles**: Celebrate when you complete all 7 steps!

## 🔐 **Privacy & Security**

- **No Internet Required**: Completely offline application
- **No Data Collection**: No analytics, tracking, or data transmission
- **Local Storage Only**: All preferences saved on your device
- **No Permissions**: App requires no special Android permissions
- **Open Source**: Built from the open-source web version

## 🆘 **Troubleshooting**

### App Won't Install:
- Ensure "Unknown Sources" is enabled
- Check available storage space (need ~10MB free)
- Try redownloading the APK file

### App Crashes on Launch:
- Restart your device
- Clear cache: Settings → Apps → Daily Micro Habit → Storage → Clear Cache
- Reinstall the app

### No Sound:
- Check device volume settings
- Ensure media volume is not muted
- Sound may not work on some custom Android ROMs

### Theme Not Saving:
- Grant storage permissions if prompted
- Try toggling theme switch multiple times
- Reinstall app if issue persists

## 📊 **File Information**

```
app-debug.apk
├── Size: 3.4 MB
├── Architecture: Universal (ARM, x86)
├── Min SDK: 22 (Android 5.1)
├── Target SDK: 33 (Android 13)
└── Signed: Debug certificate

app-release.aab
├── Size: 2.5 MB  
├── Format: Android App Bundle
├── Optimized: Yes
└── Ready for: Google Play Store
```

## 🎉 **Example Micro Habits**

- "Drink a glass of water"
- "Do 10 pushups"
- "Write down one thing you're grateful for"
- "Stretch for 1 minute"
- "Smile at yourself in the mirror"
- "Take 5 deep breaths"
- "Make your bed"
- "Read one page of a book"
- And 100+ more!

## 📞 **Support**

This APK was generated from the Daily Micro Habit web application. For issues or questions:

1. **Web Version**: Try the original web version first
2. **APK Issues**: Check troubleshooting section above
3. **Feature Requests**: Consider them for future versions

---

**Build Information:**
- Generated: 2024
- Cordova Version: 12.0.0
- Platform: cordova-android@12.0.1
- Java: OpenJDK 17
- Build Tool: Gradle 7.6

**Install and start building better habits today! 🌱**