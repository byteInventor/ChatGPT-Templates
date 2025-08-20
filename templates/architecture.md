# Architecture Template

Use this template when you need help designing system architecture, database schemas, or API contracts.

## Template

```
**Business case:** [multi-tenant SaaS / microservices / etc.]

**Requirements:** [scalability, cost efficiency, speed]

**Constraints:** [stack, hosting, budget]

**Task:** Design architecture diagram + db schema + api contracts.
```

## Example Usage

```
**Business case:** Multi-tenant SaaS platform for project management with teams of 5-500 users per tenant

**Requirements:** 
- Handle 10,000+ concurrent users
- 99.9% uptime
- Real-time collaboration features
- Cost-efficient scaling
- Fast response times (<200ms API calls)

**Constraints:** 
- Must use AWS infrastructure
- Budget: $5000/month initially
- Team expertise: Node.js, PostgreSQL, Redis
- Must be GDPR compliant

**Task:** Design architecture diagram + db schema + api contracts for user management, project creation, and real-time updates.
```

## What You'll Get

When using this template, you can expect:

- **Architecture Diagram**: High-level system design with components and data flow
- **Database Schema**: Tables, relationships, indexes, and data types
- **API Contracts**: Endpoint definitions, request/response formats, authentication
- **Technology Recommendations**: Specific tools and services suited to your needs
- **Scalability Considerations**: How the architecture handles growth
- **Security Best Practices**: Authentication, authorization, and data protection

## Tips for Better Results

- **Be specific about scale**: Mention expected user counts, data volume, transaction rates
- **Include business context**: Explain the domain and core business operations
- **Mention compliance needs**: GDPR, HIPAA, SOC2, etc.
- **State technology preferences**: What your team knows vs. what you're open to learning
- **Define success metrics**: Performance benchmarks, availability requirements