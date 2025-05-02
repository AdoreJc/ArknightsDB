# ClimbTowerInnerBuffModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String buffId`

- `String buffDesc`

- `Int32 professionOrder`

- `Int32 sortId`

- `ProfessionCategory buffProfession`

- `ClimbTowerTaticalBuffType buffType`


## Methods

- `Void LoadData(String)`

- `String GetProfessionIconName()`

- `String GetBuffName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInnerBuffModel : IHotfixable
{
	public String buffId; // 0x10
	public String buffDesc; // 0x18
	public Int32 professionOrder; // 0x20
	public Int32 sortId; // 0x24
	public ProfessionCategory buffProfession; // 0x28
	public ClimbTowerTaticalBuffType buffType; // 0x2c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetProfessionIconName; // 0x8
	private static DelegateBridge __Hotfix0_GetBuffName; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2cd9a64 VA: 0x75952f1a64
	public Void LoadData(String buff) { }
	// RVA: 0x2cd9b80 VA: 0x75952f1b80
	public String GetProfessionIconName() { }
	// RVA: 0x2cd9c5c VA: 0x75952f1c5c
	public String GetBuffName() { }
	// RVA: 0x2cd9d34 VA: 0x75952f1d34
	public Void .ctor() { }
}
```