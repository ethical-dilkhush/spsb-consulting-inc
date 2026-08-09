# spsb-consulting-inc

WordPress-based consulting site for SPSB Consulting Inc., maintained as a portable project tree for review, deployment, and local development.

## About

This repository preserves the public-facing WordPress application and configuration templates for the SPSB Consulting Inc. site. It includes the WordPress source tree, sample Nginx/PHP/MySQL configuration templates, and an exported content archive.

## Setup

1. Serve the `app/public` directory with a PHP-enabled web server.
2. Import the SQL snapshot from `app/sql/local.sql` into MySQL.
3. Configure Nginx/PHP using the templates in `conf/`.
4. Place the application document root at `app/public`.

## Usage

- Admin and site assets are served from the standard WordPress paths under `app/public`.
- Review exported content and site structure using the included WordPress eXtended RSS archive.
- Use the configuration templates as a starting point for local or staging environments.

## Repository

Source, issues, and updates: https://github.com/ethical-dilkhush/spsb-consulting-inc
