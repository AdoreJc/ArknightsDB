# PortDataCache

**Namespace:** ` `


## Methods

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : XNode.dll
// Namespace : 
private class PortDataCache : Dictionary`2, ISerializationCallbackReceiver
{
	private List`1 keys; // 0x50
	private List`1 values; // 0x58


	// RVA: 0x6a90764 VA: 0x75990a8764
	public Void OnBeforeSerialize() { }
	// RVA: 0x6a90a44 VA: 0x75990a8a44
	public Void OnAfterDeserialize() { }
	// RVA: 0x6a8fa88 VA: 0x75990a7a88
	public Void .ctor() { }
}
```