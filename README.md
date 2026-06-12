# A209877_NurainaSafiah_DrNazatul_Project2

🌱 EduMate

EduMate is an intelligent, privacy-conscious student workspace companion application designed to empower learners through structured academic management and supportive cognitive tools.

🌸 SDG 4 Theme Connection: Quality Education

Traditional scheduling and academic management applications function merely as passive task checklists, frequently ignoring the holistic connection between long study hours, environmental workspace comfort, and psychological burnout. EduMate directly addresses SDG 4 (ensuring inclusive and equitable quality education and promoting lifelong learning opportunities) by integrating real-time task database tracking alongside contextual environment monitoring, offering a personalized, localized, and accessible platform for students to optimize their learning workflows and mental wellness.

✨ Core Features

* **Advanced Declarative UI:** Built entirely with Jetpack Compose following modern Material Design 3 adaptive layout guidelines, featuring a smoothly scrollable multi-card dashboard framework.
* **Offline-First Storage (Room DB):** Strict local reliability architecture keeping all academic tasks, study items, and schedules securely stored via a structured SQLite database framework.
* **Cloud Synchronization (Firebase):** Secure user profile and progress backup pipelines syncing metrics (XP, Streaks) seamlessly to Firestore collections.
* **Ambient Sensor Engine (SensorManager):** Utilizes device hardware ambient light sensors (`Sensor.TYPE_LIGHT`) to monitor study environment lux contexts and actively alert users if a workspace is optimized for reading.
* **Live Insights Network (Retrofit API):** Parses live educational quote assets and motivational microservices over the internet via `zenquotes.io` to reduce learner fatigue and boost focus.
* **Multi-Screen Route Flow:** Interactive navigation graph architecture ensuring smooth passing of state destinations across target functional views.

🛠️ Setup & Installation Instructions

### Prerequisites
Ensure you have a modern stable version of Android Studio installed (supporting Arctic Fox through Koala / Ladybug architectures) along with an Android Virtual Device (AVD) running API level 33 or higher (such as a Pixel 9a configuration setup).

### Execution Details
1. **Clone or Download:** Extract the project source archive files into your local AndroidStudioProjects directory.
2. **Build Sync:** Open the project in Android Studio and allow the Gradle engine to automatically download package dependencies.
3. **Run Application:** Press the green **Run** icon to compile and mount the application onto your emulator.
4. **Simulate Sensors:** To test the light sensor component, open the emulator's **Extended Controls (...)** window panel, select **Virtual Sensors**, navigate to **Additional Sensors**, and adjust the **Light (lux)** slider to observe your app's live responses!
