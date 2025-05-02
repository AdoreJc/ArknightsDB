# SandboxV2LogisticsHomeState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _backRectTransform`

- `SandboxV2LogisticsTotalBuffInfoView _totalBuffInfoView`

- `SandboxV2LogisticsCharBuffInfoView _charBuffInfoView`

- `SandboxV2LogisticsSquadView _squadView`

- `SandboxV2LogisticsHomeStateBean m_stateBean`

- `OpenOption m_cachedOpenOption`

- `Boolean m_isInited`

- `Coroutine m_tutorialCoroutine`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnBackClicked()`

- `Void OnDrinkBtnClicked()`

- `Void OnRemoveCharBtnClicked()`

- `Void OnUpdateSquadBtnClicked()`

- `Void _InitIfNot()`

- `Void _OnBackPressed()`

- `Void _OnJumpToCharSelectState(IStateBean)`

- `Void _OnSquadItemClicked(Int32)`

- `Void _OnSquadBlockItemClicked()`

- `Void _OnRemoveCharDialogConfirmed(Int32)`

- `Void _TryToOpenSelectCharState(Int32)`

- `Void _ReLoadDataAndRefresh()`

- `Void _TryRaiseTutorialSignal()`

- `IEnumerator _CoroutineTriggerTutorial()`

- `Void _StopTutorialCoroutine()`

- `Void <_OnRemoveCharDialogConfirmed>b__25_0(SandboxV2RemoveSupplyResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsHomeState : State, IValueMsgReceiver
{
	public const Int32 MSG_ON_SQUAD_ITEM_CLICKED; // 0x0
	public const Int32 MSG_ON_SQUAD_BLOCK_ITEM_CLICKED; // 0x0
	public RectTransform _backRectTransform; // 0x50
	private SandboxV2LogisticsTotalBuffInfoView _totalBuffInfoView; // 0x58
	private SandboxV2LogisticsCharBuffInfoView _charBuffInfoView; // 0x60
	private SandboxV2LogisticsSquadView _squadView; // 0x68
	private SandboxV2LogisticsHomeStateBean m_stateBean; // 0x70
	private OpenOption m_cachedOpenOption; // 0x78
	private Boolean m_isInited; // 0xd0
	private Coroutine m_tutorialCoroutine; // 0xd8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnDrinkBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnRemoveCharBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnUpdateSquadBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpToCharSelectState; // 0x60
	private static DelegateBridge __Hotfix0__OnSquadItemClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnSquadBlockItemClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnRemoveCharDialogConfirmed; // 0x78
	private static DelegateBridge __Hotfix0__TryToOpenSelectCharState; // 0x80
	private static DelegateBridge __Hotfix0__ReLoadDataAndRefresh; // 0x88
	private static DelegateBridge __Hotfix0__TryRaiseTutorialSignal; // 0x90
	private static DelegateBridge __Hotfix0__CoroutineTriggerTutorial; // 0x98
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x25d8698 VA: 0x7594bf0698
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25d86fc VA: 0x7594bf06fc
	protected override Void OnEnter() { }
	// RVA: 0x25d8a5c VA: 0x7594bf0a5c
	protected override Void OnResume() { }
	// RVA: 0x25d8c60 VA: 0x7594bf0c60
	protected override Void OnPause() { }
	// RVA: 0x25d8d7c VA: 0x7594bf0d7c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x25d90c8 VA: 0x7594bf10c8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x25d9240 VA: 0x7594bf1240
	public Void OnBackClicked() { }
	// RVA: 0x25d939c VA: 0x7594bf139c
	public Void OnDrinkBtnClicked() { }
	// RVA: 0x25d9608 VA: 0x7594bf1608
	public Void OnRemoveCharBtnClicked() { }
	// RVA: 0x25d9e30 VA: 0x7594bf1e30
	public Void OnUpdateSquadBtnClicked() { }
	// RVA: 0x25d8850 VA: 0x7594bf0850
	private Void _InitIfNot() { }
	// RVA: 0x25d92a8 VA: 0x7594bf12a8
	private Void _OnBackPressed() { }
	// RVA: 0x25da12c VA: 0x7594bf212c
	private Void _OnJumpToCharSelectState(IStateBean stateBean) { }
	// RVA: 0x25d8e44 VA: 0x7594bf0e44
	private Void _OnSquadItemClicked(Int32 index) { }
	// RVA: 0x25d8fe8 VA: 0x7594bf0fe8
	private Void _OnSquadBlockItemClicked() { }
	// RVA: 0x25da51c VA: 0x7594bf251c
	private Void _OnRemoveCharDialogConfirmed(Int32 charInstId) { }
	// RVA: 0x25d9e9c VA: 0x7594bf1e9c
	private Void _TryToOpenSelectCharState(Int32 selectedIndex) { }
	// RVA: 0x25d8af4 VA: 0x7594bf0af4
	private Void _ReLoadDataAndRefresh() { }
	// RVA: 0x25d8bb8 VA: 0x7594bf0bb8
	private Void _TryRaiseTutorialSignal() { }
	// RVA: 0x25dae60 VA: 0x7594bf2e60
	private IEnumerator _CoroutineTriggerTutorial() { }
	// RVA: 0x25d8cd4 VA: 0x7594bf0cd4
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x25daf24 VA: 0x7594bf2f24
	public Void .ctor() { }
	// RVA: 0x25db07c VA: 0x7594bf307c
	private Void <_OnRemoveCharDialogConfirmed>b__25_0(SandboxV2RemoveSupplyResponse response) { }
	// RVA: 0x25db080 VA: 0x7594bf3080
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25db088 VA: 0x7594bf3088
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x25db090 VA: 0x7594bf3090
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x25db098 VA: 0x7594bf3098
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```