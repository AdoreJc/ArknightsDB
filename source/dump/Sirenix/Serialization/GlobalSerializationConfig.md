# GlobalSerializationConfig

**Namespace:** `Sirenix.Serialization`


## Fields

- `Boolean HideSerializationCautionaryMessage`

- `Boolean HidePrefabCautionaryMessage`

- `Boolean HideOdinSerializeAttributeWarningMessages`

- `Boolean HideNonSerializedShowInInspectorWarningMessages`

- `DataFormat buildSerializationFormat`

- `DataFormat editorSerializationFormat`

- `LoggingPolicy loggingPolicy`

- `ErrorHandlingPolicy errorHandlingPolicy`


## Properties

- `ILogger Logger`

- `DataFormat EditorSerializationFormat`

- `DataFormat BuildSerializationFormat`

- `LoggingPolicy LoggingPolicy`

- `ErrorHandlingPolicy ErrorHandlingPolicy`


## Methods

- `ILogger get_Logger()`

- `DataFormat get_EditorSerializationFormat()`

- `Void set_EditorSerializationFormat(DataFormat)`

- `DataFormat get_BuildSerializationFormat()`

- `Void set_BuildSerializationFormat(DataFormat)`

- `LoggingPolicy get_LoggingPolicy()`

- `Void set_LoggingPolicy(LoggingPolicy)`

- `ErrorHandlingPolicy get_ErrorHandlingPolicy()`

- `Void set_ErrorHandlingPolicy(ErrorHandlingPolicy)`

- `Void OnInspectorGUI()`


## Dump
```C#
// Dll : Sirenix.Serialization.Config.dll
// Namespace : Sirenix.Serialization
public class GlobalSerializationConfig : GlobalConfig`1
{
	public const String ODIN_SERIALIZATION_CAUTIONARY_WARNING_TEXT; // 0x0
	public const String ODIN_PREFAB_CAUTIONARY_WARNING_TEXT; // 0x0
	public const String ODIN_SERIALIZATION_CAUTIONARY_WARNING_BUTTON_TEXT; // 0x0
	public const String ODIN_PREFAB_CAUTIONARY_WARNING_BUTTON_TEXT; // 0x0
	private static readonly DataFormat[] BuildFormats; // 0x0
	public Boolean HideSerializationCautionaryMessage; // 0x18
	public Boolean HidePrefabCautionaryMessage; // 0x19
	public Boolean HideOdinSerializeAttributeWarningMessages; // 0x1a
	public Boolean HideNonSerializedShowInInspectorWarningMessages; // 0x1b
	private DataFormat buildSerializationFormat; // 0x1c
	private DataFormat editorSerializationFormat; // 0x20
	private LoggingPolicy loggingPolicy; // 0x24
	private ErrorHandlingPolicy errorHandlingPolicy; // 0x28

	public ILogger Logger { get; }
	public DataFormat EditorSerializationFormat { get; set; }
	public DataFormat BuildSerializationFormat { get; set; }
	public LoggingPolicy LoggingPolicy { get; set; }
	public ErrorHandlingPolicy ErrorHandlingPolicy { get; set; }

	// RVA: 0x61bee1c VA: 0x75987d6e1c
	public ILogger get_Logger() { }
	// RVA: 0x61bee68 VA: 0x75987d6e68
	public DataFormat get_EditorSerializationFormat() { }
	// RVA: 0x61bee70 VA: 0x75987d6e70
	public Void set_EditorSerializationFormat(DataFormat value) { }
	// RVA: 0x61bee78 VA: 0x75987d6e78
	public DataFormat get_BuildSerializationFormat() { }
	// RVA: 0x61bee80 VA: 0x75987d6e80
	public Void set_BuildSerializationFormat(DataFormat value) { }
	// RVA: 0x61bee88 VA: 0x75987d6e88
	public LoggingPolicy get_LoggingPolicy() { }
	// RVA: 0x61bee90 VA: 0x75987d6e90
	public Void set_LoggingPolicy(LoggingPolicy value) { }
	// RVA: 0x61bee98 VA: 0x75987d6e98
	public ErrorHandlingPolicy get_ErrorHandlingPolicy() { }
	// RVA: 0x61beea0 VA: 0x75987d6ea0
	public Void set_ErrorHandlingPolicy(ErrorHandlingPolicy value) { }
	// RVA: 0x61beea8 VA: 0x75987d6ea8
	private Void OnInspectorGUI() { }
	// RVA: 0x61bf300 VA: 0x75987d7300
	public Void .ctor() { }
	// RVA: 0x61bf350 VA: 0x75987d7350
	private static Void .cctor() { }
}
```