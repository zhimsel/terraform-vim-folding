# Folding syntax for Terraform files

## Installation

If you haven't already, make sure `.tf` files are set to the `terraform` filetype

```
au BufRead,BufNewFile *.tf setlocal filetype=terraform
```

Then, add via your favorite plugin manager. For instance, if you use vim-plug:

```
Plug 'zhimsel/terraform-vim-folding', { 'for': 'terraform' }
```

![screenshot](https://cloud.githubusercontent.com/assets/156436/12099980/ff94a0b4-b2f9-11e5-997a-4aed67f4bb51.png)
