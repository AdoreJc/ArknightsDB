# TuningHomeViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String actId`

- `String nextTimeDesc`

- `Boolean showRemainTime`

- `Int32 entryAnimSequence`

- `Boolean showArchiveEntry`

- `TuningHomeMajorInvestViewModel majorInvestModel`

- `TuningHomeHiddenInvestViewModel hiddenInvestModel`

- `TuningHomeNormalInvestGroupViewModel normalInvestGroupModel`

- `Int64 m_actEndTs`


## Methods

- `Void LoadData(String)`

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeViewModel : IHotfixable
{
	public List`1 fragList; // 0x10
	public String actId; // 0x18
	public String nextTimeDesc; // 0x20
	public Boolean showRemainTime; // 0x28
	public Int32 entryAnimSequence; // 0x2c
	public Boolean showArchiveEntry; // 0x30
	public TuningHomeMajorInvestViewModel majorInvestModel; // 0x38
	public TuningHomeHiddenInvestViewModel hiddenInvestModel; // 0x40
	public TuningHomeNormalInvestGroupViewModel normalInvestGroupModel; // 0x48
	private Int64 m_actEndTs; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x232ac64 VA: 0x7594942c64
	public Void LoadData(String activityId) { }
	// RVA: 0x232b04c VA: 0x759494304c
	public Void RefreshPlayerData() { }
	// RVA: 0x232b398 VA: 0x7594943398
	public Void .ctor() { }
}
```