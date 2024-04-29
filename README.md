Export/Import Realm through cmd:
[url]( https://www.keycloak.org/server/importExport)

- go inside container `keycloak_web` 
- /opt/keycloak/bin/kc.sh export --help
- /opt/keycloak/bin/kc.sh export --file myFile.json

- /opt/keycloak/bin/kc.sh import --file myFile.json