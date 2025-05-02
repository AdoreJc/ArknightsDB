# JsonPropertyCollection

**Namespace:** `Newtonsoft.Json.Serialization`


## Methods

- `Void AddProperty(JsonProperty)`

- `JsonProperty GetClosestMatchProperty(String)`

- `Boolean TryGetValue(String, out)`

- `JsonProperty GetProperty(String, StringComparison)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class JsonPropertyCollection : KeyedCollection`2
{
	private readonly Type _type; // 0x30
	private readonly List`1 _list; // 0x38


	// RVA: 0x61733e8 VA: 0x759878b3e8
	public Void .ctor(Type type) { }
	// RVA: 0x6173564 VA: 0x759878b564
	protected override String GetKeyForItem(JsonProperty item) { }
	// RVA: 0x617357c VA: 0x759878b57c
	public Void AddProperty(JsonProperty property) { }
	// RVA: 0x61737b0 VA: 0x759878b7b0
	public JsonProperty GetClosestMatchProperty(String propertyName) { }
	// RVA: 0x61738dc VA: 0x759878b8dc
	private Boolean TryGetValue(String key, out JsonProperty item) { }
	// RVA: 0x61737f0 VA: 0x759878b7f0
	public JsonProperty GetProperty(String propertyName, StringComparison comparisonType) { }
}
```