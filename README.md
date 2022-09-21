# Xenorchestra Resource Provider

The xenorchestra Resource Provider lets you manage [xenorchestra](http://example.com) resources.

## Installing

This package is available for several languages/platforms:

### Python

To use from Python, install using `pip`:

```bash
pip install pulumi_xenorchestra
```

### Go

To use from Go, use `go get` to grab the latest version of the library:

```bash
go get github.com/pulumi/pulumi-xenorchestra/sdk/go/...
```

### .NET

To use from .NET, install using `dotnet add package`:

```bash
dotnet add package Pulumi.Xenorchestra
```

## Configuration

The following configuration points are available for the `xenorchestra` provider:

- `xenorchestra:url` (environment: `XOA_URL`) - Hostname of the xoa router
- `xenorchestra:username` (environment: `XOA_USER`) - User account for xoa api
- `xenorchestra:password` (environment: `XOA_PASSWORD`) - Password for xoa api
- `xenorchestra:insecure` (environment: `XOA_INSECURE`) - Whether SSL should be verified or not