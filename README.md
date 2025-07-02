# S(ssh)A(nsible)

A tool for quickly connecting to hosts based on ssh inventory

## Config

Example:

```
{
    "hosts": "~/ansible/hosts"
}
```

## Usage

Register shell extension: `eval "$(register-python-argcomplete sa)"`

Connect to host: `sa gitlab-gitaly-01`
