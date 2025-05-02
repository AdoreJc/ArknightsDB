# IsoDateTimeConverter

**Namespace:** `Newtonsoft.Json.Converters`


## Fields

- `DateTimeStyles _dateTimeStyles`

- `String _dateTimeFormat`

- `CultureInfo _culture`


## Properties

- `CultureInfo Culture`


## Methods

- `CultureInfo get_Culture()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Converters
public class IsoDateTimeConverter : DateTimeConverterBase
{
	private DateTimeStyles _dateTimeStyles; // 0x10
	private String _dateTimeFormat; // 0x18
	private CultureInfo _culture; // 0x20

	public CultureInfo Culture { get; }

	// RVA: 0x61aa390 VA: 0x75987c2390
	public CultureInfo get_Culture() { }
	// RVA: 0x61aa3f8 VA: 0x75987c23f8
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x61aa668 VA: 0x75987c2668
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x61aab38 VA: 0x75987c2b38
	public Void .ctor() { }
}
```