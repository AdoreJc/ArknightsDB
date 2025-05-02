# SellInfo

**Namespace:** ` `


## Fields

- `String shopId`

- `String shopIconId`

- `Int32 sellPrice`

- `Int32 sellCount`

- `Int32 stockCount`

- `Int32 prizeReward`

- `Boolean isPlayer`

- `Int32 sortId`


## Properties

- `Boolean isPlayerSoldOut`

- `Int32 income`


## Methods

- `Boolean get_isPlayerSoldOut()`

- `Int32 get_income()`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SellInfo : IHotfixable, IComparable
{
	public String shopId; // 0x10
	public String shopIconId; // 0x18
	public Int32 sellPrice; // 0x20
	public Int32 sellCount; // 0x24
	public Int32 stockCount; // 0x28
	public Int32 prizeReward; // 0x2c
	public Boolean isPlayer; // 0x30
	public Int32 sortId; // 0x34
	private static DelegateBridge __Hotfix0_get_isPlayerSoldOut; // 0x0
	private static DelegateBridge __Hotfix0_get_income; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isPlayerSoldOut { get; }
	public Int32 income { get; }

	// RVA: 0x28a3000 VA: 0x7594ebb000
	public Boolean get_isPlayerSoldOut() { }
	// RVA: 0x28a2f24 VA: 0x7594ebaf24
	public Int32 get_income() { }
	// RVA: 0x28a3080 VA: 0x7594ebb080
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x28a2eb4 VA: 0x7594ebaeb4
	public Void .ctor() { }
}
```