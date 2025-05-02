# MibIPGlobalProperties

**Namespace:** `System.Net.NetworkInformation`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class MibIPGlobalProperties : UnixIPGlobalProperties
{
	public readonly String StatisticsFile; // 0x10
	public readonly String StatisticsFileIPv6; // 0x18
	public readonly String TcpFile; // 0x20
	public readonly String Tcp6File; // 0x28
	public readonly String UdpFile; // 0x30
	public readonly String Udp6File; // 0x38
	private static readonly Char[] wsChars; // 0x0


	// RVA: 0x634bd44 VA: 0x7598963d44
	public Void .ctor(String procDir) { }
	// RVA: 0x634bef0 VA: 0x7598963ef0
	private static Void .cctor() { }
}
```