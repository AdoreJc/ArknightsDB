# ActArchiveParam

**Namespace:** ` `


## Fields

- `String archiveId`

- `String bgmInstIdAlias`

- `Type <archivePluginType>k__BackingField`

- `DataBundle extraPassthroughData`


## Properties

- `Type archivePluginType`


## Methods

- `Type get_archivePluginType()`

- `Void set_archivePluginType(Type)`

- `ActArchiveParam SetPlugin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ActArchiveParam
{
	public String archiveId; // 0x10
	public String bgmInstIdAlias; // 0x18
	private Type <archivePluginType>k__BackingField; // 0x20
	public DataBundle extraPassthroughData; // 0x28

	public Type archivePluginType { get; set; }

	// RVA: 0x3006fbc VA: 0x759561efbc
	public Type get_archivePluginType() { }
	// RVA: 0x3006fc4 VA: 0x759561efc4
	private Void set_archivePluginType(Type value) { }
	// RVA: 0x VA: 0x0
	public ActArchiveParam SetPlugin() { }
	// RVA: 0x3006fcc VA: 0x759561efcc
	public Void .ctor() { }
}
```