# UriBuilder

**Namespace:** `System`


## Fields

- `Boolean _changed`

- `String _fragment`

- `String _host`

- `String _password`

- `String _path`

- `Int32 _port`

- `String _query`

- `String _scheme`

- `String _schemeDelimiter`

- `Uri _uri`

- `String _username`


## Properties

- `String Host`

- `String Path`

- `Int32 Port`

- `String Query`

- `String Scheme`

- `Uri Uri`


## Methods

- `Void Init(Uri)`

- `Void set_Host(String)`

- `String get_Path()`

- `Void set_Path(String)`

- `Void set_Port(Int32)`

- `Void set_Query(String)`

- `Void set_Scheme(String)`

- `Uri get_Uri()`

- `Void SetFieldsFromUri(Uri)`


## Dump
```C#
// Dll : System.dll
// Namespace : System
public class UriBuilder
{
	private Boolean _changed; // 0x10
	private String _fragment; // 0x18
	private String _host; // 0x20
	private String _password; // 0x28
	private String _path; // 0x30
	private Int32 _port; // 0x38
	private String _query; // 0x40
	private String _scheme; // 0x48
	private String _schemeDelimiter; // 0x50
	private Uri _uri; // 0x58
	private String _username; // 0x60

	public String Host { set; }
	public String Path { get; set; }
	public Int32 Port { set; }
	public String Query { set; }
	public String Scheme { set; }
	public Uri Uri { get; }

	// RVA: 0x636d8c4 VA: 0x75989858c4
	public Void .ctor(Uri uri) { }
	// RVA: 0x636da9c VA: 0x7598985a9c
	private Void Init(Uri uri) { }
	// RVA: 0x636de4c VA: 0x7598985e4c
	public Void .ctor(String schemeName, String hostName) { }
	// RVA: 0x636e230 VA: 0x7598986230
	public Void .ctor(String scheme, String host, Int32 portNumber) { }
	// RVA: 0x636e2c8 VA: 0x75989862c8
	public Void .ctor(String scheme, String host, Int32 port, String pathValue) { }
	// RVA: 0x636e138 VA: 0x7598986138
	public Void set_Host(String value) { }
	// RVA: 0x636e3c0 VA: 0x75989863c0
	public String get_Path() { }
	// RVA: 0x636e300 VA: 0x7598986300
	public Void set_Path(String value) { }
	// RVA: 0x636e258 VA: 0x7598986258
	public Void set_Port(Int32 value) { }
	// RVA: 0x636e3c8 VA: 0x75989863c8
	public Void set_Query(String value) { }
	// RVA: 0x636dfe4 VA: 0x7598985fe4
	public Void set_Scheme(String value) { }
	// RVA: 0x636e48c VA: 0x759898648c
	public Uri get_Uri() { }
	// RVA: 0x636e534 VA: 0x7598986534
	public override Boolean Equals(Object rparam) { }
	// RVA: 0x636e590 VA: 0x7598986590
	public override Int32 GetHashCode() { }
	// RVA: 0x636dc78 VA: 0x7598985c78
	private Void SetFieldsFromUri(Uri uri) { }
	// RVA: 0x636e5b0 VA: 0x75989865b0
	public override String ToString() { }
}
```