# php-skeleton

## XDebug configurations

### VSCode

```json
{
    "name": "Listen for XDebug",
    "type": "php",
    "request": "launch",
    "port": 9040,
    "pathMappings": {
        "/var/www/html": "${workspaceRoot}"
    }
}
```