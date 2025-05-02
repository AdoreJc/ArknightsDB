# SixStarRuneSelectViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String stageId`

- `String milestoneGroupId`

- `Boolean showTrackPoint`

- `Int32 totalGotPoint`

- `Int32 maxPoint`

- `Int32 currPoint`

- `String nextRewardTip`

- `Boolean showNextTip`

- `UIItemViewModel nextRewardItem`


## Methods

- `Void LoadData(String, String)`

- `Void RefreshPlayerData()`

- `Void SetGroupLocked(Int32)`

- `Void SetGroupUnlock(Int32)`

- `SixStarRuneSelectGroupViewModel GetGroupModel(Int32)`

- `Void _UpdateCompleteStatus(PlayerDungeon)`

- `Void _UpdateCurrPoint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarRuneSelectViewModel : IHotfixable
{
	public String stageId; // 0x10
	public String milestoneGroupId; // 0x18
	public Boolean showTrackPoint; // 0x20
	public Int32 totalGotPoint; // 0x24
	public Int32 maxPoint; // 0x28
	public Int32 currPoint; // 0x2c
	public String nextRewardTip; // 0x30
	public Boolean showNextTip; // 0x38
	public UIItemViewModel nextRewardItem; // 0x40
	public List`1 runeGroupModel; // 0x48
	private List`1 m_milestoneRewardPointList; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_SetGroupLocked; // 0x10
	private static DelegateBridge __Hotfix0_SetGroupUnlock; // 0x18
	private static DelegateBridge __Hotfix0_GetGroupModel; // 0x20
	private static DelegateBridge __Hotfix0__UpdateCompleteStatus; // 0x28
	private static DelegateBridge __Hotfix0__UpdateCurrPoint; // 0x30
	private static DelegateBridge __Hotfix0__LoadRuneData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2f4da34 VA: 0x7595565a34
	public Void LoadData(String stageId, String groupId) { }
	// RVA: 0x2f4e30c VA: 0x759556630c
	public Void RefreshPlayerData() { }
	// RVA: 0x2f4f0fc VA: 0x75955670fc
	public Void SetGroupLocked(Int32 minLevel) { }
	// RVA: 0x2f4eff8 VA: 0x7595566ff8
	public Void SetGroupUnlock(Int32 minLevel) { }
	// RVA: 0x2f4eee4 VA: 0x7595566ee4
	public SixStarRuneSelectGroupViewModel GetGroupModel(Int32 level) { }
	// RVA: 0x2f50bc0 VA: 0x7595568bc0
	private Void _UpdateCompleteStatus(PlayerDungeon playerData) { }
	// RVA: 0x2f50d10 VA: 0x7595568d10
	private Void _UpdateCurrPoint() { }
	// RVA: 0x2f508a0 VA: 0x75955688a0
	private static SixStarRuneSelectGroupViewModel _LoadRuneData(Int32 level, List`1 runeIdList, Dictionary`2 runeDataMap) { }
	// RVA: 0x2f510a0 VA: 0x75955690a0
	public Void .ctor() { }
}
```