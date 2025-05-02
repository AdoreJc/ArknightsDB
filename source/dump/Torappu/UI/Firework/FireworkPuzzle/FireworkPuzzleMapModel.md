# FireworkPuzzleMapModel

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `String actId`

- `Boolean mapAnimActive`

- `Int32 puzzleCompletedCount`

- `Int32 puzzleTotalCount`

- `Int32 focusSeqNum`

- `Single focusXAxis`

- `String puzzleListDesc`

- `Int32 puzzleDailyRewardNum`

- `String m_cachedMapAnimGroupId`


## Methods

- `Void LoadData(String, List`1)`

- `Void RefreshData(String, List`1)`

- `Boolean IsPuzzleUnlock(String)`

- `Void SetFocusPuzzle(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleMapModel : IHotfixable
{
	public String actId; // 0x10
	public ListDict`2 itemDict; // 0x18
	public Dictionary`2 groupDict; // 0x20
	public Boolean mapAnimActive; // 0x28
	public Int32 puzzleCompletedCount; // 0x2c
	public Int32 puzzleTotalCount; // 0x30
	public Int32 focusSeqNum; // 0x34
	public Single focusXAxis; // 0x38
	public String puzzleListDesc; // 0x40
	public Int32 puzzleDailyRewardNum; // 0x48
	private String m_cachedMapAnimGroupId; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0_IsPuzzleUnlock; // 0x10
	private static DelegateBridge __Hotfix0_SetFocusPuzzle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28f5db4 VA: 0x7594f0ddb4
	public Void LoadData(String actId, List`1 unlockedPuzzleList) { }
	// RVA: 0x28f64c0 VA: 0x7594f0e4c0
	public Void RefreshData(String actId, List`1 unlockedPuzzleList) { }
	// RVA: 0x28f6b90 VA: 0x7594f0eb90
	public Boolean IsPuzzleUnlock(String puzzleId) { }
	// RVA: 0x28f6a60 VA: 0x7594f0ea60
	public Void SetFocusPuzzle(String puzzleId) { }
	// RVA: 0x28f6c68 VA: 0x7594f0ec68
	public Void .ctor() { }
}
```