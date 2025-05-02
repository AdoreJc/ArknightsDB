# BossRushRelicNodeModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String relicId`

- `Int32 relicLevel`

- `Int32 maxLevel`

- `Boolean showNewPart`

- `RELIC_STATE relicState`

- `Boolean selecting`

- `Int32 upgradeNeed`

- `RelicInfo relicInfo`

- `Boolean playSelectAnim`

- `Boolean playUnSelectAnim`

- `RelicData relicData`

- `RelicLevelInfoData relicLevelInfoData`


## Methods

- `Void InitData(RelicData, RelicLevelInfoData)`

- `Void UpdateData(RelicInfo, Boolean)`

- `Void UpdateSelect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushRelicNodeModel : IHotfixable
{
	public String relicId; // 0x10
	public Int32 relicLevel; // 0x18
	public Int32 maxLevel; // 0x1c
	public Boolean showNewPart; // 0x20
	public RELIC_STATE relicState; // 0x24
	public Boolean selecting; // 0x28
	public Int32 upgradeNeed; // 0x2c
	public RelicInfo relicInfo; // 0x30
	public Boolean playSelectAnim; // 0x38
	public Boolean playUnSelectAnim; // 0x39
	public RelicData relicData; // 0x40
	public RelicLevelInfoData relicLevelInfoData; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2e609ec VA: 0x75954789ec
	public Void InitData(RelicData relicData, RelicLevelInfoData relicLevelInfoData) { }
	// RVA: 0x2e60adc VA: 0x7595478adc
	public Void UpdateData(RelicInfo data, Boolean refreshSelect) { }
	// RVA: 0x2e60d40 VA: 0x7595478d40
	public Void UpdateSelect(String selectingRelicId) { }
	// RVA: 0x2e60df0 VA: 0x7595478df0
	public Void .ctor() { }
}
```