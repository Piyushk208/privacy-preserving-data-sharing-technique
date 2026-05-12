# 🔐 Privacy-Preserving Data Sharing Technique

A Python-based privacy-preserving data anonymization system designed to secure sensitive personal information while maintaining data usability for analysis and research purposes. This project demonstrates the practical implementation of multiple data privacy techniques on a synthetic dataset containing personally identifiable information (PII) such as Aadhaar numbers, age, city, and salary details.

The system applies a combination of anonymization methods including Aadhaar masking, age generalization, salary perturbation, and SHA-256-based city hashing with salting to reduce the risk of identity disclosure and re-identification attacks. Additionally, the project evaluates the effectiveness of privacy protection using the K-anonymity model, which measures how well individual records are hidden within groups of similar records.

This project highlights important concepts in data privacy, cybersecurity, and privacy-preserving data publishing by balancing two major goals:

* Protecting sensitive user information
* Preserving data utility for analytics and research

## ✨ Key Features

* Removal of direct identifiers for enhanced privacy
* Partial masking of Aadhaar numbers
* Conversion of exact ages into age groups
* Salary anonymization using random perturbation
* Secure hashing of city names using SHA-256 with salt
* K-anonymity calculation and privacy strength evaluation
* Logging and audit tracking for transparency

## 🛠️ Technologies Used

* Python
* Pandas
* Hashlib
* Logging
* Random Module

## 📊 Applications

* Privacy-preserving data sharing
* Research and academic projects
* Cybersecurity and data protection studies
* Secure data publishing and analytics

## 🚀 Future Enhancements

* Implementation of advanced privacy models such as L-diversity and T-closeness
* Integration with real-world datasets
* Development of a web-based interface for interactive anonymization
* Export and visualization of anonymized datasets
