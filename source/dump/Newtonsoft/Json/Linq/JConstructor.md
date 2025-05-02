# JConstructor

**Namespace:** `Newtonsoft.Json.Linq`


## Fields

- `String _name`


## Properties

- `String Name`


## Methods

- `String get_Name()`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JConstructor : JContainer
{
	private String _name; // 0x50
	private readonly List`1 _values; // 0x58

	protected override IList`1 ChildrenTokens { get; }
	public String Name { get; }
	public override JTokenType Type { get; }
	public override JToken Item { get; }

	// RVA: 0x6189cc4 VA: 0x75987a1cc4
	protected override IList`1 get_ChildrenTokens() { }
	// RVA: 0x6189ccc VA: 0x75987a1ccc
	internal override Int32 IndexOfItem(JToken item) { }
	// RVA: 0x6189d24 VA: 0x75987a1d24
	public String get_Name() { }
	// RVA: 0x6189d2c VA: 0x75987a1d2c
	public override JTokenType get_Type() { }
	// RVA: 0x6189d34 VA: 0x75987a1d34
	public Void .ctor() { }
	// RVA: 0x6189e10 VA: 0x75987a1e10
	public Void .ctor(JConstructor other) { }
	// RVA: 0x618a1d0 VA: 0x75987a21d0
	public Void .ctor(String name) { }
	// RVA: 0x618a314 VA: 0x75987a2314
	internal override Boolean DeepEquals(JToken node) { }
	// RVA: 0x618a678 VA: 0x75987a2678
	internal override JToken CloneToken() { }
	// RVA: 0x618a6d8 VA: 0x75987a26d8
	public override Void WriteTo(JsonWriter writer, JsonConverter[] converters) { }
	// RVA: 0x618a9e8 VA: 0x75987a29e8
	public override JToken get_Item(Object key) { }
	// RVA: 0x618ab14 VA: 0x75987a2b14
	internal override Int32 GetDeepHashCode() { }
	// RVA: 0x618ae58 VA: 0x75987a2e58
	public static JConstructor Load(JsonReader reader, JsonLoadSettings settings) { }
}
```