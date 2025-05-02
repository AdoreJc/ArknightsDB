# HandBookMapState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookCommonStateBean _stateBean`

- `GameObject _topMenu`

- `HandBookScrollView _scrollView`

- `CanvasGroup _canvasGroup`

- `Animator _animator`

- `UICommonTrackPoint _missionTrackPoint`

- `TrackPointViewProperty missionTrackPointProperty`

- `String m_cacheTargetCharId`

- `Boolean m_initFlag`

- `Tween m_cacheTween`


## Methods

- `Void OnEnemyHandBookClick()`

- `IEnumerator _OnFadeBack()`

- `Void CleanEffect()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _JumpFromOtherState(IStateBean)`

- `Void EventOpenMission()`

- `Void EventOnBtnCheckClick()`

- `Void <OnResume>b__14_0()`

- `Single <_OnFadeBack>b__15_0()`

- `Void <_OnFadeBack>b__15_1(Single)`

- `Void <_OnFadeBack>b__15_2()`

- `Void <RegisterToDataListener>b__20_0(IStateBean)`

- `Void <RegisterFromDataListener>b__23_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookMapState : State
{
	private HandBookCommonStateBean _stateBean; // 0x50
	private GameObject _topMenu; // 0x58
	private HandBookScrollView _scrollView; // 0x60
	private CanvasGroup _canvasGroup; // 0x68
	private Animator _animator; // 0x70
	private UICommonTrackPoint _missionTrackPoint; // 0x78
	public TrackPointViewProperty missionTrackPointProperty; // 0x80
	private const String FASTPLAY_FLAG; // 0x0
	private const String TRIGGER_FLAG; // 0x0
	private String m_cacheTargetCharId; // 0x88
	private Boolean m_initFlag; // 0x90
	private Tween m_cacheTween; // 0x98
	private static DelegateBridge __Hotfix0_OnEnemyHandBookClick; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__OnFadeBack; // 0x18
	private static DelegateBridge __Hotfix0_CleanEffect; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x38
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x40
	private static DelegateBridge __Hotfix0__JumpFromOtherState; // 0x48
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x50
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x58
	private static DelegateBridge __Hotfix0_EventOpenMission; // 0x60
	private static DelegateBridge __Hotfix0_EventOnBtnCheckClick; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2ea739c VA: 0x75954bf39c
	public Void OnEnemyHandBookClick() { }
	// RVA: 0x2ea74a8 VA: 0x75954bf4a8
	protected override Void OnEnter() { }
	// RVA: 0x2ea7514 VA: 0x75954bf514
	protected override Void OnResume() { }
	// RVA: 0x2ea78f4 VA: 0x75954bf8f4
	private IEnumerator _OnFadeBack() { }
	// RVA: 0x2ea79c8 VA: 0x75954bf9c8
	public Void CleanEffect() { }
	// RVA: 0x2ea7a3c VA: 0x75954bfa3c
	protected override Void OnExit() { }
	// RVA: 0x2ea7ab0 VA: 0x75954bfab0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ea7b18 VA: 0x75954bfb18
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x2ea7f78 VA: 0x75954bff78
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ea816c VA: 0x75954c016c
	private Void _JumpFromOtherState(IStateBean stateBean) { }
	// RVA: 0x2ea822c VA: 0x75954c022c
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2ea82a4 VA: 0x75954c02a4
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2ea8500 VA: 0x75954c0500
	public Void EventOpenMission() { }
	// RVA: 0x2ea860c VA: 0x75954c060c
	public Void EventOnBtnCheckClick() { }
	// RVA: 0x2ea8888 VA: 0x75954c0888
	public Void .ctor() { }
	// RVA: 0x2ea8938 VA: 0x75954c0938
	private Void <OnResume>b__14_0() { }
	// RVA: 0x2ea8954 VA: 0x75954c0954
	private Single <_OnFadeBack>b__15_0() { }
	// RVA: 0x2ea8970 VA: 0x75954c0970
	private Void <_OnFadeBack>b__15_1(Single val) { }
	// RVA: 0x2ea898c VA: 0x75954c098c
	private Void <_OnFadeBack>b__15_2() { }
	// RVA: 0x2ea89ac VA: 0x75954c09ac
	private Void <RegisterToDataListener>b__20_0(IStateBean stateBean) { }
	// RVA: 0x2ea8a64 VA: 0x75954c0a64
	private Void <RegisterFromDataListener>b__23_0(IStateBean stateBean) { }
	// RVA: 0x2ea8b40 VA: 0x75954c0b40
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ea8b48 VA: 0x75954c0b48
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2ea8b50 VA: 0x75954c0b50
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2ea8b58 VA: 0x75954c0b58
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2ea8b60 VA: 0x75954c0b60
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2ea8b68 VA: 0x75954c0b68
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```