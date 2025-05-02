# SandboxV2DungeonRareAnimalViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String enemyId`

- `String enemyGroupKey`

- `SandboxV2DropDetail rareAnimalDrop`

- `Int32 remainDays`

- `Boolean hpRatioValid`

- `Int32 hpRatio`


## Methods

- `Void UpdateData(UpdateParam)`

- `Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonRareAnimalViewModel : SandboxV2DungeonFloatViewModel
{
	private const Int32 DEFAULT_HP_RATIO; // 0x0
	public String enemyId; // 0x60
	public String enemyGroupKey; // 0x68
	public SandboxV2DropDetail rareAnimalDrop; // 0x70
	public Int32 remainDays; // 0x90
	public Boolean hpRatioValid; // 0x94
	public Int32 hpRatio; // 0x98
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0_CompareDungeonFloat; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25c0228 VA: 0x7594bd8228
	public Void UpdateData(UpdateParam updateParam) { }
	// RVA: 0x25c0544 VA: 0x7594bd8544
	public override Int32 CompareDungeonFloat(SandboxV2DungeonFloatViewModel other) { }
	// RVA: 0x25c0650 VA: 0x7594bd8650
	public Void .ctor() { }
	// RVA: 0x25c06bc VA: 0x7594bd86bc
	private Int32 <>xLuaBaseProxy_CompareDungeonFloat(SandboxV2DungeonFloatViewModel P0) { }
}
```