# ListDictConverter

**Namespace:** `Torappu`


## Fields

- `Object m_lock`


## Methods

- `GenericContext _GetGenericContext(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ListDictConverter : JsonConverter
{
	private const String KEY_NAME; // 0x0
	private const String VALUE_NAME; // 0x0
	private Dictionary`2 m_genericMap; // 0x10
	private Object m_lock; // 0x18


	// RVA: 0x34fc460 VA: 0x7595b14460
	private GenericContext _GetGenericContext(Type genericType) { }
	// RVA: 0x34fc844 VA: 0x7595b14844
	public override Boolean CanConvert(Type objectType) { }
	// RVA: 0x34fc954 VA: 0x7595b14954
	public override Object ReadJson(JsonReader reader, Type objectType, Object existingValue, JsonSerializer serializer) { }
	// RVA: 0x34fce74 VA: 0x7595b14e74
	public override Void WriteJson(JsonWriter writer, Object value, JsonSerializer serializer) { }
	// RVA: 0x34fd1fc VA: 0x7595b151fc
	public Void .ctor() { }
}
```