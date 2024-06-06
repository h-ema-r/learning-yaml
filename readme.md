# What is YAML?
-YAML, which stands for "YAML Ain't Markup Language", is a human-readable data serialization standard that can be used in conjunction with all programming languages and is often used to write configuration files.Here's a brief overview of YAML:

**1. Human-Readable:** YAML's syntax is designed to be  easy for humans to read and write. It uses indentation to denote structure, which makes the data representation clear and concise.

**2. Data Serialization:** YAML is used to serialize data, meaning it converts data structures or objects into a format that can be stored and reconstructed later.

**3. Common Uses:** YAML is commonly used for configuration files in various software applications and for data exchange between languages with different data structures. For example, it's used in Docker Compose files, Kubernetes configuration files, and Ansible playbooks.

**4. Syntax:**
- uses Python-style indentation to indicate nesting.
- Whitespaces for indentation & Tab are not allowed.
- No Format Symbols like braces, square, brackets, or quotation tags.
- Uses .yml or .yaml file extension.

**5. YAML Structure**
- Structure of a YAML file is a map or list .
- Maps allows us to associate key-value pairs.
- Keys are Unique, and the order doesn't matter.
- A map in YAML needs to be resolved before it can be closed, and a new map is created.

**6. YAML Data Types**
- Scalar(Strings, integers, dates, numbers or Boolean)
- A list(collection of items) and it can start with a dash, with indentation separating the parent.
- New Map can be created by either increasing indentation level or by resolving the previous map.
