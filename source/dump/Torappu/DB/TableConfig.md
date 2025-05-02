# TableConfig

**Namespace:** `Torappu.DB`


## Fields

- `Boolean loadFromResource`

- `String assetPath`

- `TextAsset textAsset`

- `ConverterType convertType`


## Properties

- `Boolean fromResource`


## Methods

- `Boolean get_fromResource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class TableConfig
{
	public Boolean loadFromResource; // 0x10
	public String assetPath; // 0x18
	public TextAsset textAsset; // 0x20
	public ConverterType convertType; // 0x28

	public Boolean fromResource { get; }

	// RVA: 0x371e350 VA: 0x7595d36350
	public Boolean get_fromResource() { }
	// RVA: 0x371e358 VA: 0x7595d36358
	public Void .ctor() { }
}
```