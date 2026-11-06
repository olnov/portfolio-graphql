## Description

This is an implementation of a test assignment from IT SMI for evaluating skills.

This is a digital portfolio backend implementation, that represents your professional profile, skills, work experience, and projects.

## Requirements

Backend should provide an Apollo Sandbox through which you can access information about yourself.
It should return:

1. Profile:
  - name;
  - short description;
  - links to GitHub/LinkedIn or other professional resources.
2. List of skills.
3. Work experience:
  - company;
  - position;
  - period of work;
  - your achievements.
4. Projects:
  - title;
  - link to project/repository.

Database should be initialized with your data upon application startup.

API should allow fetching the profile and related data.
For example, a GraphQL query to fetch the profile and related data could look like this:
```graphql
query {
  profile {
    name
    description
    skills {
      name
    }
    experience {
      company
      position
    }
    projects {
      name
    }
  }
}
```


## Technologies Used

- TypeScript;
- PostgreSQL;
- Docker;
- Nest JS;
- Git;
- Claude Code;
- S3 storage;
- Prisma;
- GraphQL.

## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

Yet to be considered.

## Observability

Out of the scope of this particular project.