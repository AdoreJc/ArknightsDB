# FurnCurrentInfoViewModel

**Namespace:** ` `


## Fields

- `String goodId`

- `String furnName`

- `String setName`

- `String furnId`

- `Int32 currentCount`

- `Int32 remainCount`

- `Int32 diamondPrice`

- `Int32 furnCoinPrice`

- `Boolean ableToBuy`

- `Int32 buyCount`

- `Int32 m_perCount`


## Properties

- `Int32 perCountWrapped`


## Methods

- `Int32 get_perCountWrapped()`

- `Void set_perCountWrapped(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FurnCurrentInfoViewModel
{
	public String goodId; // 0x10
	public String furnName; // 0x18
	public String setName; // 0x20
	public String furnId; // 0x28
	public Int32 currentCount; // 0x30
	public Int32 remainCount; // 0x34
	public Int32 diamondPrice; // 0x38
	public Int32 furnCoinPrice; // 0x3c
	public Boolean ableToBuy; // 0x40
	public Int32 buyCount; // 0x44
	private Int32 m_perCount; // 0x48

	public Int32 perCountWrapped { get; set; }

	// RVA: 0x243e67c VA: 0x7594a5667c
	public Int32 get_perCountWrapped() { }
	// RVA: 0x243f2cc VA: 0x7594a572cc
	public Void set_perCountWrapped(Int32 value) { }
	// RVA: 0x243f234 VA: 0x7594a57234
	public Void .ctor() { }
}
```