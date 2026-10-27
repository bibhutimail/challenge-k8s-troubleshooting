
# FDX Academy — Fix the Broken Kubernetes Deployment

## Challenge Overview

A web application has been deployed to Kubernetes, but it is not
working as expected. Your task is to investigate the problem,
identify the root causes, fix the configuration, and prove that
the application is healthy.

**Difficulty:** Intermediate  
**Estimated time:** 60–120 minutes  
**Category:** Kubernetes Troubleshooting

## Learning Objectives

- Troubleshoot Kubernetes Deployments and Pods.
- Interpret Pod events and container status.
- Understand Services, selectors, and target ports.
- Validate application availability.
- Document root causes and corrective actions.

## Prerequisites

- Basic Kubernetes knowledge
- kubectl
- kind or minikube
- A terminal with internet access to pull container images

## Getting Started

1. Clone this repository.
2. Create a local Kubernetes cluster using kind or minikube.
3. Review the files in the `manifests/` directory.
4. Deploy the supplied resources.
5. Investigate the application failure.
6. Correct the configuration and validate the application.

## Your Tasks

1. Identify all configuration problems.
2. Explain the root cause of each problem.
3. Fix the Kubernetes resources.
4. Confirm that the Pod becomes Ready.
5. Confirm that the Service has healthy endpoints.
6. Test access to the application.
7. Document your changes and test results.

## Acceptance Criteria

- All intended application Pods are Ready.
- The Service selects the correct Pods.
- The Service forwards traffic to the correct container port.
- The application returns a successful HTTP response.
- The solution does not introduce unnecessary privileges.
- The submission includes clear troubleshooting evidence.

## Submission

Follow `SUBMISSION.md`.

Submit your own repository URL and commit reference through
the FDX Academy challenge platform when available.

## Safety

Use a local, disposable Kubernetes cluster.
Never submit credentials, kubeconfig files, access tokens,
or production configuration.

## Assessment

Submissions are reviewed against the challenge rubric.
A successful deployment alone is not sufficient: explain
the root causes and demonstrate how you validated the fix.
