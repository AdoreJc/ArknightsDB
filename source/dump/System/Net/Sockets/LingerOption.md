# LingerOption

**Namespace:** `System.Net.Sockets`


## Fields

- `Boolean enabled`

- `Int32 lingerTime`


## Properties

- `Boolean Enabled`

- `Int32 LingerTime`


## Methods

- `Void set_Enabled(Boolean)`

- `Void set_LingerTime(Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public class LingerOption
{
	private Boolean enabled; // 0x10
	private Int32 lingerTime; // 0x14

	public Boolean Enabled { set; }
	public Int32 LingerTime { set; }

	// RVA: 0x63601ac VA: 0x75989781ac
	public Void .ctor(Boolean enable, Int32 seconds) { }
	// RVA: 0x63601e0 VA: 0x75989781e0
	public Void set_Enabled(Boolean value) { }
	// RVA: 0x63601ec VA: 0x75989781ec
	public Void set_LingerTime(Int32 value) { }
}
```