# WARNING
These example v1 templates are from https://github.com/F5Networks/f5-azure-arm-templates. The repository was archived (read-only) in Dec-2023. While still functional with newer BIG-IP software versions, the v1 templates are no longer fully supported by F5. These customized examples are provided AS-IS without warranty.


# Azure deploy buttons

Use the appropriate button below to deploy:

- **standalone-3nic-existing-byol** (bring your own license): This allows you to use an existing BIG-IP license.

  [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ff5jason%2Ff5-arm-v1-custom%2Frefs%2Fheads%2Fmain%2Fstandalone-3nic-existing-byol%2Fazuredeploy.json)


- **standalone-1nic-existing-byol** (bring your own license): This allows you to use an existing BIG-IP license.
  
  [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ff5jason%2Ff5-arm-v1-custom%2Frefs%2Fheads%2Fmain%2Fstandalone-1nic-existing-byol%2Fazuredeploy.json)


# Change Log
2026-04-07: Change BIG-IP Version field to pick list format with options for 17.1, 17.5, 21.0

2026-02-12: Added updated template v17-standalone-3nic-existing-byol - defaults to BIG-IP 17.1.3.x

2026-02-11: Updated template v17-standalone-1nic-existing-byol - defaults to BIG-IP 17.1.3.x
