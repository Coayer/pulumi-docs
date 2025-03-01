---
title_tag: Next Steps | Kubernetes
meta_desc: This page provides a list of tutorials that take a deeper dive into Kubernetes
           across all major cloud providers.
title: Next steps
h1: "Pulumi & Kubernetes: Next steps"
weight: 9
menu:
  clouds:
    parent: kubernetes-get-started
    identifier: kubernetes-next-steps

aliases:
- /docs/quickstart/kubernetes/next-steps/
- /docs/get-started/kubernetes/next-steps/
- /docs/clouds/kubernetes/get-started/next-steps/
---

Congrats! You've deployed your first project to Kubernetes with Pulumi. Here are some next steps, depending on your learning style.

## Try Pulumi ESC (Environments, Secrets, and Configuration)

[Pulumi ESC](/docs/esc/) is a centralized secrets management and orchestration service. It introduces the concepts of _environments_ --- managed collections of static and dynamic settings that you can use to configure any project, stack, application, or service, including with short-lived cloud credentials through OpenID Connect.

With Pulumi ESC you can:

- **Stop secret sprawl.** Pull and sync configuration and secrets with any secrets store – including HashiCorp Vault, AWS Secrets Manager, Azure Key Vault, GCP Secret Manager, 1Password, and more – and consume in any application, tool, or CI/CD platform.
- **Trust (and prove) your secrets are secure.** Every environment can be locked down with role-based access controls (RBAC) and versioned with all changes fully logged for auditing.
- **Ditch `.env` files.** No more storing secrets in plaintext on dev computers. Developers can easily access secrets via CLI, API, Kubernetes operator, the Pulumi Cloud UI, and in-code with Typescript/Javascript, Python, and Go SDKs.

{{< get-started-next-step path="/docs/esc/get-started" label="Learn more about Pulumi ESC" ref="gs-k8-esc" >}}

## Learn Pulumi

Dive into Learn Pulumi for a comprehensive walkthrough of key Pulumi concepts in the context of a real-life application.

{{< get-started-next-step path="/learn/pulumi-fundamentals" label="Learn Pulumi Fundamentals" ref="gs-k8s-learn" >}}

## How-to Guides

Explore our how-to guides if you're looking for examples of specific architectures or application stacks. These guides are available in all Pulumi languages and cover creating managed Kubernetes clusters across all major cloud providers ([AWS](/registry/packages/kubernetes/how-to-guides/eks/), [Azure](/registry/packages/kubernetes/how-to-guides/aks/), [Google Cloud](/registry/packages/kubernetes/how-to-guides/gke/) as well as deploying app workloads on running Kubernetes clusters ([WordPress Helm Chart](/registry/packages/kubernetes/how-to-guides/wordpress-chart/), [Stateless App Deployment](/registry/packages/kubernetes/how-to-guides/stateless-app/).

{{< get-started-next-step path="/registry/packages/kubernetes/how-to-guides" label="Explore How-to Guides" ref="gs-k8s-guides" >}}

## How Pulumi Works

Learn how Pulumi works from its architecture to key concepts, including [stacks](/docs/concepts/stack/), [state](/docs/concepts/state/), [configuration](/docs/concepts/config/), and [secrets](/docs/concepts/secrets/).

{{< get-started-next-step path="/docs/concepts/" label="Read Documentation" ref="gs-k8s-docs" >}}

## Blog Posts

Read through the latest blog posts about using Pulumi with Kubernetes.

{{< get-started-next-step path="/blog/tag/kubernetes" label="Read the Pulumi Blog" ref="gs-k8s-blog" >}}
