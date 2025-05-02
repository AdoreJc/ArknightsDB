# JTokenReader

**Namespace:** `Newtonsoft.Json.Linq`


## Fields

- `String _initialPath`

- `JToken _parent`

- `JToken _current`


## Properties

- `JToken CurrentToken`


## Methods

- `JToken get_CurrentToken()`

- `Boolean ReadOver(JToken)`

- `Boolean ReadToEnd()`

- `Boolean ReadInto(JContainer)`

- `Boolean SetEnd(JContainer)`

- `Void SetToken(JToken)`

- `String SafeToString(Object)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JTokenReader : JsonReader, IJsonLineInfo
{
	private readonly JToken _root; // 0x78
	private String _initialPath; // 0x80
	private JToken _parent; // 0x88
	private JToken _current; // 0x90

	public JToken CurrentToken { get; }
	private Int32 Newtonsoft.Json.IJsonLineInfo.LineNumber { get; }
	private Int32 Newtonsoft.Json.IJsonLineInfo.LinePosition { get; }
	public override String Path { get; }

	// RVA: 0x6191d40 VA: 0x75987a9d40
	public JToken get_CurrentToken() { }
	// RVA: 0x6191d48 VA: 0x75987a9d48
	public Void .ctor(JToken token) { }
	// RVA: 0x6191dbc VA: 0x75987a9dbc
	public override Boolean Read() { }
	// RVA: 0x6191f14 VA: 0x75987a9f14
	private Boolean ReadOver(JToken t) { }
	// RVA: 0x61924c0 VA: 0x75987aa4c0
	private Boolean ReadToEnd() { }
	// RVA: 0x6192590 VA: 0x75987aa590
	private Nullable`1 GetEndToken(JContainer c) { }
	// RVA: 0x6191e90 VA: 0x75987a9e90
	private Boolean ReadInto(JContainer c) { }
	// RVA: 0x61924f0 VA: 0x75987aa4f0
	private Boolean SetEnd(JContainer c) { }
	// RVA: 0x6191fe4 VA: 0x75987a9fe4
	private Void SetToken(JToken token) { }
	// RVA: 0x61926d8 VA: 0x75987aa6d8
	private String SafeToString(Object value) { }
	// RVA: 0x61926f8 VA: 0x75987aa6f8
	private Boolean Newtonsoft.Json.IJsonLineInfo.HasLineInfo() { }
	// RVA: 0x61927ac VA: 0x75987aa7ac
	private Int32 Newtonsoft.Json.IJsonLineInfo.get_LineNumber() { }
	// RVA: 0x6192864 VA: 0x75987aa864
	private Int32 Newtonsoft.Json.IJsonLineInfo.get_LinePosition() { }
	// RVA: 0x619291c VA: 0x75987aa91c
	public override String get_Path() { }
}
```