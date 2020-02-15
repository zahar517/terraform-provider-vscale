Terraform Provider
==================

- Website: https://www.terraform.io
- [![Gitter chat](https://badges.gitter.im/hashicorp-terraform/Lobby.png)](https://gitter.im/hashicorp-terraform/Lobby)
- Mailing list: [Google Groups](http://groups.google.com/group/terraform-tool)

<img src="https://cdn.rawgit.com/hashicorp/terraform-website/master/content/source/assets/images/logo-hashicorp.svg" width="600px">

Requirements
------------

-	[Terraform](https://www.terraform.io/downloads.html) > 0.10.x
-	[Go](https://golang.org/doc/install) > 1.8 (to build the provider plugin)

Building The Provider
---------------------

Clone repository

```sh
$ git clone git@github.com:zahar517/terraform-provider-vscale.git
```

Enter the provider directory and build the provider

```sh
$ cd terraform-provider-vscale
$ go mod init github.com/zahar517/terraform-provider-vscale
$ go build
```

Installing the provider
----------------------

```sh
$ go install
```
