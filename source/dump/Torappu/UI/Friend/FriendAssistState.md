# FriendAssistState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `StateEngine _stateEngine`

- `FriendListStateBean _stateBean`

- `FriendStateControl _stateControl`

- `Input m_paramToSelectState`

- `Int32 m_cachedSelectIndex`


## Methods

- `Void ApplyFloatPanel(Int32, String, ItemType)`

- `Void HideFloatPanel()`

- `Void ApplySelect(Int32, String, ItemType)`

- `Void ToSelectState(Int32)`

- `Void <RegisterFromDataListener>b__14_0(IStateBean)`

- `Void <RegisterToDataListener>b__15_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistState : State
{
	private StateEngine _stateEngine; // 0x50
	private FriendListStateBean _stateBean; // 0x58
	private FriendStateControl _stateControl; // 0x60
	private Input m_paramToSelectState; // 0x68
	private Int32 m_cachedSelectIndex; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_ApplyFloatPanel; // 0x18
	private static DelegateBridge __Hotfix0_HideFloatPanel; // 0x20
	private static DelegateBridge __Hotfix0_ApplySelect; // 0x28
	private static DelegateBridge __Hotfix0_ToSelectState; // 0x30
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x38
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x40
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x28ada2c VA: 0x7594ec5a2c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28ada94 VA: 0x7594ec5a94
	protected override Void OnEnter() { }
	// RVA: 0x28adb88 VA: 0x7594ec5b88
	protected override Void OnExit() { }
	// RVA: 0x28adc08 VA: 0x7594ec5c08
	public Void ApplyFloatPanel(Int32 index, String id, ItemType type) { }
	// RVA: 0x28adcb8 VA: 0x7594ec5cb8
	public Void HideFloatPanel() { }
	// RVA: 0x28add7c VA: 0x7594ec5d7c
	public Void ApplySelect(Int32 index, String id, ItemType type) { }
	// RVA: 0x28ade5c VA: 0x7594ec5e5c
	public Void ToSelectState(Int32 index) { }
	// RVA: 0x28adefc VA: 0x7594ec5efc
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x28adf74 VA: 0x7594ec5f74
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x28ae0ec VA: 0x7594ec60ec
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x28ae264 VA: 0x7594ec6264
	public Void .ctor() { }
	// RVA: 0x28ae2dc VA: 0x7594ec62dc
	private Void <RegisterFromDataListener>b__14_0(IStateBean stateBean) { }
	// RVA: 0x28ae368 VA: 0x7594ec6368
	private Void <RegisterToDataListener>b__15_0(IStateBean stateBean) { }
	// RVA: 0x28ae770 VA: 0x7594ec6770
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x28ae778 VA: 0x7594ec6778
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x28ae780 VA: 0x7594ec6780
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x28ae788 VA: 0x7594ec6788
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x28ae790 VA: 0x7594ec6790
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```