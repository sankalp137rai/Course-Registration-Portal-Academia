# Course Registration Portal (Academia)

## Project Description

The Course Registration Portal (Academia) is a user-friendly and multifunctional system designed to manage academic operations for students, faculty, and administrators. This project implements a client-server architecture using socket programming to handle multiple concurrent connections.

## Features

- Secure login system for Students, Faculty, and Administrators
- File-based storage for Student, Faculty, and Course information
- Role-based access control
- Password-protected administrative access

### Administrator Features
- Add new students
- Add new faculty members
- Activate/Deactivate student accounts
- Update student/faculty details

### Student Features
- Enroll in new courses
- Unenroll from courses
- View enrolled courses
- Change password

### Faculty Features
- Add new courses
- Remove offered courses
- View course enrollments
- Change password

## Technical Details

- Implemented using socket programming
- Server maintains the database and serves multiple clients concurrently
- Read locks for viewing course details
- Write locks for enrollment/unenrollment operations to protect critical data
- Courses have a limited number of seats
