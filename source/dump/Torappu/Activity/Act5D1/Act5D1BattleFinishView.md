# Act5D1BattleFinishView

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `RuneBattleFinishHolder _holder`

- `RuneBattleFinishEffView _effView`

- `RuneBattleFinishStateBean _stateBean`

- `Boolean m_isLoadingAnimEnd`

- `Single m_animEndTime`


## Methods

- `IEnumerator _PlayAnim()`

- `Void EventOnPageClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1BattleFinishView : ActivityBattleFinishView
{
	private RuneBattleFinishHolder _holder; // 0x30
	private RuneBattleFinishEffView _effView; // 0x38
	private RuneBattleFinishStateBean _stateBean; // 0x40
	private const Single CLOSE_VIEW_DELAY; // 0x0
	private Boolean m_isLoadingAnimEnd; // 0x48
	private Single m_animEndTime; // 0x4c
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0_EventOnPageClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31c68b8 VA: 0x75957de8b8
	protected override Void OnInit() { }
	// RVA: 0x31c74a8 VA: 0x75957df4a8
	private IEnumerator _PlayAnim() { }
	// RVA: 0x31c757c VA: 0x75957df57c
	public Void EventOnPageClicked() { }
	// RVA: 0x31c7694 VA: 0x75957df694
	public Void .ctor() { }
}
```