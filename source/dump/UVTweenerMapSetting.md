# UVTweenerMapSetting

**Namespace:** ` `


## Fields

- `Boolean enabled`

- `String mapName`

- `Single XSpeed`

- `Single YSpeed`

- `Vector4 mapST`

- `String m_mapSTProp`


## Properties

- `String mapSTProp`


## Methods

- `String get_mapSTProp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UVTweenerMapSetting
{
	public Boolean enabled; // 0x10
	public String mapName; // 0x18
	public Single XSpeed; // 0x20
	public Single YSpeed; // 0x24
	public Vector4 mapST; // 0x28
	private String m_mapSTProp; // 0x38

	public String mapSTProp { get; }

	// RVA: 0x3f00528 VA: 0x7596518528
	public String get_mapSTProp() { }
	// RVA: 0x3f00bb8 VA: 0x7596518bb8
	public Void .ctor() { }
}
```