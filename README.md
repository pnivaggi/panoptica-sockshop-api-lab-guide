# Panoptica API Security

![](./images/lab-topology.png)

The repository provides an introduction lab to Panoptica API Security capabilities. As a target application a custom version of weave's sock shop is used.The following sections are currently available:

- [01. Lab Overview](01.lab-overview.md)
- [02. Panoptica Setup](02.panoptica-install-bundle.md)
- [03. Vulnerable Application Deployment](03.vulnerable-app-deployment.md)
- [04. Runtime Visualization](04.runtime-visualization.md)
- [05. Runtime Policies](05.runtime-policies.md)
- [06. API Token Injection](06.api-token-injection.md)
- [07. Third Party APIs](07.third-party-apis.md)
- [08. OpenAPI Reconstruction and Risk Findings Analysis](08.openapi-spec-reconstr-and-analysis.md)
- [09. OpenAPI Specification Upload and Difference Detection](09.openapi-spec-upload-and-diff.md)
- [10. BFLA Finding](10.bfla-finding.md)
- [11. API Trace Analysis](11.api-trace-analysis.md)
- [12. API Fuzzing Testing](12.api-fuzzing-testing.md)
- [13. Connection Policy](13.connection-policy.md)

The notions covered are the following:

- [01. Lab Overview](01.lab-overview.md): review a Kubernetes cluster example to understand Panoptica's flexibility of requirements 
- [02. Panoptica Setup](02.panoptica-install-bundle.md): setup a Panoptica free account and onboard a Kubernetes cluster
- [03. Vulnerable Application Deployment](03.vulnerable-app-deployment.md): 
  - create protected namespace
  - create application environment
  - manage Sock Shop application and deployment
  - generate traffic load
- [04. Runtime Visualization](04.runtime-visualization.md):
  - List top security risks
  - Visualize workload vulnerabilities and risks
  - Read network activity and runtime cluster events
- [05. Runtime Policies](05.runtime-policies.md):
  - policy-based declarative security - learn about risk-score thresholds and custom policies to apply across an entire environment
- [06. API Token Injection](06.api-token-injection.md):
  - configure API token injection on PayPal API
- [07. Third Party APIs](07.third-party-apis.md):
  - check third party APIs
- [08. OpenAPI Reconstruction and Risk Findings Analysis](08.openapi-spec-reconstr-and-analysis.md):
  - analysis of discovered APIs
  - OpenAPI spec reconstruction
  - analysis of spec risk findings
- [09. OpenAPI Specification Upload and Difference Detection](09.openapi-spec-upload-and-diff.md):
  - upload OpenAPI spec
  - detect differences between expected and real traffic based on given OpenAPI spec
- [10. BFLA Finding](10.bfla-finding.md):
  - build authorization model of applications
  - detect micro-service BFLA
- [11. API Trace Analysis](11.api-trace-analysis.md):
  - trace analysis of real traffic
- [12. API Fuzzing Testing](12.api-fuzzing-testing.md)
- [13. Connection Policy](13.connection-policy.md):
  - connection policy to block inter-service traffic