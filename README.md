# File Processing & System Design Portfolio

This repository contains Python solutions and implementations for six file processing, exception handling, and architectural design tasks.

---

## Table of Contents
1. [Task 1: Mess Bill Processor (Diagnose & Repair)](#task-1-mess-bill-processor-diagnose--repair)
2. [Task 2: Biometric Attendance Files](#task-2-biometric-attendance-files)
3. [Task 3: Custom Exceptions & Error Handling](#task-3-custom-exceptions--error-handling)
4. [Task 4: File and Exception Forensics](#task-4-file-and-exception-forensics)
5. [Task 5: Modular Organisation & Packages](#task-5-modular-organisation--packages)
6. [Task 6: College Fest Registration Desk Design Challenge](#task-6-college-fest-registration-desk-design-challenge)

---

## Task 1: Mess Bill Processor (Diagnose & Repair)
* **Description:** Refactors a poorly designed script that processed student mess bills. Fixes hard-coded paths, resource leaks, memory overload, bare exceptions, and floating-point currency issues by introducing `with` statements, line-by-line streaming, `Decimal` arithmetic, and explicit error logging.
* **File:** `mess_processor.py`

## Task 2: Biometric Attendance Files
* **Description:** Processes daily classroom biometric attendance text files across a directory. Computes monthly attendance percentages, flags students falling below 75% attendance, and generates a structured error log for damaged lines.
* **File:** `attendance_processor.py`

## Task 3: Custom Exceptions & Error Handling
* **Description:** Implements robust exception handling using a custom exception class (`InvalidRecord`), precise `try-except-else-finally` blocks, and error bubbling to handle missing files, incorrect permissions, and malformed data records cleanly.
* **File:** `exception_handler.py`

## Task 4: File and Exception Forensics
* **Description:** Diagnoses and fixes file-writing bugs where logs were overwritten or left unclosed. Implements append mode (`"a"`), newline formatting, and automated fallback error logging to prevent silent failures.
* **File:** `forensics_logger.py`

## Task 5: Modular Organisation & Packages
* **Description:** Organizes the attendance utility into clean functional units (reading, statistics, and reporting) and extends functionality to track students absent for three consecutive days.
* **File:** `modular_attendance.py`

## Task 6: College Fest Registration Desk Design Challenge
* **Description:** A comprehensive data processing pipeline that reads multi-department registration files, validates emails using string methods, removes duplicate registrations using `set` lookups, logs errors, and generates a master list, event-wise participant lists, and a summary report.
* **File:** `fest_registration.py`

---

## Getting Started
1. Ensure Python 3.8+ is installed.
2. Place input text files in the appropriate directories (e.g., `./attendance_records`, `./fest_records`).
3. Run any module directly using:
   ```bash
   python <filename>.py
