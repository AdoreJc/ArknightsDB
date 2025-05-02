# fsLazyCycleDefinitionWriter

**Namespace:** ` `


## Methods

- `Void WriteDefinition(Int32, fsData)`

- `Void WriteReference(Int32, Dictionary`2)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
internal class fsLazyCycleDefinitionWriter
{
	private Dictionary`2 _pendingDefinitions; // 0x10
	private HashSet`1 _references; // 0x18


	// RVA: 0x34b7a24 VA: 0x7595acfa24
	public Void WriteDefinition(Int32 id, fsData data) { }
	// RVA: 0x34b76c4 VA: 0x7595acf6c4
	public Void WriteReference(Int32 id, Dictionary`2 dict) { }
	// RVA: 0x34b96ec VA: 0x7595ad16ec
	public Void Clear() { }
	// RVA: 0x34b624c VA: 0x7595ace24c
	public Void .ctor() { }
}
```