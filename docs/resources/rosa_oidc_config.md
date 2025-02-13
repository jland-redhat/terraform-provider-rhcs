---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rhcs_rosa_oidc_config Resource - terraform-provider-rhcs"
subcategory: ""
description: |-
  Manages OIDC config
---

# rhcs_rosa_oidc_config (Resource)

Manages OIDC config



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `managed` (Boolean) Indicates whether it is a Red Hat managed or unmanaged (Customer hosted) OIDC configuration, for the cluster's OIDC provider.

### Optional

- `installer_role_arn` (String) AWS STS Role ARN for cluster install (with get-secrets permission in the attached policy)
- `issuer_url` (String) The bucket/issuer URL
- `secret_arn` (String) Indicates for unmanaged OIDC config, the secret ARN

### Read-Only

- `id` (String) The OIDC config ID
- `oidc_endpoint_url` (String) OIDC Endpoint URL
- `thumbprint` (String) SHA1-hash value of the root CA of the issuer URL


