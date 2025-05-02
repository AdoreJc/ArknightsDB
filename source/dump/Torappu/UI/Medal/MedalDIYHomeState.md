# MedalDIYHomeState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `UIMedalDIYManager _manager`

- `RectTransform _btnBack`

- `MedalDIYHomeBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnResetClicked()`

- `Void EventOnAddClicked()`

- `Void EventOnSaveClicked()`

- `Void EventOnPreviewClicked()`

- `Void EventOnBackClicked()`

- `Void _OnRouteToPreview(MedalDIYPreviewBean)`

- `Void _OnRouteToSelectState(MedalListStateBean)`

- `Void _OnBackFromSelectState(MedalListStateBean)`

- `Void _ResetAllTokens()`

- `Boolean _CheckIfToStayToSave(Action)`

- `Boolean _CheckIfEditingTokenDirty()`

- `Void _SendSaveCustomDataRequest()`

- `MedalSetCustomDataRequest _CreateSetCustomDataRequest()`

- `Void <RegisterToDataListener>b__7_0(IStateBean)`

- `Void <RegisterToDataListener>b__7_1(IStateBean)`

- `Void <RegisterFromDataListener>b__9_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalDIYHomeState : State
{
	private UIMedalDIYManager _manager; // 0x50
	private RectTransform _btnBack; // 0x58
	private MedalDIYHomeBean m_stateBean; // 0x60
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_EventOnResetClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnAddClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnSaveClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnPreviewClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnRouteToPreview; // 0x58
	private static DelegateBridge __Hotfix0__OnRouteToSelectState; // 0x60
	private static DelegateBridge __Hotfix0__OnBackFromSelectState; // 0x68
	private static DelegateBridge __Hotfix0__ResetAllTokens; // 0x70
	private static DelegateBridge __Hotfix0__CheckIfToStayToSave; // 0x78
	private static DelegateBridge __Hotfix0__CheckIfEditingTokenDirty; // 0x80
	private static DelegateBridge __Hotfix0__SendSaveCustomDataRequest; // 0x88
	private static DelegateBridge __Hotfix0__CreateSetCustomDataRequest; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x2763b7c VA: 0x7594d7bb7c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2763be4 VA: 0x7594d7bbe4
	private Void _InitIfNot() { }
	// RVA: 0x2763cfc VA: 0x7594d7bcfc
	protected override Void OnEnter() { }
	// RVA: 0x2763e98 VA: 0x7594d7be98
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x276408c VA: 0x7594d7c08c
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2764104 VA: 0x7594d7c104
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x276427c VA: 0x7594d7c27c
	public Void EventOnResetClicked() { }
	// RVA: 0x2764548 VA: 0x7594d7c548
	public Void EventOnAddClicked() { }
	// RVA: 0x2764660 VA: 0x7594d7c660
	public Void EventOnSaveClicked() { }
	// RVA: 0x2764928 VA: 0x7594d7c928
	public Void EventOnPreviewClicked() { }
	// RVA: 0x2764a40 VA: 0x7594d7ca40
	public Void EventOnBackClicked() { }
	// RVA: 0x2764ca0 VA: 0x7594d7cca0
	private Void _OnRouteToPreview(MedalDIYPreviewBean stateBean) { }
	// RVA: 0x2764d4c VA: 0x7594d7cd4c
	private Void _OnRouteToSelectState(MedalListStateBean listBean) { }
	// RVA: 0x2764e4c VA: 0x7594d7ce4c
	private Void _OnBackFromSelectState(MedalListStateBean listBean) { }
	// RVA: 0x27644b8 VA: 0x7594d7c4b8
	private Void _ResetAllTokens() { }
	// RVA: 0x2764b38 VA: 0x7594d7cb38
	private Boolean _CheckIfToStayToSave(Action actionExit) { }
	// RVA: 0x2764fd0 VA: 0x7594d7cfd0
	private Boolean _CheckIfEditingTokenDirty() { }
	// RVA: 0x27646c8 VA: 0x7594d7c6c8
	private Void _SendSaveCustomDataRequest() { }
	// RVA: 0x27650ac VA: 0x7594d7d0ac
	private MedalSetCustomDataRequest _CreateSetCustomDataRequest() { }
	// RVA: 0x276534c VA: 0x7594d7d34c
	public Void .ctor() { }
	// RVA: 0x27653f8 VA: 0x7594d7d3f8
	private Void <RegisterToDataListener>b__7_0(IStateBean stateBean) { }
	// RVA: 0x2765478 VA: 0x7594d7d478
	private Void <RegisterToDataListener>b__7_1(IStateBean stateBean) { }
	// RVA: 0x27654f8 VA: 0x7594d7d4f8
	private Void <RegisterFromDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x2765578 VA: 0x7594d7d578
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2765580 VA: 0x7594d7d580
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2765588 VA: 0x7594d7d588
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2765590 VA: 0x7594d7d590
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```