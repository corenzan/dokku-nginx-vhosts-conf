# dokku-nginx-vhost-conf

> Dokku plugin for managing Nginx configuration.

## About

...

## Requirements

- dokku 1.17.0+
- nginx 1.14.0+

## Usage

You can always run `dokku nginx-conf:help` to get a summary of options and commands in your shell.

<details>
    <summary><code>nginx-conf</code>, <code>nginx-conf:report</code></summary>
    <p>Report about current nginx configuration.</p>
</details>

<details>
    <summary><code>nginx-conf:install  _package_</code></summary>
    <p>Back the current Nginx configuration up and replace with the contents from the package. Accepts either a path or URL to a ZIP file.</p>
</details>

<details>
    <summary><code>nginx-conf:restore</code></summary>
    <p>Discard current configuration and restore last backup.</p>
</details>

<details>
    <summary><code>nginx-conf:install-template  _template_</code></summary>
    <p>Set a custom application configuration template. Accepts either a path or URL to the template file.</p>
</details>

<details>
    <summary><code>nginx-conf:restore-template</code></summary>
    <p>Clear custom application configuration.</p>
</details>

## Legal

The MIT License © 2019 Arthur Corenzan
