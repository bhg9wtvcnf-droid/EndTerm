# EndTerm
# Library Management System

## Project Description
Library Management System is a Java-based application designed to manage books, library members, and loan operations.
The project demonstrates Object-Oriented Programming principles, Java language features, and design patterns.

## Main Features
- Manage book catalog (printed books, eBooks, reference books)
- Manage library members
- Borrow and return books
- Calculate fines for overdue loans
- Generate loan reports

## Project Structure (Components)
The system is structured into components based on business responsibilities:

- CatalogComponent – manages books and book creation
- LoanManagementComponent – handles borrowing, returning, and fine calculation
- MemberManagementComponent – manages library members
- ReportingComponent – generates reports and summaries

This structure follows component principles such as CCP (Common Closure Principle) and CRP (Common Reuse Principle).

## Design Patterns and Concepts
- Generics – generic CrudRepository<T, ID>
- Singleton – FinePolicy
- Factory – BookFactory
- Builder – LoanReportBuilder
- OOP principles – encapsulation and separation of concerns

## Team
- Aiym Nygmet
- AIbaer Yeerbolati
