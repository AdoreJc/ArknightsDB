# ClimbTowerEndingState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEndingView _endingView`

- `RectTransform _backBtn`

- `ClimbTowerEndingStateBean m_stateBean`

- `String m_currentTowerId`


## Methods

- `Void _OnJumpToTopState(IStateBean)`

- `Void OnClick()`

- `IEnumerator _ShowTopState()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndingState : PopupFadeState, IHotfixable
{
	private ClimbTowerEndingView _endingView; // 0x70
	private RectTransform _backBtn; // 0x78
	private ClimbTowerEndingStateBean m_stateBean; // 0x80
	private String m_currentTowerId; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToTopState; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge __Hotfix0__ShowTopState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2c9bc04 VA: 0x75952b3c04
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c9bc6c VA: 0x75952b3c6c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2c9bde4 VA: 0x75952b3de4
	protected override Void OnEnter() { }
	// RVA: 0x2c9c0cc VA: 0x75952b40cc
	protected override Void OnResume() { }
	// RVA: 0x2c9c4bc VA: 0x75952b44bc
	private Void _OnJumpToTopState(IStateBean stateBean) { }
	// RVA: 0x2c9c5e8 VA: 0x75952b45e8
	public Void OnClick() { }
	// RVA: 0x2c9c8c4 VA: 0x75952b48c4
	private IEnumerator _ShowTopState() { }
	// RVA: 0x2c9c998 VA: 0x75952b4998
	public Void .ctor() { }
	// RVA: 0x2c9caf0 VA: 0x75952b4af0
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2c9caf8 VA: 0x75952b4af8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c9cb00 VA: 0x75952b4b00
	private Void <>xLuaBaseProxy_OnResume() { }
}
```