# dokku-nginx-vhosts-conf

> dokku plugin for managing nginx configuration.

## Requirements

- dokku 1.17.0+
- nginx 1.14.0+

## Install

```shell
sudo dokku plugin:install https://github.com/corenzan/dokku-nginx-vhosts-conf.git
```

⚠️ If you use the `--name ...` flag you must pick a name that comes below `nginx-vhosts`, otherwise the plugin won't be able to undo dokku edits to nginx configuration files.

## Usage

Once it's installed use `nginx-conf:install repository-url` to install nginx configuration from a Git repository. The plugin will also look for a `dokku/nginx.conf.sigil` inside your nginx configuration and apply it to all future application builds.

<details>
    <summary><code>nginx-conf:help</code></summary>
    <p>Display usage details.</p>
</details>

<details>
    <summary><code>nginx-conf:install repository-url</code></summary>
    <p>Save nginx config files and clone given repository in its place.</p>
</details>

<details>
    <summary><code>nginx-conf:report</code></summary>
    <p>🚧️ Report about current nginx configuration.</p>
</details>

<details>
    <summary><code>nginx-conf:restore</code></summary>
    <p>🚧️ Restore original nginx config files.</p>
</details>

<details>
    <summary><code>nginx-conf:update</code></summary>
    <p>🚧️ Update currently installed config.</p>
</details>

## Legal

The MIT License © 2019 Arthur Corenzan
