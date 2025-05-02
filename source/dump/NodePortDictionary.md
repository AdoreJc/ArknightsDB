# NodePortDictionary

**Namespace:** ` `


## Methods

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : XNode.dll
// Namespace : 
private class NodePortDictionary : Dictionary`2, ISerializationCallbackReceiver
{
	private List`1 keys; // 0x50
	private List`1 values; // 0x58


	// RVA: 0x6a8c86c VA: 0x75990a486c
	public Void OnBeforeSerialize() { }
	// RVA: 0x6a8cb4c VA: 0x75990a4b4c
	public Void OnAfterDeserialize() { }
	// RVA: 0x6a8c4f4 VA: 0x75990a44f4
	public Void .ctor() { }
}
```