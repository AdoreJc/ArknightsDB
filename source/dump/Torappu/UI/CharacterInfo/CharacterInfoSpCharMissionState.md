# CharacterInfoSpCharMissionState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSpCharMissionView _view`

- `CharacterInfoSpCharMissionStateBean m_stateBean`

- `Boolean m_inited`


## Methods

- `Void _EventOnJumpToCharClicked(SpCharMissionCharViewModel)`

- `Void _EventOnGetRewardClicked(SpCharMissionObjViewModel)`

- `Void _InitIfNot()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void _ConsumeSpCharMissionNew()`

- `Void <_EventOnGetRewardClicked>b__6_0(GetSpCharMissionRewardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSpCharMissionState : PopupFloatState
{
	private CharacterInfoSpCharMissionView _view; // 0x70
	private CharacterInfoSpCharMissionStateBean m_stateBean; // 0x78
	private Boolean m_inited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__EventOnJumpToCharClicked; // 0x10
	private static DelegateBridge __Hotfix0__EventOnGetRewardClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__ConsumeSpCharMissionNew; // 0x30
	private static DelegateBridge __Hotfix0__TraceSpCharsMissionNew; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d4b348 VA: 0x7595363348
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d4b3b0 VA: 0x75953633b0
	protected override Void OnEnter() { }
	// RVA: 0x2d4b614 VA: 0x7595363614
	private Void _EventOnJumpToCharClicked(SpCharMissionCharViewModel charModel) { }
	// RVA: 0x2d4b6f8 VA: 0x75953636f8
	private Void _EventOnGetRewardClicked(SpCharMissionObjViewModel missionModel) { }
	// RVA: 0x2d4b454 VA: 0x7595363454
	private Void _InitIfNot() { }
	// RVA: 0x2d4b8fc VA: 0x75953638fc
	private IEnumerator _ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x2d4b5a4 VA: 0x75953635a4
	private Void _ConsumeSpCharMissionNew() { }
	// RVA: 0x2d4b9e4 VA: 0x75953639e4
	private IEnumerator`1 _TraceSpCharsMissionNew() { }
	// RVA: 0x2d4bab8 VA: 0x7595363ab8
	public Void .ctor() { }
	// RVA: 0x2d4bb68 VA: 0x7595363b68
	private Void <_EventOnGetRewardClicked>b__6_0(GetSpCharMissionRewardResponse response) { }
	// RVA: 0x2d4bbc8 VA: 0x7595363bc8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```