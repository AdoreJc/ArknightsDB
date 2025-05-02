# Act5D1ShopDetailCommonState

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1ShopDetailCommonStateBean _stateBean`

- `Act5D1ShopDetailView _view`

- `Act5D1ResourceBar _resourceBar`


## Methods

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1ShopDetailCommonState : PopupFloatState, IHotfixable
{
	private Act5D1ShopDetailCommonStateBean _stateBean; // 0x70
	private Act5D1ShopDetailView _view; // 0x78
	private Act5D1ResourceBar _resourceBar; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31d6940 VA: 0x75957ee940
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31d69a8 VA: 0x75957ee9a8
	protected override Void OnEnter() { }
	// RVA: 0x31d6a54 VA: 0x75957eea54
	protected override Void OnResume() { }
	// RVA: 0x31d6adc VA: 0x75957eeadc
	public Void .ctor() { }
	// RVA: 0x31d6b4c VA: 0x75957eeb4c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x31d6b54 VA: 0x75957eeb54
	private Void <>xLuaBaseProxy_OnResume() { }
}
```