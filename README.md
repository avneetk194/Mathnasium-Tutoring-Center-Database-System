# Mathnasium-Tutoring-Center-Database-System
End-to-end MySQL database project supporting student enrollment, tutor scheduling, attendance tracking, payment processing, and progress reporting.

Mathnasium Tutoring Center Database System
Project Overview

This project is a comprehensive relational database management system designed for a Mathnasium tutoring center. The database streamlines core business operations including student enrollment, tutor scheduling, attendance tracking, payment processing, and academic progress reporting.

The goal of this project was to design and implement a scalable MySQL database that supports efficient day-to-day operations while maintaining data integrity and supporting future business growth.

Technologies Used
MySQL
ER/EER Modeling
Relational Database Design
SQL
Database Normalization (3NF)
Foreign Keys
Constraints
Joins
Stored Procedures
Indexing
Business Problem

Tutoring centers manage large amounts of operational data, including students, tutors, schedules, attendance records, payments, and progress reports. Without a centralized database, these processes become difficult to manage and scale.

This database provides a structured solution that improves organization, consistency, and reporting capabilities.

Database Features
Student enrollment management
Tutor assignment and scheduling
Session attendance tracking
Parent and guardian management
Payment processing and package plans
Academic progress reporting
Multi-location support
Business analytics and reporting
Database Design

The system contains 14 interconnected tables representing key business entities, including:

Student
Tutor
Subject
Enrollment
Session
Session Attendance
Parent Guardian
Package Plan
Payment
Progress Report
Center
Location

The database was normalized to Third Normal Form (3NF) to reduce redundancy and improve data integrity.

Key Design Decisions
Implemented associative entities to resolve many-to-many relationships.
Enforced referential integrity using foreign keys.
Added CHECK and UNIQUE constraints to maintain data quality.
Designed the schema to support scalability across multiple tutoring centers.
Used structured relationships to support reporting and analytics.
Example Business Use Cases
Student Registration

Register new students, link guardians, and assign tutoring packages.

Session Scheduling

Assign tutors to sessions based on subject expertise and availability.

Attendance Tracking

Record student participation and session attendance.

Revenue Analytics

Generate reports on package sales and tutoring center revenue.

Project Outcomes
Developed a fully functional relational database schema.
Implemented and tested database constraints.
Validated relationships through SQL queries and business scenarios.
Demonstrated real-world tutoring center workflows using SQL operations.
Created analytical reports to support operational decision-making.

Future Enhancements
Parent web portal for progress tracking
Automated monthly revenue reports
Performance optimization through indexing
Enhanced business intelligence reporting
Additional automation using stored procedures and triggers

Repository Contents
Project Report (PDF)
ER Diagram
Database Design Documentation
Sample SQL Queries and Outputs

Authors
Avneet Kaur
Sadia Sultana
Shifath Hossain
