# CultureNotFoundException

**Namespace:** `System.Globalization`


## Fields

- `String _invalidCultureName`


## Properties

- `String FormatedInvalidCultureId`


## Methods

- `String get_FormatedInvalidCultureId()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class CultureNotFoundException : ArgumentException
{
	private String _invalidCultureName; // 0x98
	private Nullable`1 _invalidCultureId; // 0xa0

	public virtual Nullable`1 InvalidCultureId { get; }
	public virtual String InvalidCultureName { get; }
	private static String DefaultMessage { get; }
	private String FormatedInvalidCultureId { get; }
	public override String Message { get; }

	// RVA: 0x60450a8 VA: 0x759865d0a8
	public Void .ctor() { }
	// RVA: 0x6045134 VA: 0x759865d134
	public Void .ctor(String paramName, String message) { }
	// RVA: 0x6045148 VA: 0x759865d148
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6045318 VA: 0x759865d318
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x604547c VA: 0x759865d47c
	public virtual Nullable`1 get_InvalidCultureId() { }
	// RVA: 0x6045484 VA: 0x759865d484
	public virtual String get_InvalidCultureName() { }
	// RVA: 0x60450f4 VA: 0x759865d0f4
	private static String get_DefaultMessage() { }
	// RVA: 0x604548c VA: 0x759865d48c
	private String get_FormatedInvalidCultureId() { }
	// RVA: 0x60455c8 VA: 0x759865d5c8
	public override String get_Message() { }
}
```