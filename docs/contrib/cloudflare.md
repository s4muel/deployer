<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit contrib/cloudflare.php -->
<!-- Then run bin/docgen -->

# cloudflare

[Source](/contrib/cloudflare.php)


### Installing

Add to your _deploy.php_

```php
require 'contrib/cloudflare.php';
```

### Configuration

- `cloudflare` – array with configuration for cloudflare
    - `service_key` – Cloudflare Service Key. If this is not provided, use api_key and email.
    - `api_key` – Cloudflare API key generated on the "My Account" page.
    - `email` – Cloudflare Email address associated with your account.
    - `domain` – The domain you want to clear
    - `zone_id` – Cloudflare Zone ID (optional).

### Usage

Since the website should be built and some load is likely about to be applied to your server, this should be one of,
if not the, last tasks before cleanup





## Tasks

### deploy:cloudflare
[Source](https://github.com/deployphp/deployer/blob/master/contrib/cloudflare.php#L29)

Clearing Cloudflare Cache.




