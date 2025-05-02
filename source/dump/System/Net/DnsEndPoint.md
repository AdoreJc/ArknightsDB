# DnsEndPoint

**Namespace:** `System.Net`


## Fields

- `String m_Host`

- `Int32 m_Port`


## Properties

- `String Host`

- `Int32 Port`


## Methods

- `String get_Host()`

- `Int32 get_Port()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class DnsEndPoint : EndPoint
{
	private String m_Host; // 0x10
	private Int32 m_Port; // 0x18

	public String Host { get; }
	public Int32 Port { get; }

	// RVA: 0x64296e0 VA: 0x7598a416e0
	public String get_Host() { }
	// RVA: 0x64296e8 VA: 0x7598a416e8
	public Int32 get_Port() { }
}
```