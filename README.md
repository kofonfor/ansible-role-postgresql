# PostgreSQL role

## Variables

- postgres_version: tested on 9.3 and 9.4 only
- postgres_enable_conf: if enabled, creates /etc/postgresql/{{ postgres_version }}/main/conf.d directory and includes it in /etc/postgresql/{{ postgres_version }}/main/postgresql.conf.
