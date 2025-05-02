# DelegateSerializationHolder

**Namespace:** `System`


## Fields

- `Delegate _delegate`


## Methods

- `Void GetObjectData(SerializationInfo, StreamingContext)`

- `Object GetRealObject(StreamingContext)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class DelegateSerializationHolder : ISerializable, IObjectReference
{
	private Delegate _delegate; // 0x10


	// RVA: 0x61000ac VA: 0x75987180ac
	private Void .ctor(SerializationInfo info, StreamingContext ctx) { }
	// RVA: 0x60ffc74 VA: 0x7598717c74
	public static Void GetDelegateData(Delegate instance, SerializationInfo info, StreamingContext ctx) { }
	// RVA: 0x61006a4 VA: 0x75987186a4
	public Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x61006e4 VA: 0x75987186e4
	public Object GetRealObject(StreamingContext context) { }
}
```