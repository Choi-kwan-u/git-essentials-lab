# How to run the library demo

## Prerequisites

- JDK 17 or later (`java` and `javac` on your PATH)
- Python 3.9 or later
- A clone of this repository

No Maven, Gradle, or third-party Java library is needed.

## Run

From the repository root:

```text
python3 run.py demo
```

## What the demo does

The demo compiles the small library application and runs a fixed scenario:
it prints the student and faculty borrowing limits, searches the catalog for
`git`, borrows the matching book for a member, shows the loan receipt with its
due date, and finally returns the book and prints the overdue fee.
