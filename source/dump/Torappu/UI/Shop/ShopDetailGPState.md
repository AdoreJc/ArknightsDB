# ShopDetailGPState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `UIItemViewModel m_cachedItemViewModel`


## Methods

- `Void _ToChoosePreviewState(IStateBean)`

- `Void _ToEvolvePreviewState(IStateBean)`

- `Void _ToPlayerAvatarDisplayState(IStateBean)`

- `Void EventOnPreviewBtnClick(String)`

- `Void _TryOpenPreviewState(UIItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailGPState : ShopDetailCommonState
{
	private UIItemViewModel m_cachedItemViewModel; // 0x78
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x0
	private static DelegateBridge __Hotfix0__ToChoosePreviewState; // 0x8
	private static DelegateBridge __Hotfix0__ToEvolvePreviewState; // 0x10
	private static DelegateBridge __Hotfix0__ToPlayerAvatarDisplayState; // 0x18
	private static DelegateBridge __Hotfix0_EventOnPreviewBtnClick; // 0x20
	private static DelegateBridge __Hotfix0__TryOpenPreviewState; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2437364 VA: 0x7594a4f364
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x24375c8 VA: 0x7594a4f5c8
	private Void _ToChoosePreviewState(IStateBean stateBean) { }
	// RVA: 0x24376f0 VA: 0x7594a4f6f0
	private Void _ToEvolvePreviewState(IStateBean stateBean) { }
	// RVA: 0x24377cc VA: 0x7594a4f7cc
	private Void _ToPlayerAvatarDisplayState(IStateBean stateBean) { }
	// RVA: 0x24378ac VA: 0x7594a4f8ac
	public Void EventOnPreviewBtnClick(String itemId) { }
	// RVA: 0x2437a1c VA: 0x7594a4fa1c
	private Void _TryOpenPreviewState(UIItemViewModel itemViewModel) { }
	// RVA: 0x2437dbc VA: 0x7594a4fdbc
	public Void .ctor() { }
	// RVA: 0x2437e28 VA: 0x7594a4fe28
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```