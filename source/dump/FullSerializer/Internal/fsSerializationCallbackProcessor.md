# fsSerializationCallbackProcessor

**Namespace:** `FullSerializer.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsSerializationCallbackProcessor : fsObjectProcessor
{


	// RVA: 0x34c3944 VA: 0x7595adb944
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34c39d8 VA: 0x7595adb9d8
	public override Void OnBeforeSerialize(Type storageType, Object instance) { }
	// RVA: 0x34c3ad4 VA: 0x7595adbad4
	public override Void OnAfterSerialize(Type storageType, Object instance, ref fsData data) { }
	// RVA: 0x34c3bdc VA: 0x7595adbbdc
	public override Void OnBeforeDeserializeAfterInstanceCreation(Type storageType, Object instance, ref fsData data) { }
	// RVA: 0x34c3dd4 VA: 0x7595adbdd4
	public override Void OnAfterDeserialize(Type storageType, Object instance) { }
	// RVA: 0x34b6384 VA: 0x7595ace384
	public Void .ctor() { }
}
```