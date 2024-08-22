---
title: "Projects"
---
<!-- This exists so that theres a gap between the table of contents and the heading on smaller screens -->
<br>

## Blonote
{{< projectBox githubLink="https://github.com/your-repo-link" deploymentLink="https://your-deployment-link" techStack="TypeScript, Cloudwfare Workers, Hono.js, PostgreSQL, Prisma, React, Tailwind" >}}
- Created a Blogging site where users can Sign Up/Log In, read and write blogs with Notion-like text editing features like:
multiple headings, images, lists, tables, text colouring, text alignment, etc
- Created and deployed backend in Cloudfare Workers runtime for high performance and used Hono as the routing framework
- Used Prisma Accelerate for Connection Pooling and Prisma ORM to store data on Postgres Database (deployed on Neon)
- Used Zod for input schema validation, PBKDF2 for hashing password and JWT for authorization
- Created responsive and optimal frontend using React and Tailwind
{{< /projectBox >}}


## FlySh UNIX Shell
{{< projectBox githubLink="https://github.com/your-repo-link"  techStack="C, GNU Make, Syscalls, Compiler Design" >}}
- Created a UNIX shell which can execute commands like: ls, echo, pwd, grep, mkdir, rm, cat, clear, touch, etc.
- Implemented custom Lexer, Parser, Tokenizer and Abstract Syntax Tree (AST)
- Executed tokenized commands using execv, fork and waitpid syscalls
{{< /projectBox >}}


## Walletora: E-Wallet
{{< projectBox githubLink="https://github.com/your-repo-link"  techStack="React, Express, Node.js, MongoDB, JavaScript, Tailwind" >}}
- Created a E-Wallet which follows ACID properties using MongoDB Transactions ensuring rollback mechanism
- Created responsive frontend using React and Tailwind with which users can easily send money from one user to other
- Implemented JWT authorization for Sign up/ Log in routes using JWT tokens stored in browser’s localStorage
- Used Zod for input schema validation and Bcrypt to hash passwords
- Used Mongoose to store data in MongoDB and used Vite as the build tool
{{< /projectBox >}}


## Train Ticket Booking Management System
{{< projectBox githubLink="https://github.com/your-repo-link"  techStack="Java, Gradle" >}}
- Created a CLI program based on OOPs principles using which users can book trains tickets from one destination to another
- Features included: Sign up/Log in, Searching train according to source/destination, Booking tickets for seats of the selected
train, Cancelling booking
- Used Java8 features like: Stream API (to iterate easily and perform map/filter), Optional (to avoid NullPointerException)
- Used Jackson ObjectMapper to serialize/deserialize data from/to JSON files where in-memory data about users and trains
are stored, used Bcrypt to hash passwords and used Gradle as the build tool
{{< /projectBox >}}