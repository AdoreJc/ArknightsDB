# PositionedEffectInfo

**Namespace:** ` `


## Fields

- `Int32 sourceInstId`

- `Int32 equipInstId`

- `Int32 earnedMoney`

- `Boolean upgraded`

- `Boolean gained`

- `Boolean destoryed`

- `Boolean equipDestoryed`

- `Boolean lined`

- `Boolean upgradeExpChanges`

- `GridPosition pos`

- `GridPosition sourcePos`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PositionedEffectInfo : IHotfixable
{
	public Int32 sourceInstId; // 0x10
	public Int32 equipInstId; // 0x14
	public Int32 earnedMoney; // 0x18
	public Boolean upgraded; // 0x1c
	public Boolean gained; // 0x1d
	public Boolean destoryed; // 0x1e
	public Boolean equipDestoryed; // 0x1f
	public Boolean lined; // 0x20
	public Boolean upgradeExpChanges; // 0x21
	public GridPosition pos; // 0x24
	public GridPosition sourcePos; // 0x2c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1d011fc VA: 0x75943191fc
	public Void .ctor() { }
}
```