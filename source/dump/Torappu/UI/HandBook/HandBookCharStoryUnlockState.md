# HandBookCharStoryUnlockState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookCharStoryUnlockStateBean _stateBean`

- `Text _textTitle`

- `Text _textTip`


## Methods

- `Void _RenderView()`

- `Void _SetTopMenuActive(Boolean)`

- `Void CloseAndShowItem()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookCharStoryUnlockState : PopupFloatState
{
	private HandBookCharStoryUnlockStateBean _stateBean; // 0x70
	private Text _textTitle; // 0x78
	private Text _textTip; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__RenderView; // 0x10
	private static DelegateBridge __Hotfix0__SetTopMenuActive; // 0x18
	private static DelegateBridge __Hotfix0_CloseAndShowItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2e9ef68 VA: 0x75954b6f68
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e9efd0 VA: 0x75954b6fd0
	protected override Void OnEnter() { }
	// RVA: 0x2e9f490 VA: 0x75954b7490
	private Void _RenderView() { }
	// RVA: 0x2e9f678 VA: 0x75954b7678
	private Void _SetTopMenuActive(Boolean isActive) { }
	// RVA: 0x2e9f7a8 VA: 0x75954b77a8
	public Void CloseAndShowItem() { }
	// RVA: 0x2e9f9dc VA: 0x75954b79dc
	public Void .ctor() { }
	// RVA: 0x2e9fa4c VA: 0x75954b7a4c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```