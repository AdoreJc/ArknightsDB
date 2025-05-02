# MultiplayerServerLogRule

**Namespace:** ` `


## Properties

- `String prefix`

- `Boolean logDetail`


## Methods

- `String get_prefix()`

- `Boolean get_logDetail()`

- `Boolean AllowedRevMsg(Protocol)`

- `Boolean AllowedSendMsg(Protocol)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MultiplayerServerLogRule : IServerLogRule
{

	public String prefix { get; }
	public Boolean logDetail { get; }

	// RVA: 0x35a9180 VA: 0x7595bc1180
	public String get_prefix() { }
	// RVA: 0x35a91c0 VA: 0x7595bc11c0
	public Boolean get_logDetail() { }
	// RVA: 0x35a91c8 VA: 0x7595bc11c8
	public Boolean AllowedRevMsg(Protocol protocol) { }
	// RVA: 0x35a91f0 VA: 0x7595bc11f0
	public Boolean AllowedSendMsg(Protocol protocol) { }
	// RVA: 0x35a6590 VA: 0x7595bbe590
	public Void .ctor() { }
}
```