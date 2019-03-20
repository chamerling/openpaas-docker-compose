# openpaas-docker-compose

Some docker compose files for OpenPaaS

## HOWTO

Each yml file contains a single version of OpenPaaS with required components. To run a version, just do:

```
PROVISION=true docker-compose -f ./1.4.3.yml up
```

Where:

- The file name is the version you are launching
- `PROVISION` is just required on first launch
