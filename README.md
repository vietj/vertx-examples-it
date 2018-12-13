## Notes

```
mvn clean install -Pprepare '-P!it'
mvn clean verify install --fail-never -U -Pstaging

# On some linux boxes the interface for clustering needs to be specified
mvn clean verify install --fail-never -U -Pstaging -Dinterface=127.0.0.1
```
