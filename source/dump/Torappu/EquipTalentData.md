# EquipTalentData

**Namespace:** `Torappu`


## Fields

- `Boolean displayRangeId`

- `String upgradeDescription`

- `Int32 talentIndex`


## Methods

- `Boolean <>xLuaBaseProxy_get_displayRange()`

- `String <>xLuaBaseProxy_GetDescription()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class EquipTalentData : TalentData
{
	public Boolean displayRangeId; // 0x51
	public String upgradeDescription; // 0x58
	public Int32 talentIndex; // 0x60
	private static DelegateBridge __Hotfix0_get_displayRange; // 0x0
	private static DelegateBridge __Hotfix0_GetDescription; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Boolean displayRange { get; }

	// RVA: 0x34f8ae8 VA: 0x7595b10ae8
	public override Boolean get_displayRange() { }
	// RVA: 0x34f8b50 VA: 0x7595b10b50
	public override String GetDescription() { }
	// RVA: 0x34f8bd8 VA: 0x7595b10bd8
	public Void .ctor() { }
	// RVA: 0x34f8c44 VA: 0x7595b10c44
	private Boolean <>xLuaBaseProxy_get_displayRange() { }
	// RVA: 0x34f8c48 VA: 0x7595b10c48
	private String <>xLuaBaseProxy_GetDescription() { }
}
```