# HandBookV2GroupMapState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2GroupMapStateBean _stateBean`

- `RectTransform _viewContent`

- `HandBookV2MapGroupHolder _holder`

- `HandBookV2MapCardView m_cacheCard`

- `String m_cacheForceId`


## Methods

- `Void ToOtherGroupByForceId(String)`

- `Void OnClick(HandBookV2MapCardView)`

- `Void <RegisterToDataListener>b__9_0(IStateBean)`

- `Void <RegisterToDataListener>b__9_1(IStateBean)`

- `Void <RegisterFromDataListener>b__11_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2GroupMapState : PopupFadeState
{
	private HandBookV2GroupMapStateBean _stateBean; // 0x70
	private RectTransform _viewContent; // 0x78
	private HandBookV2MapGroupHolder _holder; // 0x80
	private HandBookV2MapCardView m_cacheCard; // 0x88
	private String m_cacheForceId; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnExit; // 0x8
	private static DelegateBridge __Hotfix0_ToOtherGroupByForceId; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2eca304 VA: 0x75954e2304
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2eca36c VA: 0x75954e236c
	protected override Void OnExit() { }
	// RVA: 0x2eca40c VA: 0x75954e240c
	public Void ToOtherGroupByForceId(String forceId) { }
	// RVA: 0x2eca4d0 VA: 0x75954e24d0
	public Void OnClick(HandBookV2MapCardView cardView) { }
	// RVA: 0x2eca668 VA: 0x75954e2668
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2eca85c VA: 0x75954e285c
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2eca8d4 VA: 0x75954e28d4
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2ecaa4c VA: 0x75954e2a4c
	public Void .ctor() { }
	// RVA: 0x2ecaabc VA: 0x75954e2abc
	private Void <RegisterToDataListener>b__9_0(IStateBean stateBean) { }
	// RVA: 0x2ecad68 VA: 0x75954e2d68
	private Void <RegisterToDataListener>b__9_1(IStateBean stateBean) { }
	// RVA: 0x2ecae4c VA: 0x75954e2e4c
	private Void <RegisterFromDataListener>b__11_0(IStateBean stateBean) { }
	// RVA: 0x2ecafcc VA: 0x75954e2fcc
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2ecafd4 VA: 0x75954e2fd4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2ecafdc VA: 0x75954e2fdc
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2ecafe4 VA: 0x75954e2fe4
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```