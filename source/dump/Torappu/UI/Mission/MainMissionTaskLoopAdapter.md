# MainMissionTaskLoopAdapter

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MainMissionTask taskPrefab`

- `MainMissionLockedTask lockedTaskPrefab`

- `BranchWrappedGroup wrappedModel`

- `UIStringEvent onSpreadFold`

- `UIStringEvent onHideFold`


## Methods

- `Void NotifyRebuild()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MainMissionTaskLoopAdapter : UIRecycleLayoutAdapter
{
	public List`1 m_virtualViewList; // 0x18
	public MainMissionTask taskPrefab; // 0x20
	public MainMissionLockedTask lockedTaskPrefab; // 0x28
	public BranchWrappedGroup wrappedModel; // 0x30
	public UIStringEvent onSpreadFold; // 0x38
	public UIStringEvent onHideFold; // 0x40
	private static DelegateBridge __Hotfix0_NotifyRebuild; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x273e18c VA: 0x7594d5618c
	public Void NotifyRebuild() { }
	// RVA: 0x273f3dc VA: 0x7594d573dc
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x273ce84 VA: 0x7594d54e84
	public Void .ctor() { }
}
```