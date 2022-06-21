# ephemeral-db

Note: **This tool should not be used for creating secure production-ready
databases. This tool should only be used to create quick ephemeral/temporary
databases that you can use to test and easily debug applications with.**

## Usage

```
$ ephemeral-postgres -h
USAGE
    ephemeral-postgres [-f|--force] [--shell] IDENTIFIER
    ephemeral-postgres [-k|--kill] IDENTIFIER
    ephemeral-postgres [-h|--help]

DESCRIPTION
    Creates an emphemeral PostgreSQL database with
    Docker using IDENTIFIER as the root password, main
    username, their password, and also the primary
    database name. IDENTIFIER can't start or end
    with dashes, but overall can include alphanumberic
    characters, underscores, and dashes.
```

```
$ ephemeral-mysql -h
USAGE
    ephemeral-mysql [-f|--force] [--shell] IDENTIFIER
    ephemeral-mysql [-k|--kill] IDENTIFIER
    ephemeral-mysql [-h|--help]

DESCRIPTION
    Creates an emphemeral MySQL database with
    Docker using IDENTIFIER as the root password, main
    username, their password, and also the primary
    database name. IDENTIFIER can't start or end
    with dashes, but overall can include alphanumberic
    characters, underscores, and dashes.
```

## License

MIT