# ShopContent

**Namespace:** ` `


## Fields

- `Bank bank`

- `String id`

- `Boolean canBattle`

- `Boolean hasBoss`

- `Boolean showRefresh`

- `Int32 refreshCnt`

- `Int32 recycleCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ShopContent
{
	public Bank bank; // 0x10
	public String id; // 0x18
	public List`1 goods; // 0x20
	public Boolean canBattle; // 0x28
	public Boolean hasBoss; // 0x29
	public Boolean showRefresh; // 0x2a
	public Int32 refreshCnt; // 0x2c
	public List`1 recycleGoods; // 0x30
	public Int32 recycleCount; // 0x38


	// RVA: 0x32db154 VA: 0x75958f3154
	public Void .ctor() { }
}
```