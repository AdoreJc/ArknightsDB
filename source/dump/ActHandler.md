# ActHandler

**Namespace:** ` `


## Fields

- `EnemyDuelEntryPage m_entryPage`


## Methods

- `Void _GenLifeCycleModel(Action`2)`

- `Void _GenMedalViewModel(Action`2)`

- `Void _GenMilestoneViewModel(Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ActHandler : ActivityEntryPageHandler
{
	private EnemyDuelEntryPage m_entryPage; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x8
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x10
	private static DelegateBridge __Hotfix0__GenLifeCycleModel; // 0x18
	private static DelegateBridge __Hotfix0__GenMedalViewModel; // 0x20
	private static DelegateBridge __Hotfix0__GenMilestoneViewModel; // 0x28
	private static DelegateBridge __Hotfix0_TriggerEntryEnterAnim; // 0x30
	private static DelegateBridge __Hotfix0_ResetEntryToState; // 0x38


	// RVA: 0x29460e4 VA: 0x7594f5e0e4
	public Void .ctor(EnemyDuelEntryPage page) { }
	// RVA: 0x29463c0 VA: 0x7594f5e3c0
	protected override Void InitModelDict(Action`2 initViewModel) { }
	// RVA: 0x2946878 VA: 0x7594f5e878
	protected override Void OnRefreshData() { }
	// RVA: 0x2946458 VA: 0x7594f5e458
	private Void _GenLifeCycleModel(Action`2 initViewModel) { }
	// RVA: 0x29465b0 VA: 0x7594f5e5b0
	private Void _GenMedalViewModel(Action`2 initViewModel) { }
	// RVA: 0x29466fc VA: 0x7594f5e6fc
	private Void _GenMilestoneViewModel(Action`2 initViewModel) { }
	// RVA: 0x2946b28 VA: 0x7594f5eb28
	protected override Void TriggerEntryEnterAnim(Action onAnimFinish) { }
	// RVA: 0x2946ee4 VA: 0x7594f5eee4
	protected override Void ResetEntryToState(Boolean isShow) { }
}
```