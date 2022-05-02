[![NuGet Gallery](https://img.shields.io/badge/NuGet%20Gallery-enbrea.guidfactory-blue.svg)](https://www.nuget.org/packages/Enbrea.GuidFactory/)
![GitHub](https://img.shields.io/github/license/enbrea/enbrea.guidfactory)

# ENBREA GuidFactory

A .NET library for for generating deterministic GUID values. See [RFC 4122](https://www.ietf.org/rfc/rfc4122.txt) for algorithm details. 

+ Supports .NET Core 3.1, .NET 5 and .NET 6
+ This library is based on existing code from the following [blog article](https://faithlife.codes/blog/2011/04/generating_a_deterministic_guid/).

## Installation

```
dotnet add package Enbrea.GuidFactory
```

## Example

``` csharp
Guid guid = GuidGenerator.Create(GuidGenerator.DnsNamespace, "www.enbrea.org");
```

## Can I help?

Yes, that would be much appreciated. The best way to help is to post a response via the Issue Tracker and/or submit a Pull Request.
