# XDeclaration

**Namespace:** `System.Xml.Linq`


## Fields

- `String _version`

- `String _encoding`

- `String _standalone`


## Properties

- `String Encoding`

- `String Standalone`

- `String Version`


## Methods

- `String get_Encoding()`

- `String get_Standalone()`

- `String get_Version()`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XDeclaration
{
	private String _version; // 0x10
	private String _encoding; // 0x18
	private String _standalone; // 0x20

	public String Encoding { get; }
	public String Standalone { get; }
	public String Version { get; }

	// RVA: 0x6281fc8 VA: 0x7598899fc8
	public Void .ctor(String version, String encoding, String standalone) { }
	// RVA: 0x6282028 VA: 0x759889a028
	public Void .ctor(XDeclaration other) { }
	// RVA: 0x62820c8 VA: 0x759889a0c8
	public String get_Encoding() { }
	// RVA: 0x62820d0 VA: 0x759889a0d0
	public String get_Standalone() { }
	// RVA: 0x62820d8 VA: 0x759889a0d8
	public String get_Version() { }
	// RVA: 0x62820e0 VA: 0x759889a0e0
	public override String ToString() { }
}
```