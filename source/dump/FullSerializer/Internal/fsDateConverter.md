# fsDateConverter

**Namespace:** `FullSerializer.Internal`


## Properties

- `String DateTimeFormatString`


## Methods

- `String get_DateTimeFormatString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsDateConverter : fsConverter
{
	private const String DefaultDateTimeFormatString; // 0x0
	private const String DateTimeOffsetFormatString; // 0x0

	private String DateTimeFormatString { get; }

	// RVA: 0x34bc2d4 VA: 0x7595ad42d4
	private String get_DateTimeFormatString() { }
	// RVA: 0x34bc338 VA: 0x7595ad4338
	public override Boolean CanProcess(Type type) { }
	// RVA: 0x34bc464 VA: 0x7595ad4464
	public override fsResult TrySerialize(Object instance, out fsData serialized, Type storageType) { }
	// RVA: 0x34bc6a4 VA: 0x7595ad46a4
	public override fsResult TryDeserialize(fsData data, ref Object instance, Type storageType) { }
	// RVA: 0x34b633c VA: 0x7595ace33c
	public Void .ctor() { }
}
```