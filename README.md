# Library Management System

A software system for managing library books and members.

# Language Decision Justification: Why Python is Suitable for the LMS Project

Python is an appropriate programming language for the Library
Management System (LMS) project due to its high productivity,
readability, and strong ecosystem support. As a high-level
language with simple and expressive syntax, Python allows
developers to focus more on solving business problems rather
than dealing with complex language constructs. This is
particularly important for an LMS, which involves modeling
real-world entities such as books, members, and transactions.

From a learning perspective, Python reinforces key software
engineering concepts such as object-oriented programming,
modular design, and unit testing. Its structure supports clean
separation of concerns through packages and modules, which
aligns well with the proposed project architecture (models,
services, and utilities). This makes it ideal for implementing
layered design and maintainable code.

Python also has excellent testing support through frameworks
like pytest, which simplifies test-driven development and
ensures reliability of the system. For version control and
collaboration, Python integrates seamlessly with Git-based
workflows.

Additionally, Python’s scalability allows the project to evolve
in the future. The LMS could later be extended into a web-based
system using frameworks such as Flask or Django without
changing the core language. Overall, Python satisfies
productivity, educational value, maintainability, and
extensibility requirements for the LMS project.

## Construction Decisions

- **Language:** Python 3.8+
- **Testing:** pytest
- **Version Control:** Git

## Project Structure

- `src/` - Source code
- `tests/` - Unit tests

## Getting Started

1. Clone the repository: `git clone https://github.com/gubioabdul/lms-project.git`

2. Install dependencies: `pip install -r requirements.txt`

3. Run tests: `pytest`