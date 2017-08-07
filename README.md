# azure-java-jaxrs-deployment

This is the deployment repository for the corresponding "azure-java-jaxrs" repo.

The "azure-java-jaxrs" repo contains the Java & JAX-RS source code, and a 
build process which creates the "webapps/ROOT.WAR" file in THIS repo.

The reason for this repository design is to deploy ONLY the war file via
Azure deployments from GitHub, rather than deploy all of the source code PLUS
the war file.

The following lists the entire contents of this deployment repo:

```
$ git ls-files
.gitignore
README.md
webapps/ROOT.WAR
```

See file "build.sh" in the corresponding "azure-java-jaxrs" repo.
