# fsForwardConverter

**Namespace:** `FullSerializer.Internal`


## Fields

- `String _memberName`


## Methods

- `fsResult GetProperty(Object, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsForwardConverter : fsConverter
{
	private String _memberName; // 0x18


	// RVA: 0x34b6ea8 VA: 0x7595aceea8
	public Void .ctor(fsForwardAttribute attribute) { }
	// RVA: 0x34bef30 VA: 0x7595ad6f30
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34bef80 VA: 0x7595ad6f80
	private fsResult GetProperty(Object instance, out fsMetaProperty property) { }
	// RVA: 0x34bf150 VA: 0x7595ad7150
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34bf3c8 VA: 0x7595ad73c8
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34bf6f0 VA: 0x7595ad76f0
	public override Object CreateInstance(fsData data, Type storageType) { }
}
```