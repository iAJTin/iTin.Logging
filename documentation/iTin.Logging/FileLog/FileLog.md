# FileLog constructor (1 of 3)

Initializes a new instance of the [`FileLog`](../FileLog.md) class.

```csharp
public FileLog(ILayout layout = null)
```

| parameter | description |
| --- | --- |
| layout | The layout to apply. |

## See Also

* interface [ILayout](../../iTin.Logging.ComponentModel/ILayout.md)
* class [FileLog](../FileLog.md)
* namespace [iTin.Logging](../../iTin.Logging.md)

---

# FileLog constructor (2 of 3)

Initializes a new instance of the [`FileLog`](../FileLog.md) class.

```csharp
public FileLog(string filename, ILayout layout = null)
```

| parameter | description |
| --- | --- |
| filename | A sting that specifies the log file name. |
| layout | The layout to apply. |

## See Also

* interface [ILayout](../../iTin.Logging.ComponentModel/ILayout.md)
* class [FileLog](../FileLog.md)
* namespace [iTin.Logging](../../iTin.Logging.md)

---

# FileLog constructor (3 of 3)

Initializes a new instance of the [`FileLog`](../FileLog.md) class.

```csharp
public FileLog(string filename, LogLevel level, ILayout layout = null, 
    FileLogSettings settings = null)
```

| parameter | description |
| --- | --- |
| filename | A string that specifies the log file name. |
| level | A [`LogLevel`](../../iTin.Logging.ComponentModel/LogLevel.md) enumeration value that specifies log verbosity. |
| layout | The layout to apply. |
| settings | the file log settings |

## See Also

* enum [LogLevel](../../iTin.Logging.ComponentModel/LogLevel.md)
* interface [ILayout](../../iTin.Logging.ComponentModel/ILayout.md)
* class [FileLogSettings](../../iTin.Logging.ComponentModel/FileLogSettings.md)
* class [FileLog](../FileLog.md)
* namespace [iTin.Logging](../../iTin.Logging.md)

<!-- DO NOT EDIT: generated by xmldocmd for iTin.Logging.dll -->
