# Temporary neutron-api test fixture for Arista

## Publishing to the store

```
$ charm login
$ charm push . cs:~aurelien-lourot/neutron-api-arista-test-fixture
url: cs:~aurelien-lourot/neutron-api-arista-test-fixture-0
channel: unpublished
$ charm release cs:~aurelien-lourot/neutron-api-arista-test-fixture-0
url: cs:~aurelien-lourot/neutron-api-arista-test-fixture-0
channel: stable
warning: bugs-url and homepage are not set.  See set command.
$ charm set cs:~aurelien-lourot/neutron-api-arista-test-fixture \
    homepage=https://github.com/AurelienLourot/charm-neutron-api/tree/arista
$ charm grant cs:~aurelien-lourot/neutron-api-arista-test-fixture-0 \
    --acl read everyone
```

The published charm can be found
[here](https://jaas.ai/u/aurelien-lourot/neutron-api-arista-test-fixture).
