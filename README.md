# vault-plugin-list
List fo plugin for Hashicorp Vault


# Plugins
- [vault-acme](https://github.com/remilapeyre/vault-acme) Vault ACME is a Vault secret engine that allow users and application to retrieve TLS certificates validated by an ACME provider like Let's Encrypt without having to give each applications permission to modify DNS and using Vault's audit and policy systems.
- [vault-plugin-secrets-artifactory](https://github.com/jsok/vault-plugin-secrets-artifactory) This is a backend plugin to be used with Hashicorp Vault. It uses the Artifactory REST API to dynamically issue Access Tokens.
- [vault-plugin-auth-chefnode](https://github.com/nhuff/vault-plugin-auth-chefnode) - The "chef-node" auth backend allows Nodes registered with a Chef server to authenticate using their private keys.
- [vault-auth-plugin-chef](https://github.com/criteo/vault-auth-plugin-chef)- Vault Authentication plugin for Chef.
- [vault-auth-chef](https://github.com/svagner/vault-auth-chef) - Chef authorization plugin for Hashicorp Vault.
- [kubernetes-flexvolume-vault-plugin](https://github.com/fcantournet/kubernetes-flexvolume-vault-plugin) - A kubernetes flexvolume plugin that injects vault tokens at pod creation
- [vault-secrets-gen](https://github.com/sethvargo/vault-secrets-gen) - A Vault secrets plugin for generating high entropy passwords and passphrases.
- [vault-auth-slack](https://github.com/sethvargo/vault-auth-slack) - The Vault Auth Slack method is a Vault auth method plugin for authenticating users via Slack. The plugin can run in multiple different "modes" depending on your desired user workflow and risk tolerance. This is both a real custom Vault auth method, and an example of how to build, install, and maintain your own Vault auth plugin.
- [vault-auth-file](https://github.com/gites/vault-auth-file) - HashiCorp Vault authentication plugin for authenticating via Unix password like file.
- [vault-plugin-secrets-webhook](https://github.com/idcmp/vault-plugin-secrets-webhook) - Use Vault ACLs to control access to other REST APIs.
- [vault-plugin-secrets-github](https://github.com/martinbaillie/vault-plugin-secrets-github) - A Vault secrets plugin for creating ephemeral, finely-scoped GitHub access tokens.
- [vault-plugin-secrets-gitlab](https://github.com/splunk/vault-plugin-secrets-gitlab) - his is a backend plugin to be used with Vault. This plugin generates Gitlab Project Access Tokens
- [vault-plugin-secrets-kafka](https://github.com/Mongey/vault-plugin-secrets-kafka) A Vault plugin for generating credentials for Apache Kafka clients. Generates a dynamic username and ACL that can be used to create a uniq SSL certificate for a Kafka client.
- [vault-plugin-auth-vsphere](https://github.com/martezr/vault-plugin-auth-vsphere) This is a standalone backend plugin for use with HashiCorp Vault. This plugin allows for VMware vSphere virtual machines (VMs) to authenticate with Vault. This plugin requires the vAuth platform to be deployed and configured.
- [argocd-vault-plugin](https://github.com/legalzoom/argocd-vault-plugin) Vault ArgoCD Secret plugin is a secrets engine plugin for HashiCorp Vault that allows for the generation and usage of short-term credentials for ArgoCD.
- [vault-plugin-secrets-jenkins](https://github.com/circa10a/vault-plugin-secrets-jenkins) This is a backend plugin to be used with Hashicorp Vault. This plugin generates ephemeral Jenkins Users and API tokens.
- [vault-plugin-auth-openstack](https://github.com/summerwind/vault-plugin-auth-openstack) This is a standalone backend plugin for use with Hashicorp Vault. This plugin allows for OpenStack instances to authenticate with Vault.
- [vault-plugin-splunk](https://github.com/splunk/vault-plugin-splunk) A Hashicorp Vault plugin that aims to securely manage Splunk admin accounts, including secrets rotation for compliance purposes.
- [vault-plugin-secrets-ccp](https://github.com/LiviusNL/vault-plugin-secrets-ccp) This repository contains the source code for a Vault plugin used to retrieve secrets from the CyberArk Enterprise Password Vault (EVP) using the CyberArk Central Credentials Provider (CCP).



# Ops
- https://github.com/hootsuite/vault-ctrl-tool - Outsource authentication, secrets fetching, and lease management for services.
- https://github.com/starkandwayne/safe - A Vault CLI.
- https://github.com/avantoss/vault-infra -  Packer and Terraform to create a fully automated and HA Vault deployment.
- https://github.com/bincyber/pkictl - CLI tool for declaratively configuring and provisioning PKI secrets in HashiCorp Vault via Yaml.
- https://gitlab.com/msvechla/vaultbot - A certbot like tool to provision certificates from a Vault managed CA.
- https://github.com/seatgeek/hashi-helper - A tool meant to enable Disaster Recovery and Configuration Management for Consul and Vault clusters, by exposing configuration via a simple to use and share hcl format.
- https://github.com/UKHomeOffice/vaultctl - Vaultctl is a command line utilty for provisioning a Hashicorp's Vault from configuration files. Essentially it was written so we could source control our users, policies, backends and secrets, synchronize the vault against them and rebuild on-demand if required.
- https://github.com/cloudwatt/vault-sync - Vault-sync is a command line utilty for provisioning a Hashicorp's Vault from configuration files. Essentially it was written so we could source control our users, policies, backends and secrets, synchronize the vault against them and rebuild on-demand if required.
- https://github.com/jaxxstorm/unseal - **[deprecated]** A command line tool to unseal multiple Hashicorp Vault servers quickly.
- https://github.com/jaxxstorm/hookpick - A tool to manage some operational concepts of Hashicorp Vault.
- https://github.com/paywithcurl/vault-update - Tool for updating a single key in vaullt secret.
- https://github.com/martinbaillie/vaultsign - Sign and verify `git` commits and tags using Vault.
- https://github.com/spectralops/teller - secrets management tool for developers, integrate Vault with any other secret and key store

# Users
- https://github.com/Lingrino/vaku - Vaku is a CLI and Go API that extends the official Vault CLI and API with useful high-level functions such as the ability to copy, move, and search vault paths and folders.
- https://github.com/Mykolaichenko/vaulter - Vaulter extends default Hashicorp Vault client, implements additional methods like list all backend path, dynamically read value, search in all backend and so on.
- https://github.com/apptio/breakglass - Breakglass is a tool that will make API calls to Hashicorp Vault servers and then retrieve credentials for you. It's designed to ease the process of getting elevated login credentials for a variety of servers. It currently supports MySQL servers and SSH Command line access.
- https://github.com/ilijamt/vht/ - vht extends the functionality of Vault and adds searching, tree and recursive deletes.

# K8s
*Note: There is now official plugin for k8s: https://www.vaultproject.io/docs/auth/kubernetes.html*
- https://github.com/keyparty/vault-init - K8s Init Container for Vault Token Generation and Retrieval.
- https://github.com/kelseyhightower/vault-controller - The Vault Controller automates the creation of Vault tokens for Kubernetes Pods. This repo includes a set of hands-on tutorials and example programs you can use to try out the Vault Controller.
- https://github.com/Boostport/kubernetes-vault - The Kubernetes-Vault project allows pods to automatically receive a Vault token using Vault's AppRole auth backend.
- https://github.com/sethvargo/vault-kubernetes-authenticator - An app and container for authenticating services to HashiCorp Vault's via the Kubernetes auth method.
- https://github.com/UKHomeOffice/vault-sidekick - Vault Sidekick is a add-on container which can be used as a generic entry-point for interacting with Hashicorp Vault service, retrieving secrets (both static and dynamic) and PKI certs. The sidekick will take care of renewal's and extension of leases for you and renew the credentials in the specified format for you.
- https://github.com/banzaicloud/bank-vaults - A Vault swiss-army knife: Go client with automatic token renewal, Kubernetes support, dynamic secrets, multiple unseal options and more. A CLI tool to init, unseal and configure Vault (auth methods, secret engines). A K8s operator. 
- https://github.com/uswitch/vault-webhook - Kubernetes Mutating Webhook to inject Vault-Creds Sidecar into pods.
- https://github.com/uswitch/vault-creds - Sidecar container for requesting dynamic Vault database secrets.
- https://github.com/cruise-automation/daytona - This is intended to be a lighter, alternative, implementation of the Vault client CLI primarily for services and containers. Its core features are the ability to automate authentication, fetching of secrets, and automated token renewal. Supports K8s, AWS IAM and GCP IAM auth methods.
- https://github.com/postfinance/vault-kubernetes - Authenticate services to @hashicorp Vault via the Kubernetes auth method.
- https://github.com/postfinance/kubectl-vault_sync - Kubernetes plugin to synchronize secrets from vault as kubernetes secrets.
- https://github.com/ricoberger/vault-secrets-operator - Create Kubernetes secrets from Vault for a secure GitOps based workflow.


# UI
- https://github.com/djenriquez/vault-ui Vault-UI ??? A beautiful UI to manage your Vault, written in React.
- https://github.com/Caiyeon/goldfish - A HashiCorp Vault UI panel written with VueJS and Vault native Go API.
- https://github.com/nyxcharon/vault-ui -  A webapp for working with Hashicorp's Vault.
- https://github.com/adobe/cryptr - Cryptr is a GUI for Hashicorp's Vault.


# Other
- https://github.com/asteris-llc/vaultfs - VaultFS mounts arbitrary Vault prefixes in a FUSE filesystem. It also provides a Docker volume plugin to the do the same for your containers.
- https://github.com/gites/vault-cert-helper - 
Vault-cert-helper is a simple tool intended to help you provision certificates from on-premises Vault to services running in AWS and GCE (or any other S3 compatible cloud).
- https://github.com/channable/vaultenv - Launch processes with Vault secrets in the environment.
- https://github.com/joemiller/vault-token-helper - Vault Token Helper for macOS, Linux and Windows with support for secure token storage and multiple Vault instances
