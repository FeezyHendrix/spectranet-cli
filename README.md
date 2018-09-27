# Spectranet CLI (In Development)

This is an unofficial CLI tool for accessing Spectranet user account data from its web portal.

## Installation

`yarn add spectranet-cli`

## Usage

- Get Basic Info

```bash
spectranet-cli
```

- Get Payments Info

```bash
spectranet-cli payments
    -f, --first <count>  view oldest payment info
    -l, --last <count>   view most recent payment info
```

To get first 3 payments, use `spectranet-cli payments -f 3` or `spectranet-cli payments --first 3`

- Get Data Usage Info

```bash
spectranet-cli usage
    -f, --from <from>  from date in DD-MM-YYYY format
    -t, --to <to>      to date in DD-MM-YYYY format
```

To specify the starting/from date as `26-09-2018`, use

```bash
spectranet-cli usage -f 26-09-2018
```

or

```bash
spectranet-cli usage --from 26-09-2018
```