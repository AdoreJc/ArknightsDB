# SvrLogRule

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
private class SvrLogRule : IServerLogRule
{

	public String prefix { get; }
	public Boolean logDetail { get; }

	// RVA: 0x29ae8c4 VA: 0x7594fc68c4
	public String get_prefix() { }
	// RVA: 0x29ae904 VA: 0x7594fc6904
	public Boolean get_logDetail() { }
	// RVA: 0x29ae90c VA: 0x7594fc690c
	public Boolean AllowedRevMsg(Protocol protocol) { }
	// RVA: 0x29ae934 VA: 0x7594fc6934
	public Boolean AllowedSendMsg(Protocol protocol) { }
	// RVA: 0x29adb5c VA: 0x7594fc5b5c
	public Void .ctor() { }
}
```