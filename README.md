## Advanced AWS CDK Learning Resources
> Last verified: October 2026 | Current CDK version: aws-cdk-lib v2.275.0 / CLI v2.1146.1

---
### MCP Server

- Great add-on for your preferred Coding Agent: the official **AWS IaC MCP Server** (inlcudes CDK features): https://github.com/awslabs/mcp/tree/main/src/aws-iac-mcp-server
  - Get started with this MCP server for creating and troubleshooting AWS infrastructure as code. Tools include CloudFormation template validation, compliance checking, deployment troubleshooting, CloudFormation documentation search, AWS CDK documentation search with official CDK knowledge bases, CDK code samples and constructs, and CDK and CloudFormation best practices.

---

### Official CDK sample content

- **[GitHub AWS-Samples / aws-cdk-examples](https://github.com/aws-samples/aws-cdk-examples)**
  — Official CDK sample code.

---

### Advanced Topics to Explore

- **Constructs Hub**
  - https://constructs.dev/search?cdk=aws-cdk&sort=downloadsDesc&offset=0

- **[AWS CDK Pipelines](https://docs.aws.amazon.com/cdk/api/v2/docs/aws-cdk-lib.pipelines-readme.html)**
  — Self-mutating CI/CD pipelines in CDK. Use the **modern API** (not the
  original/legacy one). Supports parallel deployments, multiple synth inputs,
  and deployment engines beyond CodePipeline. ✅ Still current.

- **[CDK Mixins](https://docs.aws.amazon.com/cdk/api/v2/docs/aws-cdk-lib-readme.html)**
  — 🆕 **NEW (GA: March 2026).** Apply composable, reusable abstractions to
  any construct (L1, L2, or custom) using a simple `.with()` syntax — without
  rebuilding existing infrastructure code. A major new pattern to teach.

- **[cdk refactor command](https://docs.aws.amazon.com/cdk/v2/guide/ref-cli-cmd-refactor.html)**
  — 🆕 **NEW (Preview: September 2025).** Safely rename constructs, move
  resources between stacks, and reorganize CDK apps without replacing deployed
  resources. Eliminates a major pain point
