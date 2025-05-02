# Authorization

**Namespace:** `System.Net`


## Fields

- `String m_Message`

- `Boolean m_Complete`


## Properties

- `String Message`

- `Boolean Complete`


## Methods

- `String get_Message()`

- `Boolean get_Complete()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class Authorization
{
	private String m_Message; // 0x10
	private Boolean m_Complete; // 0x18
	internal String ModuleAuthenticationType; // 0x20

	public String Message { get; }
	public Boolean Complete { get; }

	// RVA: 0x64293e4 VA: 0x7598a413e4
	public Void .ctor(String token) { }
	// RVA: 0x6429470 VA: 0x7598a41470
	public Void .ctor(String token, Boolean finished) { }
	// RVA: 0x64294fc VA: 0x7598a414fc
	public String get_Message() { }
	// RVA: 0x6429504 VA: 0x7598a41504
	public Boolean get_Complete() { }
}
```