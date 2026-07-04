# CJW Exponential Media Site Data

Installation data package for the [CJW Exponential Platform Nexus](https://github.com/se7enxweb/exponential-platform-nexus) starter project.

Used by the `cjw-exponential-media` installer type:

```shell
php bin/console ezplatform:install cjw-exponential-media
```

## Package Structure

```
cjw-exponential-media/
  data.sql        # Full content data (schema + content)
  storage/        # Binary file storage placeholder
schema/
  schema.sql      # Database schema only
```

## License

GPL-2.0-only — see [LICENSE.md](LICENSE.md).
