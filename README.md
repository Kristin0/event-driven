### Node.js applications infrastructure

• Two deployment pipelines: Core API(backend), Frontend

• Pipelines are initiated by pull request merged commit events

• The main CI/CD file, "buildspec.yml," is stored within service configuration directories and is essential for successful builds

• CloudFront invalidation

• Discord bot as a notification manager

• The databases - PostgreSQL, Redis

• Authorization - Amazon Cognito
