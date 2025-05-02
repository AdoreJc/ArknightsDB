# UILayoutDimensionListener

**Namespace:** `Torappu.UI`


## Fields

- `Action eventOnPostLayout`


## Methods

- `Void add_eventOnPostLayout(Action)`

- `Void remove_eventOnPostLayout(Action)`

- `Void GraphicUpdateComplete()`

- `Void LayoutComplete()`

- `Void Rebuild(CanvasUpdate)`

- `Void DoOnceOnPostLayout(IAction)`

- `Void _SetDirty()`

- `Void _InvokePostLayoutCallback()`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnRectTransformDimensionsChange()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UILayoutDimensionListener : UIBehaviour, IHotfixable, ICanvasElement
{
	private ListSet`1 m_actionsWhenLayoutReady; // 0x18
	private Action eventOnPostLayout; // 0x20
	private static DelegateBridge __Hotfix0_add_eventOnPostLayout; // 0x0
	private static DelegateBridge __Hotfix0_remove_eventOnPostLayout; // 0x8
	private static DelegateBridge __Hotfix0_GraphicUpdateComplete; // 0x10
	private static DelegateBridge __Hotfix0_LayoutComplete; // 0x18
	private static DelegateBridge __Hotfix0_Rebuild; // 0x20
	private static DelegateBridge __Hotfix0_DoOnceOnPostLayout; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge __Hotfix0_OnRectTransformDimensionsChange; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0__SetDirty; // 0x48
	private static DelegateBridge __Hotfix0__InvokePostLayoutCallback; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58
	private static DelegateBridge __Hotfix0_UnityEngine.UI.ICanvasElement.get_transform; // 0x60


	// RVA: 0x21d8768 VA: 0x75947f0768
	public Void add_eventOnPostLayout(Action value) { }
	// RVA: 0x21d8844 VA: 0x75947f0844
	public Void remove_eventOnPostLayout(Action value) { }
	// RVA: 0x21d8920 VA: 0x75947f0920
	public Void GraphicUpdateComplete() { }
	// RVA: 0x21d8984 VA: 0x75947f0984
	public Void LayoutComplete() { }
	// RVA: 0x21d89e8 VA: 0x75947f09e8
	public Void Rebuild(CanvasUpdate executing) { }
	// RVA: 0x21d8b2c VA: 0x75947f0b2c
	public Void DoOnceOnPostLayout(IAction action) { }
	// RVA: 0x21d8bdc VA: 0x75947f0bdc
	protected override Void OnEnable() { }
	// RVA: 0x21d8d00 VA: 0x75947f0d00
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x21d8d74 VA: 0x75947f0d74
	protected override Void OnDestroy() { }
	// RVA: 0x21d8c50 VA: 0x75947f0c50
	private Void _SetDirty() { }
	// RVA: 0x21d8e18 VA: 0x75947f0e18
	private Void _InvokePostLayoutCallback() { }
	// RVA: 0x21d91e4 VA: 0x75947f11e4
	public Void .ctor() { }
	// RVA: 0x21d92a8 VA: 0x75947f12a8
	private Transform UnityEngine.UI.ICanvasElement.get_transform() { }
	// RVA: 0x21d9314 VA: 0x75947f1314
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x21d931c VA: 0x75947f131c
	private Void <>xLuaBaseProxy_OnRectTransformDimensionsChange() { }
	// RVA: 0x21d9324 VA: 0x75947f1324
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```