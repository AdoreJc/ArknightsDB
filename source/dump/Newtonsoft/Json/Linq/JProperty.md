# JProperty

**Namespace:** `Newtonsoft.Json.Linq`


## Properties

- `String Name`

- `JToken Value`


## Methods

- `String get_Name()`

- `JToken get_Value()`

- `Void set_Value(JToken)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JProperty : JContainer
{
	private readonly JPropertyList _content; // 0x50
	private readonly String _name; // 0x58

	protected override IList`1 ChildrenTokens { get; }
	public String Name { get; }
	public JToken Value { get; set; }
	public override JTokenType Type { get; }

	// RVA: 0x619adf4 VA: 0x75987b2df4
	protected override IList`1 get_ChildrenTokens() { }
	// RVA: 0x619adfc VA: 0x75987b2dfc
	public String get_Name() { }
	// RVA: 0x6189598 VA: 0x75987a1598
	public JToken get_Value() { }
	// RVA: 0x618f384 VA: 0x75987a7384
	public Void set_Value(JToken value) { }
	// RVA: 0x619ae04 VA: 0x75987b2e04
	public Void .ctor(JProperty other) { }
	// RVA: 0x619aea0 VA: 0x75987b2ea0
	internal override JToken GetItem(Int32 index) { }
	// RVA: 0x619aefc VA: 0x75987b2efc
	internal override Void SetItem(Int32 index, JToken item) { }
	// RVA: 0x619b048 VA: 0x75987b3048
	internal override Boolean RemoveItem(JToken item) { }
	// RVA: 0x619b0fc VA: 0x75987b30fc
	internal override Void RemoveItemAt(Int32 index) { }
	// RVA: 0x619b1b0 VA: 0x75987b31b0
	internal override Int32 IndexOfItem(JToken item) { }
	// RVA: 0x619b1e4 VA: 0x75987b31e4
	internal override Void InsertItem(Int32 index, JToken item, Boolean skipParentCheck) { }
	// RVA: 0x619b2f8 VA: 0x75987b32f8
	internal override Boolean ContainsItem(JToken item) { }
	// RVA: 0x619b31c VA: 0x75987b331c
	internal override Void ClearItems() { }
	// RVA: 0x619b3d0 VA: 0x75987b33d0
	internal override Boolean DeepEquals(JToken node) { }
	// RVA: 0x619b47c VA: 0x75987b347c
	internal override JToken CloneToken() { }
	// RVA: 0x619b4dc VA: 0x75987b34dc
	public override JTokenType get_Type() { }
	// RVA: 0x618e164 VA: 0x75987a6164
	internal Void .ctor(String name) { }
	// RVA: 0x618f400 VA: 0x75987a7400
	public Void .ctor(String name, Object content) { }
	// RVA: 0x619b4e4 VA: 0x75987b34e4
	public override Void WriteTo(JsonWriter writer, JsonConverter[] converters) { }
	// RVA: 0x619b564 VA: 0x75987b3564
	internal override Int32 GetDeepHashCode() { }
	// RVA: 0x6199e1c VA: 0x75987b1e1c
	public static JProperty Load(JsonReader reader, JsonLoadSettings settings) { }
}
```