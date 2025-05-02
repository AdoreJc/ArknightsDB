# JArray

**Namespace:** `Newtonsoft.Json.Linq`


## Properties

- `JToken Item`

- `Boolean IsReadOnly`


## Methods

- `JToken get_Item(Int32)`

- `Void set_Item(Int32, JToken)`

- `Int32 IndexOf(JToken)`

- `Void Insert(Int32, JToken)`

- `Void RemoveAt(Int32)`

- `Void Add(JToken)`

- `Void Clear()`

- `Boolean Contains(JToken)`

- `Void CopyTo(JToken[], Int32)`

- `Boolean get_IsReadOnly()`

- `Boolean Remove(JToken)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JArray : JContainer, IList`1, ICollection`1, IEnumerable`1, IEnumerable
{
	private readonly List`1 _values; // 0x50

	protected override IList`1 ChildrenTokens { get; }
	public override JTokenType Type { get; }
	public override JToken Item { get; }
	public JToken Item { get; set; }
	public Boolean IsReadOnly { get; }

	// RVA: 0x61915c8 VA: 0x75987a95c8
	protected override IList`1 get_ChildrenTokens() { }
	// RVA: 0x61915d0 VA: 0x75987a95d0
	public override JTokenType get_Type() { }
	// RVA: 0x618dfb0 VA: 0x75987a5fb0
	public Void .ctor() { }
	// RVA: 0x61915d8 VA: 0x75987a95d8
	public Void .ctor(JArray other) { }
	// RVA: 0x619166c VA: 0x75987a966c
	public Void .ctor(Object content) { }
	// RVA: 0x6191714 VA: 0x75987a9714
	internal override Boolean DeepEquals(JToken node) { }
	// RVA: 0x61917a0 VA: 0x75987a97a0
	internal override JToken CloneToken() { }
	// RVA: 0x6191800 VA: 0x75987a9800
	public static JArray Load(JsonReader reader) { }
	// RVA: 0x6191808 VA: 0x75987a9808
	public static JArray Load(JsonReader reader, JsonLoadSettings settings) { }
	// RVA: 0x61919a8 VA: 0x75987a99a8
	public override Void WriteTo(JsonWriter writer, JsonConverter[] converters) { }
	// RVA: 0x6191a74 VA: 0x75987a9a74
	public override JToken get_Item(Object key) { }
	// RVA: 0x6191ba0 VA: 0x75987a9ba0
	public JToken get_Item(Int32 index) { }
	// RVA: 0x6191bb0 VA: 0x75987a9bb0
	public Void set_Item(Int32 index, JToken value) { }
	// RVA: 0x6191bc0 VA: 0x75987a9bc0
	internal override Int32 IndexOfItem(JToken item) { }
	// RVA: 0x6191c18 VA: 0x75987a9c18
	public Int32 IndexOf(JToken item) { }
	// RVA: 0x6191c28 VA: 0x75987a9c28
	public Void Insert(Int32 index, JToken item) { }
	// RVA: 0x6191c3c VA: 0x75987a9c3c
	public Void RemoveAt(Int32 index) { }
	// RVA: 0x6191c4c VA: 0x75987a9c4c
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x6191ce4 VA: 0x75987a9ce4
	public Void Add(JToken item) { }
	// RVA: 0x6191cf4 VA: 0x75987a9cf4
	public Void Clear() { }
	// RVA: 0x6191d04 VA: 0x75987a9d04
	public Boolean Contains(JToken item) { }
	// RVA: 0x6191d14 VA: 0x75987a9d14
	public Void CopyTo(JToken[] array, Int32 arrayIndex) { }
	// RVA: 0x6191d24 VA: 0x75987a9d24
	public Boolean get_IsReadOnly() { }
	// RVA: 0x6191d2c VA: 0x75987a9d2c
	public Boolean Remove(JToken item) { }
	// RVA: 0x6191d3c VA: 0x75987a9d3c
	internal override Int32 GetDeepHashCode() { }
}
```