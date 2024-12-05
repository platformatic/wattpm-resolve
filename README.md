# wattpm-resolve

Demo repository of a watt application resolving the services from multiple respositories

## Usage

```bash
npm install
npm run resolve
npm run build
npm start
```

This will install the dependencies,
resolve the services from their git repositories,
build the application and start it.

It's possible to configure Watt to resolve one or more of the
services to a local directory instead of a git repository
by setting `PLT_NODE_PATH` or `PLT_NEXT_PATH` to the local directory.
of the responsive services.

## License

MIT
