# DBMS_Project
# **Lakes International School - Database Management System (LISDBMS)**

## **Project Overview**

The Lakes International School Database Management System (LISDBMS) is a Python-based application designed to manage and maintain the data of students, teachers, and staff. It provides an intuitive interface that allows authorized users, specifically the school's staff, to perform a range of CRUD (Create, Read, Update, Delete) operations on the data stored in the system.

## **Features and Functionalities**

1. **User Authentication System**: 
   - The system is equipped with a login screen to ensure data security. 
   - Staff members can log in using their unique staff ID and associated password.

2. **CRUD Operations**:
   - **Viewing Data**: Authorized users can view the details of teachers and students. This data can be filtered based on specific criteria such as the subject taught by a teacher or the class in which a student is enrolled.
   - **Registering Data**: The system provides functionalities to add new entries for teachers and students, capturing pertinent details like teacher's name, post, date of joining, salary, etc. or student's name, roll number, class, and contact details.
   - **Updating Data**: Existing data entries can be updated. This is useful in scenarios where a teacher might get a promotion, or a student's contact details change.
   - **Removing Data**: In cases of teacher retirements or students graduating, their data can be safely removed from the system.

## **Technical Details**

- **Database**:
  - The system utilizes MySQL as its database, providing robustness and reliability.
  - Table structures have been defined for staff, student details, and teacher details.
  
- **Development**:
  - Developed in Python, leveraging the `mysql.connector` library for database interactions.

## **Security Considerations**

While the initial design of the system stores passwords in plaintext, future iterations should consider hashing passwords for improved security. Proper error handling mechanisms also need to be incorporated to enhance system resilience and user experience.

## **Usage**

The intended users are the staff members of Lakes International School. After successful authentication, users are presented with various options to view, register, update, or remove details. The system is designed with user-friendliness in mind, and choices are provided in a menu-driven format.

## **Conclusion**

The LISDBMS is a comprehensive tool aimed at streamlining data management processes for Lakes International School. Through its user-friendly interface, the school's administration can ensure accurate and up-to-date record-keeping, allowing for more efficient operations and improved decision-making.
