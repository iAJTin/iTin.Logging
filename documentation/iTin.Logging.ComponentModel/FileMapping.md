# FileMapping class

Defines mappings for [`FileLog`](../iTin.Logging/FileLog.md).

```csharp
public class FileMapping
```

## Public Members

| name | description |
| --- | --- |
| [FileMapping](FileMapping/FileMapping.md)() | The default constructor. |
| static readonly [DefaultDebugMapping](FileMapping/DefaultDebugMapping.md) | Returns new instance of [`FileMapping`](./FileMapping.md) configured for Debug log level. |
| static readonly [DefaultErrorMapping](FileMapping/DefaultErrorMapping.md) | Returns new instance of [`FileMapping`](./FileMapping.md) configured for Error log level. |
| static readonly [DefaultFatalMapping](FileMapping/DefaultFatalMapping.md) | Returns new instance of [`FileMapping`](./FileMapping.md) configured for Fatal log level. |
| static readonly [DefaultInfoMapping](FileMapping/DefaultInfoMapping.md) | Returns new instance of [`FileMapping`](./FileMapping.md) configured for Info log level. |
| static readonly [DefaultWarnMapping](FileMapping/DefaultWarnMapping.md) | Returns new instance of [`FileMapping`](./FileMapping.md) configured for Warn log level. |
| static readonly [NotFoundMapping](FileMapping/NotFoundMapping.md) | Returns new empty instance of [`FileMapping`](./FileMapping.md) that indicates not found. |
| [Level](FileMapping/Level.md) { get; set; } | Gets or sets the log level. |
| [Pattern](FileMapping/Pattern.md) { get; set; } | Gets or set the pattern lines for this mapping . |
| override [ToString](FileMapping/ToString.md)() | Returns a String that represents this instance. |

## See Also

* namespace [iTin.Logging.ComponentModel](../iTin.Logging.md)

<!-- DO NOT EDIT: generated by xmldocmd for iTin.Logging.dll -->
