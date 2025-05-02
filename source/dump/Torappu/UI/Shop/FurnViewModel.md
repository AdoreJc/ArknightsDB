# FurnViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Boolean isGood`

- `Good good`

- `FurnGroupViewModel group`


## Methods

- `String GetGoodId()`

- `Int32 GetSortId()`

- `Int32 CompareTo(FurnViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class FurnViewModel : IComparable`1
{
	public Boolean isGood; // 0x10
	public Good good; // 0x18
	public FurnGroupViewModel group; // 0x20


	// RVA: 0x243f2d4 VA: 0x7594a572d4
	public String GetGoodId() { }
	// RVA: 0x243f30c VA: 0x7594a5730c
	public Int32 GetSortId() { }
	// RVA: 0x243f34c VA: 0x7594a5734c
	public Int32 CompareTo(FurnViewModel other) { }
	// RVA: 0x243f38c VA: 0x7594a5738c
	public Void .ctor() { }
}
```