# BlackboardConverter

**Namespace:** `Torappu`


## Methods

- `Void _WriteDataPair(JsonWriter, DataPair)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BlackboardConverter : JsonConverter
{

	public override Boolean CanRead { get; }

	// RVA: 0x34fdc58 VA: 0x7595b15c58
	public override Boolean get_CanRead() { }
	// RVA: 0x34fdc60 VA: 0x7595b15c60
	public override Boolean CanConvert(Type objectType) { }
	// RVA: 0x34fdcf4 VA: 0x7595b15cf4
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x34fdd44 VA: 0x7595b15d44
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x34fde8c VA: 0x7595b15e8c
	private Void _WriteDataPair(JsonWriter writer, DataPair data) { }
	// RVA: 0x34fdfc0 VA: 0x7595b15fc0
	public Void .ctor() { }
}
```