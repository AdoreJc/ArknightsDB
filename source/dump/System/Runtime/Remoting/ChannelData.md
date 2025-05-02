# ChannelData

**Namespace:** `System.Runtime.Remoting`


## Fields

- `ArrayList _serverProviders`

- `ArrayList _clientProviders`

- `Hashtable _customProperties`


## Properties

- `ArrayList ClientProviders`

- `Hashtable CustomProperties`


## Methods

- `ArrayList get_ClientProviders()`

- `Hashtable get_CustomProperties()`

- `Void CopyFrom(ChannelData)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class ChannelData
{
	internal String Ref; // 0x10
	internal String Type; // 0x18
	internal String Id; // 0x20
	internal String DelayLoadAsClientChannel; // 0x28
	private ArrayList _serverProviders; // 0x30
	private ArrayList _clientProviders; // 0x38
	private Hashtable _customProperties; // 0x40

	internal ArrayList ServerProviders { get; }
	public ArrayList ClientProviders { get; }
	public Hashtable CustomProperties { get; }

	// RVA: 0x5f813c0 VA: 0x75985993c0
	internal ArrayList get_ServerProviders() { }
	// RVA: 0x5f81b60 VA: 0x7598599b60
	public ArrayList get_ClientProviders() { }
	// RVA: 0x5f85a84 VA: 0x759859da84
	public Hashtable get_CustomProperties() { }
	// RVA: 0x5f80a60 VA: 0x7598598a60
	public Void CopyFrom(ChannelData other) { }
	// RVA: 0x5f859ac VA: 0x759859d9ac
	public Void .ctor() { }
}
```