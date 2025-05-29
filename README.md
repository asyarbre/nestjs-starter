# Nest JS + TypeORM + PostgreSQL + Authentication

## Features
This repository is packed with:

- Absolute Import and Path Alias — Import components using @/
- Prettier — Format your code consistently
- Husky & Lint Staged — Run scripts on your staged files before they are committed
- Conventional Commit Lint — Make sure you & your teammates follow conventional commit

## Getting Started

### 1. Clone this template 
   ```bash
   git clone https://github.com/asyarbre/nestjs-starter.git
   ```

### 2. Install dependencies
It is encouraged to use **pnpm** so the husky hooks can work properly.

```bash
pnpm install
```

### 3. Run the development server

You can start the server using this command:

```bash
pnpm start:dev
```

### 4. Make Migrations

You can make migration using this command:

```bash
pnpm run migration:generate src/migrations/createTableTag
```

### 4. Run Migrations

You can run the migration using this command:

```bash
pnpm run migration:run
```
