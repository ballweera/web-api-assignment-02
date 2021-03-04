# Instruction
1. Create API `POST /books` for adding book information
2. Create API `GET /books/:id` for retrieving book information

# Book data schema
- title: string
- price: number
- unit: number
- isbn: string
- image url: string

# Criteria to pass the assignment
- Commit #1: set up the project (library must be installed)
- Commit #2: create `POST /books` to store book data into array
- Commit #3: create `GET /books/:id` to retrieve book data from array
- Commit #4: update `POST /books` to store book data into MongoDB
- Commit #5: update `GET /books/:id` to retrieve data from MongoDB
- .gitignore to skip `node_modules` must be incluced into the project