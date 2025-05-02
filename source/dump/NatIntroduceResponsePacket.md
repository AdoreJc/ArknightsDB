# NatIntroduceResponsePacket

**Namespace:** ` `


## Fields

- `IPEndPoint <Internal>k__BackingField`

- `IPEndPoint <External>k__BackingField`

- `String <Token>k__BackingField`


## Properties

- `IPEndPoint Internal`

- `IPEndPoint External`

- `String Token`


## Methods

- `IPEndPoint get_Internal()`

- `Void set_Internal(IPEndPoint)`

- `IPEndPoint get_External()`

- `Void set_External(IPEndPoint)`

- `String get_Token()`

- `Void set_Token(String)`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : 
private class NatIntroduceResponsePacket
{
	private IPEndPoint <Internal>k__BackingField; // 0x10
	private IPEndPoint <External>k__BackingField; // 0x18
	private String <Token>k__BackingField; // 0x20

	public IPEndPoint Internal { get; set; }
	public IPEndPoint External { get; set; }
	public String Token { get; set; }

	// RVA: 0x40f919c VA: 0x759671119c
	public IPEndPoint get_Internal() { }
	// RVA: 0x40f91a4 VA: 0x75967111a4
	public Void set_Internal(IPEndPoint value) { }
	// RVA: 0x40f91ac VA: 0x75967111ac
	public IPEndPoint get_External() { }
	// RVA: 0x40f91b4 VA: 0x75967111b4
	public Void set_External(IPEndPoint value) { }
	// RVA: 0x40f91bc VA: 0x75967111bc
	public String get_Token() { }
	// RVA: 0x40f91c4 VA: 0x75967111c4
	public Void set_Token(String value) { }
	// RVA: 0x40f818c VA: 0x759671018c
	public Void .ctor() { }
}
```