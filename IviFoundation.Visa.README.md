# Package Info

|field   | value |
|---     |  ---  |
|Title   | VISA.NET Shared Components |
| Description |IVI Foundation VISA.NET Shared Components.  |
|Authors |  IVI Foundation |
|Owners  | IVI Foundation |
|Tags    | IVI VISA IVI-VISA-SharedComponents IVI-Foundation |

<!-- Following MD is the README.MD file -->
# IVI VISA.NET Shared Components

The VISA shared components are a common set of VISA components for developing multivendor software programs, including VISA I/O libraries and a variety of instrument drivers.

The components are "shared" because multiple VISA.NET vendor-specific implementations share the components. Because the components are shared and the behavior of each component is precisely described, the IVI Foundation supplies a standard implementation of each of them. In fact, the IVI Foundation implementation of each shared component must be used wherever the component is called for.

The VISA.NET Shared Components NuGet package includes the standard VISA.NET API and shared VISA.NET functionality such as the Global Resource Manager, Formatted IO and the Conflict Manager. This set of shared functionality is provided in a VISA.NET assembly. The functionality provided by the assembly is described in [VPP-4.3.6, VISA Implementation Specification for .NET](https://www.ivifoundation.org/downloads/VISA/vpp436_2025-01-13.pdf).
