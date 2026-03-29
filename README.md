# Moodle on Azure - Fixed Template

This is a fixed version of the [Azure/Moodle](https://github.com/Azure/Moodle) ARM template with the public IP SKU updated from `Basic` to `Standard` (with `Regional` tier), since Azure no longer supports the Basic SKU for `Microsoft.Network/publicIPAddresses`.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbijns%2Fmoodle-template%2Fmain%2Fazuredeploy-minimal.json)
