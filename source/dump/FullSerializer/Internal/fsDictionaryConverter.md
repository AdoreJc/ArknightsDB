# fsDictionaryConverter

**Namespace:** `FullSerializer.Internal`


## Methods

- `fsResult AddItemToDictionary(IDictionary, Object, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsDictionaryConverter : fsConverter
{


	// RVA: 0x34bcc74 VA: 0x7595ad4c74
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34bcd08 VA: 0x7595ad4d08
	public override Object CreateInstance(fsData data, Type storageType) { }
	// RVA: 0x34bcd7c VA: 0x7595ad4d7c
	public override fsResult TryDeserialize(fsData data, ref Object instance_, Type storageType) { }
	// RVA: 0x34bd8bc VA: 0x7595ad58bc
	public override fsResult TrySerialize(Object instance_, out fsData serialized, Type storageType) { }
	// RVA: 0x34bd554 VA: 0x7595ad5554
	private fsResult AddItemToDictionary(IDictionary dictionary, Object key, Object value) { }
	// RVA: 0x34bd3f8 VA: 0x7595ad53f8
	private static Void GetKeyValueTypes(Type dictionaryType, out Type keyStorageType, out Type valueStorageType) { }
	// RVA: 0x34b635c VA: 0x7595ace35c
	public Void .ctor() { }
}
```