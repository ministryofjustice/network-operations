

# Ministry of Justice Network Operations team repository
[![repo standards badge](https://img.shields.io/badge/dynamic/json?color=blue&style=for-the-badge&logo=github&label=MoJ%20Compliant&query=%24.data%5B%3F%28%40.name%20%3D%3D%20%22network-operations%22%29%5D.status&url=https%3A%2F%2Foperations-engineering-reports.cloud-platform.service.justice.gov.uk%2Fgithub_repositories)](https://operations-engineering-reports.cloud-platform.service.justice.gov.uk/github_repositories#network-operations "Link to report")

## About this Repository

This is the Ministry of Justice [Network Operations teams](https://ministryofjustice.github.io/network-operations) public repository for documentation and team information. Network Operations are part of [Technology Operations](https://ministryofjustice.github.io/technology-operations/#technology-operations).

### Our repositories

### AWS Transit Gateway
| Name | Description |
|-|-|
| [MoJO Transit Gateway Configuration](https://github.com/ministryofjustice/deployment-tgw) | This repository contains the Terraform code to deploy the AWS Transit Gateway (TGW) for connectivity between the various VPCs in the Dev, Pre-Prod and Production accounts. This repository also contains the relevant VPC and VPN attachments to other environments within the MoJ estate.|
| [MoJO Transit Gateway Terraform Module](https://github.com/ministryofjustice/terraform-aws-tgw) | Terraform module for TGW and TGW route table creation |
| [MoJ Transit Gateway](https://github.com/ministryofjustice/transit-gateways) | AWS transit gateway configuration that is now managed by TechOps. This was previously managed by Cloud Platform. |

### Palo Alto
| Name | Description |
|-|-|
|  [External Dynamic List](https://github.com/ministryofjustice/staff-external-dynamic-list) | External Dynamic List for Palo Alto endpoints |
| [GlobalProtect FW EC2 Deployment](https://github.com/ministryofjustice/deployment-GlobalProtect) | GlobalProtect firewall deployment |
| [GlobalProtect ASG Deployment](https://github.com/ministryofjustice/deployment-GlobalProtect-ASG) | GlobalProtect Autoscale Deployment |
| [GlobalProtect lambda functions](https://github.com/ministryofjustice/terraform-aws-step_function_globalprotect) | GlobalProtect lambda functions |
| [Panorama Configuration](https://github.com/ministryofjustice/terraform-panorama-config) | Panorama Config written in Terraform |
| [Public Services Network](https://github.com/ministryofjustice/deployment-PSN) | Public Services Network connection in AWS, connected via Lumen (previously CenturyLink) |

### Shared Services
| Name | Description |
|-|-|
| [Shared services infrastructure](https://github.com/ministryofjustice/staff-device-shared-services-infrastructure) | Creates infrastructure in the shared services account, including continuous integration and delivery pipelines for the Palo Alto infrastructure and MoJO Transit Gateway |

## About this Website

This repository is published via Github Pages [here](https://ministryofjustice.github.io/network-operations/#network-operations)

To update, edit files in [this directory](https://github.com/ministryofjustice/network-operations/tree/main/source).

Filenames must be `[something].html.md.erb`
