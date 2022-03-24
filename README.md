# aap-kafka-manager
Kafka manager for aap.

Fork av: https://github.com/navikt/kafka-manager

## Legg til topic
1. Legg til topic config nederst i [nais.yml](nais.yml)
2. Legg til denne appen i avien topic.yml ACL definisjon <br>
```yaml
- team: aap
  application: aap-kafka-manager
  access: read
```

## Legg til bruker
Folk i AD Gruppa `aap`: [Azure AD](http://mygroups.microsoft.com/)
