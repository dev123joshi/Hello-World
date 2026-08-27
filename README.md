# Experiment 1: Develop a Simple "Hello World" Android Application

## 1. Aim

To develop a simple **Hello World Android application** using Android Studio and understand the basic structure and working of an Android application.

## 2. Objective

The objective of this experiment is to:

* Create a basic Android application using Android Studio.
* Understand the structure of an Android project.
* Display a simple "Hello World" message on the screen.
* Build and run the application successfully.
* Perform basic test cases to verify the application output.

## 3. Concept / Technology Used

This experiment uses the following technologies:

* **Android Studio** – Integrated Development Environment (IDE) used to develop Android applications.
* **Android SDK** – Provides the tools and libraries required to build Android applications.
* **Gradle** – Build automation system used by Android projects.
* **Kotlin** – Programming language used for Android development.
* **XML / Android UI components** – Used to design the application interface.

## 4. Scenario

A simple Android application is developed that displays a **"Hello World!"** message when launched.

This is a beginner-level application used to understand how an Android project is created, built, installed, and executed on an Android device or emulator.

## 5. Project Structure

The main project structure is:

```text
Hello-World/
│
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── .../
│           ├── res/
│           │   ├── drawable/
│           │   ├── mipmap/
│           │   └── values/
│           └── AndroidManifest.xml
│
├── gradle/
│
├── .gitignore
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
└── settings.gradle.kts
```

### Important Files

**`MainActivity.kt`**
Contains the main activity and the logic for displaying the application screen.

**`activity_main.xml`**
Defines the user interface of the application, if the project uses XML-based layouts.

**`AndroidManifest.xml`**
Contains important information about the application, including the application component configuration.

**`build.gradle.kts`**
Contains Gradle configuration required to build the Android project.

**`settings.gradle.kts`**
Defines the project configuration and included modules.

## 6. Application Output

When the application is successfully launched, the screen displays:

> **Hello World!**

### Output Screenshot

Add your application output screenshot below:

```markdown
![Application Output](screenshots/output.png)
```

## 7. Test Cases

### Test Case 1: Application Launch

**Test Objective:**
Verify that the application launches successfully.

**Steps:**

1. Open the application.
2. Run the application on an emulator or Android device.
3. Observe the application screen.

**Expected Result:**
The application should launch without errors and display the Hello World screen.

**Result:**
Pass

**Screenshot:**

```markdown
![Test Case 1](screenshots/testcase1.png)
```

---

### Test Case 2: Hello World Text Display

**Test Objective:**
Verify that the "Hello World!" text is displayed correctly.

**Steps:**

1. Launch the application.
2. Observe the main screen.
3. Check the displayed text.

**Expected Result:**
The screen should display the text **"Hello World!"** correctly.

**Result:**
Pass

**Screenshot:**

```markdown
![Test Case 2](screenshots/testcase2.png)
```

---

### Test Case 3: Application Re-launch

**Test Objective:**
Verify that the application continues to work correctly after closing and reopening it.

**Steps:**

1. Launch the application.
2. Close the application.
3. Open the application again.
4. Observe the main screen.

**Expected Result:**
The application should launch successfully again and display **"Hello World!"**.

**Result:**
Pass

**Screenshot:**

<img width="1866" height="855" alt="prg1" src="https://github.com/user-attachments/assets/7d46bc5a-6ce2-4ae2-ab9d-c97a0877f429" />



## 8. Result

The **Hello World Android application** was successfully developed and executed using Android Studio.

The application successfully displays the **"Hello World!"** message, demonstrating the basic structure and execution of an Android application.

## 9. Conclusion

This experiment provided an introduction to Android application development using Android Studio. It helped in understanding the basic Android project structure, Gradle build system, application execution, and testing of a simple Android application.

## 10. GitHub Repository

The complete project is available in this GitHub repository:

**Hello World Android Application**
`https://github.com/dev123joshi/Hello-World`
