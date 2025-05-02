# NatIntroduceRequestPacket

**Namespace:** ` `


## Fields

- `IPEndPoint <Internal>k__BackingField`

- `String <Token>k__BackingField`


## Properties

- `IPEndPoint Internal`

- `String Token`


## Methods

- `IPEndPoint get_Internal()`

- `Void set_Internal(IPEndPoint)`

- `String get_Token()`

- `Void set_Token(String)`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : 
private class NatIntroduceRequestPacket
{
	private IPEndPoint <Internal>k__BackingField; // 0x10
	private String <Token>k__BackingField; // 0x18

	public IPEndPoint Internal { get; set; }
	public String Token { get; set; }

	// RVA: 0x40f917c VA: 0x759671117c
	public IPEndPoint get_Internal() { }
	// RVA: 0x40f9184 VA: 0x7596711184
	public Void set_Internal(IPEndPoint value) { }
	// RVA: 0x40f918c VA: 0x759671118c
	public String get_Token() { }
	// RVA: 0x40f9194 VA: 0x7596711194
	public Void set_Token(String value) { }
	// RVA: 0x40f8980 VA: 0x7596710980
	public Void .ctor() { }
}
```