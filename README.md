# Red Hat OpenShift AI BootCamp

[![Spelling](https://github.com/redhat-na-ssa/hobbyist-guide-to-rhoai/actions/workflows/spellcheck.yml/badge.svg)](https://github.com/redhat-na-ssa/hobbyist-guide-to-rhoai/actions/workflows/spellcheck.yml)

**Acronyms**:

- RHOCP = Red Hat OpenShift Container Platform
- RHOAI = Red Hat OpenShift AI
- ODH = Open Data Hub
- CR = Custom Resource

## About RHOAI

Red Hat OpenShift AI is a platform for data scientists and developers of artificial intelligence and machine learning applications.

OpenShift AI provides an environment to develop, train, serve, test, and monitor AI/ML models and applications on-premise or in the cloud. [More Info](https://docs.redhat.com/en/documentation/red_hat_openshift_ai_self-managed/2.13/html/introduction_to_red_hat_openshift_ai/index)

- Learn more about features and dependencies [(link)](/docs/info-features.md)

## Cluster Setup Steps

0. [Prerequisite](/docs/00-prerequisite.md)
1. [Add administrative user](/docs/01-add-administrative-user.md)
1. [(Optional) Install the web terminal](/docs/02-install-web-terminal.md)
1. [Install RHOAI Kserve dependencies](/docs/03-install-kserve-dependencies.md)
1. [Install RHOAI Operator and Components](/docs/04-install-rhoai-operator.md)
1. [Add a CA bundle](/docs/05-add-ca-bundle.md)
1. [(Optional) Configure RHOAI Operator logger](/docs/06-configure-operator-logger.md)
1. [Enable GPU support for RHOAI](/docs/07-enable-gpu-support.md)
1. [(Optional) Run sample GPU application](/docs/08-run-sample-gpu-application.md)
1. [Configure GPU dashboards](/docs/09-configure-gpu-dashboards.md)
1. [Configure GPU sharing method](/docs/10-configure-gpu-sharing-method.md)
1. [Configure distributed workloads](/docs/11-configure-distributed-workloads.md)
1. [(Optional) Configure Codeflare operator](/docs/12-configure-codeflare-operator.md)
1. [Configure RHOAI](/docs/13-configure-rhoai.md)

### Automation Key

- To run all steps, from this repo's root directory, run below command
  - ```sh
    ./scripts/runstep.sh -s 0
    ```

> NOTE: `Steps 10 - 13 are NOT fully automated, and will need manual configurations`

> For more comprehensive gitops functionality, check out below repository:  
> [**demo-ai-gitops-catalog**](https://github.com/redhat-na-ssa/demo-ai-gitops-catalog)

## Demo Instructions

1. [Distributed Workloads](/docs/demo-distributed_workloads.md)

1. [Fraud Detection](/docs/demo-fraud-detection.md)
