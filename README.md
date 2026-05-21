# MySQL_Normalization
These projects demonstrate the application of database normalization (1NF–5NF, BCNF) to real-world scenarios in telecom and HR systems. The work highlights how normalization reduces redundancy, eliminates anomalies, and ensures data integrity by systematically restructuring tables into well-defined relational models.
Telecom Database Normalization


Identified Issues: Data redundancy, multi-valued attributes, update/insertion/deletion anomalies.

1NF Conversion: Flattened multi-valued attributes into atomic rows.

2NF Conversion: Separated customer, plan, tower, services, and devices into distinct tables.

3NF Conversion: Removed transitive dependencies by introducing service and device reference tables.

BCNF Compliance: Ensured all determinants are candidate keys.

Higher Normal Forms: Addressed multi-valued dependencies (4NF) and join dependencies (5NF).

Final Design: Independent tables for Customer, Plan, Tower, Service, Device, and relationship tables (Customer_Plan, Customer_Service, Customer_Device).

HR Database Normalization


Identified Issues: Redundant manager/project data, multi-valued skills/certifications, anomalies in updates and deletions.

1NF Conversion: Expanded skills and certifications into separate rows.

2NF Conversion: Split employee, skills, certifications, and projects into separate tables.

3NF Conversion: Introduced Department and Project tables to remove transitive dependencies.

BCNF Compliance: Ensured all functional dependencies are based on candidate keys.

Higher Normal Forms: Considered multi-valued dependencies (skills vs certifications) and join dependencies across projects.

Final Design: Employee, Department, Skills, Certifications, Project, and Employee_Project tables for clean relational structure.

/*Learning Outcomes*/


Mastered step-by-step normalization from 1NF to 5NF and BCNF.

Gained practical experience in eliminating redundancy and anomalies.

Designed scalable relational schemas for telecom and HR domains.

Strengthened ability to apply theory to real-world business data models.
