# ActVecBreakOffenseEntryViewModel

**Namespace:** `Torappu.Activity.ActVecBreak`


## Fields

- `String actId`

- `Int32 curLevel`

- `Int32 curStatusTotalLevel`

- `Int32 totalLevel`

- `String curUnlockZoneName`

- `VecBreakOffenseStatus curStatus`

- `VecBreakOffenseStageModel m_tempOffenseStageModel`


## Properties

- `Boolean hasNew`


## Methods

- `Boolean get_hasNew()`

- `Void LoadData()`

- `Void _UpdateOffenseLevelState(ActVecBreakData, PlayerVecBreakActivity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakOffenseEntryViewModel : TemplateActivityViewModel, IHotfixable
{
	public String actId; // 0x20
	public Int32 curLevel; // 0x28
	public Int32 curStatusTotalLevel; // 0x2c
	public Int32 totalLevel; // 0x30
	public String curUnlockZoneName; // 0x38
	public VecBreakOffenseStatus curStatus; // 0x40
	private VecBreakOffenseStageModel m_tempOffenseStageModel; // 0x48
	private static DelegateBridge __Hotfix0_get_hasNew; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__UpdateOffenseLevelState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean hasNew { get; }

	// RVA: 0x30d70b4 VA: 0x75956ef0b4
	public Boolean get_hasNew() { }
	// RVA: 0x30d7120 VA: 0x75956ef120
	public Void LoadData() { }
	// RVA: 0x30d7258 VA: 0x75956ef258
	private Void _UpdateOffenseLevelState(ActVecBreakData actData, PlayerVecBreakActivity actPlayerData) { }
	// RVA: 0x30d7588 VA: 0x75956ef588
	public Void .ctor(Object param) { }
}
```