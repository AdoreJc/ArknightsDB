# TuningProductBagState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductBagView _bagView`

- `Transform _topMenuContainer`

- `Boolean m_isInited`

- `TuningProductBagStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _OnSelectProductType(String)`

- `Void _TransToProductState(IStateBean)`

- `Void _OnBackPress()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagState : PopupFadeState
{
	private TuningProductBagView _bagView; // 0x70
	private Transform _topMenuContainer; // 0x78
	private Boolean m_isInited; // 0x80
	private TuningProductBagStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnSelectProductType; // 0x20
	private static DelegateBridge __Hotfix0__TransToProductState; // 0x28
	private static DelegateBridge __Hotfix0__OnBackPress; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x23412bc VA: 0x75949592bc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2341324 VA: 0x7594959324
	protected override Void OnEnter() { }
	// RVA: 0x23416f8 VA: 0x75949596f8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2341458 VA: 0x7594959458
	private Void _InitIfNot() { }
	// RVA: 0x2341870 VA: 0x7594959870
	private Void _OnSelectProductType(String productTypeId) { }
	// RVA: 0x2341a64 VA: 0x7594959a64
	private Void _TransToProductState(IStateBean stateBean) { }
	// RVA: 0x2341b40 VA: 0x7594959b40
	private Void _OnBackPress() { }
	// RVA: 0x2341c54 VA: 0x7594959c54
	public Void .ctor() { }
	// RVA: 0x2341dac VA: 0x7594959dac
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2341db4 VA: 0x7594959db4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```