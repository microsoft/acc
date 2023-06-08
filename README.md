# Apps Command Center / Enterprise Apps Accelerator

Developed by the Microsoft GPS LATAM Team, the ACC Solution Accelerator provides a set of templates to help you accelerate your deployment process. The ACC Solution Accelerator is designed to help you build solutions that are secure, scalable, and reliable based on Microsoft WAF Principals.

### Make your choice

```mermaid
flowchart TD
    A[Start] --> B{Windows OS};
    B -- Yes --> C{Windows App, does need Access to Console?};
    B -- No --> D{Linux App, does need Access to Console?};
    C -- Yes --> E[Enjoy Azure VM for Windows];
    C -- No --> F{Code in Repo?};
    D -- Yes --> G[Enjoy Azure VM for Linux];
    D -- No --> H{Code in Repo?};
    F -- Yes --> I[Enjoy App Service for Windows]
    F -- No --> J[Enjoy Azure VM for Windows];
    H -- No --> K[Enjoy Azure VM for Linux];
    H -- Yes --> L{Need support Containers?};
    L -- Yes --> M[Enjoy Azure Container Apps];
    L -- No --> N[Enjoy App Service for Linux];
```
### This solution is open source. You can adapt the templates to create an architecture that meets your needs.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
