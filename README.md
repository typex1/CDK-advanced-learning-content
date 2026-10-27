## Advanced AWS CDK Learning Resources

### Official Workshops & Hands-On Labs

- **[AWS CDK Immersion Day Workshop](https://catalog.workshops.aws/cdkimmersionday)** — A deeper, structured workshop covering advanced CDK patterns, testing, and pipelines. Great next step after the basic workshop.
- **[AWS Workshop Studio Catalog](https://workshops.aws)** — Filter by "CDK" and complexity level 300–400 for expert-level content. Covers topics like CDK Pipelines, multi-account deployments, and more.
- **[AWS Builder Center Workshops](https://builder.aws.com/build/workshops)** — The full AWS workshops catalog with filtering by skill level (100-Beginner through 400-Expert), service, and category.

### Advanced Topics to Explore

- **[AWS CDK Pipelines](https://docs.aws.amazon.com/cdk/v2/guide/cdk_pipeline.html)** — Building self-mutating CI/CD pipelines entirely in CDK. A major real-world use case.
- **[AWS Solutions Constructs](https://docs.aws.amazon.com/solutions/latest/constructs/welcome.html)** — Pre-built, vetted architecture patterns (e.g., Lambda → SQS, Fargate → EventBridge) that combine multiple services with best practices baked in.
- **[Construct Hub](https://constructs.dev)** — A registry of open-source CDK libraries from AWS and the community. Great for exploring reusable constructs.

### Best Practices & Prescriptive Guidance

- **[Best Practices for CDK with TypeScript](https://docs.aws.amazon.com/prescriptive-guidance/latest/best-practices-cdk-typescript-iac/introduction.html)** — AWS Prescriptive Guidance covering IaC best practices, testing strategies, and project structure.
- **[AWS CDK Layers Pattern](https://docs.aws.amazon.com/prescriptive-guidance/latest/aws-cdk-layers/introduction.html)** — Guidance on organizing CDK apps into layers for maintainability and reuse.
- **[cdk-nag](https://github.com/cdklabs/cdk-nag)** — A tool for enforcing security and compliance rules in CDK apps. Excellent for teaching security-aware IaC.

### Testing CDK Applications

- **[Testing CDK Applications](https://docs.aws.amazon.com/cdk/v2/guide/testing.html)** — Official docs on unit testing CDK stacks using fine-grained assertions and snapshot tests.

### GitHub & Community

- **[AWS CDK Examples (GitHub)](https://github.com/aws-samples/aws-cdk-examples)** — A large collection of real-world CDK examples across many services and languages.
- **[AWS CDK GitHub Repository](https://github.com/aws/aws-cdk)** — Reading RFCs and issues is a great way for advanced students to understand design decisions.

---

**Suggested learning path for advanced students:**

1. CDK Pipelines (self-mutating CI/CD)
2. Multi-account/multi-region deployments
3. Writing and publishing custom constructs
4. Testing with `assertions` module + `cdk-nag`
5. AWS Solutions Constructs for production-ready patterns
# CDK-advanced-learning-content
