# Railway Builder

Experimental [buildpacks.io](https://buildpacks.io) builder for Railway based off the [full Paketo](https://github.com/paketo-buildpacks/full-builder) builder.


## Included Buildpacks

- NodeJS
- Go
- PHP
- Ruby
- Java
- .NET
- Nginx
- HTTPD


## Creating Builder

View the [operator guide](https://buildpacks.io/docs/operator-guide/create-a-builder/) guide for detailed docs on creating a builder.


Create the builder image

```shell
pack builder create railway-builder --config ./builder.toml
```

Use the builder

```shell
pack build my-app --builder railway-builder --path path/to/app
```
