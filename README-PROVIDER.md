# Xenorchestra Resource Provider

The Xenorchestra Resource Provider lets you manage [Xenorchestra](http://example.com) resources.

## Installing

This package is available for several languages/platforms:

### Node.js (JavaScript/TypeScript)

To use from JavaScript or TypeScript in Node.js, install using either `npm`:

```bash
npm install @pulumi/foo
```

or `yarn`:

```bash
yarn add @pulumi/foo
```

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

## Reference

For detailed reference documentation, please visit [the Pulumi registry](https://www.pulumi.com/registry/packages/xenorchestra/api-docs/).
