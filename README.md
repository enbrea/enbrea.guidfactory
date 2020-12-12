# ENBREA GUID FACTORY

This .NET Core library provides a factory class for generating deterministic GUID values. See [RFC 4122](https://www.ietf.org/rfc/rfc4122.txt) for algorithm details. This library is based on existing code from the following [blog article](https://faithlife.codes/blog/2011/04/generating_a_deterministic_guid/).

## Installation

```
dotnet add package Enbrea.GuidFactory
```

### Example

``` csharp
Guid guid = GuidFactory.Create(GuidFactory.DnsNamespace, "guid.enbrea.org");
```

## Can I help?

Yes, that would be much appreciated. The best way to help is to post a response via the Issue Tracker and/or submit a Pull Request.

## Code of Conduct

The [STÜBER SYSTEMS Code of Conduct](https://www.stueber.co.uk/code-of-conduct.php) was adopted in this project.
