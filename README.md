## Advanced AWS CDK Learning Resources
> Last verified: October 2026 | Current CDK version: aws-cdk-lib v2.275.0 / CLI v2.1146.1

---

### ⚠️ Important: CDK v1 is End-of-Life
AWS CDK v1 reached end-of-support on **June 1, 2023**. All resources below
refer to **CDK v2** only. Make sure your students are using `aws-cdk-lib` (v2),
not the old `@aws-cdk/core` (v1) packages.

---

### Official Workshops & Hands-On Labs

- **[AWS CDK Immersion Day Workshop](https://catalog.workshops.aws/cdkimmersionday)**
  — Structured workshop covering advanced CDK patterns, testing, and pipelines.
  Great next step after cdkworkshop.com. ✅ Still current.

- **[AWS Workshop Studio Catalog](https://workshops.aws)**
  — Filter by "CDK" and complexity level 300–400 for expert-level content.
  Covers CDK Pipelines, multi-account deployments, and more. ✅ Still current.

- **[AWS Builder Center Workshops](https://builder.aws.com/build/workshops)**
  — Full AWS workshops catalog with filtering by skill level (100–400),
  service, and category. ✅ Still current.

---

### Advanced Topics to Explore

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
