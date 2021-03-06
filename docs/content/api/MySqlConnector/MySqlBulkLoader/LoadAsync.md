---
title: MySqlBulkLoader.LoadAsync methods
---

# MySqlBulkLoader.LoadAsync method (1 of 2)

Asynchronously loads all data in the source file or stream into the destination table.

```csharp
public Task<int> LoadAsync()
```

## Return Value

A Task that will be completed with the number of rows inserted.

## See Also

* class [MySqlBulkLoader](../../MySqlBulkLoaderType/)
* namespace [MySqlConnector](../../MySqlBulkLoaderType/)
* assembly [MySqlConnector](../../../MySqlConnectorAssembly/)

---

# MySqlBulkLoader.LoadAsync method (2 of 2)

Asynchronously loads all data in the source file or stream into the destination table.

```csharp
public Task<int> LoadAsync(CancellationToken cancellationToken)
```

| parameter | description |
| --- | --- |
| cancellationToken | A token to cancel the asynchronous operation. |

## Return Value

A Task that will be completed with the number of rows inserted.

## See Also

* class [MySqlBulkLoader](../../MySqlBulkLoaderType/)
* namespace [MySqlConnector](../../MySqlBulkLoaderType/)
* assembly [MySqlConnector](../../../MySqlConnectorAssembly/)

<!-- DO NOT EDIT: generated by xmldocmd for MySqlConnector.dll -->
