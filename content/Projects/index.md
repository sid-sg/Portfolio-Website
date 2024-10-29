---
title: "Projects"
---
<!-- This exists so that theres a gap between the table of contents and the heading on smaller screens -->
<br>

## Walletora: E-Wallet
{{< projectBox githubLink="https://github.com/sid-sg/Walletora"  techStack="TypeScript, Next.js, Node.js, Express.js, Turborepo, Docker, CI/CD, Postgres" >}}
- Built monorepo using Turborepo with Next.js user app and Express.js webhook server
- Implemented user authentication using NextAuth; developed balance tracking and peer-to-peer money transfer features
- Integrated webhooks for real-time deposits from bank accounts to user wallets
- Ensured ACID compliance using PostgreSQL transactions and row-level locking with ”FOR UPDATE” clause
- Used Docker to containerize the apps and host images in Docker Hub
- Created CI/CD pipelines with GitHub Actions for building and deploying Docker images to AWS EC2
{{< /projectBox >}}

## Blonote
{{< projectBox githubLink="https://github.com/sid-sg/Blonote" deploymentLink="https://blonote.vercel.app/" techStack="TypeScript, Cloudflare Workers, Hono.js, PostgreSQL, Prisma, React, Tailwind" >}}
- Developed a blogging platform with Sign Up/Log In functionality and Notion-style text editing using BlockNote (supports
headings, images, lists, tables, and text formatting)
- Created and deployed the backend on Cloudflare Workers using Hono for routing
- Implemented Prisma Accelerate for connection pooling and Prisma ORM to manage data in a PostgreSQL database
- Ensured secure authentication with JWT and password hashing using PBKDF2; validated inputs with Zod
- Created responsive and optimal frontend using React and Tailwind
{{< /projectBox >}}


## FlySh UNIX Shell
{{< projectBox githubLink="https://github.com/sid-sg/Flysh-UNIX-Shell"  techStack="C, GNU Make, Syscalls, Compiler Design" >}}
- Developed a custom UNIX shell capable of executing standard commands such as ls, echo, pwd, rm, cat, clear, etc
- Designed and implemented a Lexer, Parser, Tokenizer, and Abstract Syntax Tree (AST) to process user inputs
- Handled command execution using syscalls like execv, fork, and waitpid for process management
{{< /projectBox >}}


## Train Ticket Booking Management System
{{< projectBox githubLink="https://github.com/sid-sg/Train-Ticket-Booking-System"  techStack="Java, Gradle" >}}
- Created a CLI program based on OOPs principles using which users can book trains tickets from one destination to another
- Features included: Sign up/Log in, Searching train according to source/destination, Booking tickets for seats of the selected
train, Cancelling booking
- Used Java8 features like: Stream API (to iterate easily and perform map/filter), Optional (to avoid NullPointerException)
- Used Jackson ObjectMapper to serialize/deserialize data from/to JSON files where in-memory data about users and trains
are stored, used Bcrypt to hash passwords and used Gradle as the build tool
{{< /projectBox >}}