---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rhcs_groups Data Source - terraform-provider-rhcs"
subcategory: ""
description: |-
  List of groups.
---

# rhcs_groups (Data Source)

List of groups.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `cluster` (String) Identifier of the cluster.

### Read-Only

- `items` (Attributes List) Content of the list. (see [below for nested schema](#nestedatt--items))

<a id="nestedatt--items"></a>
### Nested Schema for `items`

Read-Only:

- `id` (String) Unique identifier of the group. This is what should be used when referencing the group from other places, for example in the 'group' attribute of the user resource.
- `name` (String) Short name of the group for example 'dedicated-admins'.


