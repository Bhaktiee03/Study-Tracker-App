#  Study Tracker App

A console-based Java application designed to help students systematically log, track, summarize, and export their daily study activities.

---

##  Project Overview

The *Study Tracker App* is a utility-driven, object-oriented Java application. It allows users to maintain detailed daily study records, view summaries grouped by date or subject, and export all logs into a CSV file for easy offline tracking.

*Note:* The entire program, including the main application class (StudyTrackerApp) and the utility classes (StudyLog and StudyTracker), is contained within the single source file: *StudyTrackerApp.java*.

---

##  Key Features

* *Log Study Sessions:* Record subject, duration, description, and an *auto-generated date*.
* *Display Logs:* View all current study logs stored in memory.
* *Summarize by Date:* Calculate and display *total study hours* grouped by date.
* *Summarize by Subject:* Calculate and display *total study hours* grouped by subject.
* *Export to CSV:* Export all study logs into a file named *MarvellousStudy.csv*.
* *User-Friendly Interface:* Menu-driven interface using switch-case navigation.

---

##  Technologies Used

| Category | Details |
| :--- | :--- |
| *Language* | Java |
| *Data Structures* | java.util.* (ArrayList, TreeMap, Scanner) |
| *Date/Time* | java.time.LocalDate |
| *File Handling* | java.io.* for CSV export |

---

##  How to Compile and Run

Follow these steps from your terminal to get the application running:

1.  *Navigate* to the directory containing *StudyTrackerApp.java*.

2.  *Compile the source file:*
    bash
    javac StudyTrackerApp.java
    

3.  *Run the main application:*
    bash
    java StudyTrackerApp
    

---

##  Application Menu

The program provides the following menu options:

1.  *Insert Study Log*
2.  *Display All Logs*
3.  *Summary by Date*
4.  *Summary by Subject*
5.  *Export to CSV* (Creates MarvellousStudy.csv)
6.  *Exit Application*

---
