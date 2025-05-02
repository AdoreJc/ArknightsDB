# IPHostEntry

**Namespace:** `System.Net`


## Fields

- `String hostName`


## Properties

- `String HostName`


## Methods

- `String get_HostName()`

- `Void set_HostName(String)`

- `Void set_Aliases(String[])`

- `Void set_AddressList(IPAddress[])`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class IPHostEntry
{
	private String hostName; // 0x10
	private String[] aliases; // 0x18
	private IPAddress[] addressList; // 0x20
	internal Boolean isTrustedHost; // 0x28

	public String HostName { get; set; }
	public String[] Aliases { set; }
	public IPAddress[] AddressList { get; set; }

	// RVA: 0x6429874 VA: 0x7598a41874
	public String get_HostName() { }
	// RVA: 0x642987c VA: 0x7598a4187c
	public Void set_HostName(String value) { }
	// RVA: 0x6429884 VA: 0x7598a41884
	public Void set_Aliases(String[] value) { }
	// RVA: 0x642988c VA: 0x7598a4188c
	public IPAddress[] get_AddressList() { }
	// RVA: 0x6429894 VA: 0x7598a41894
	public Void set_AddressList(IPAddress[] value) { }
	// RVA: 0x642989c VA: 0x7598a4189c
	public Void .ctor() { }
}
```