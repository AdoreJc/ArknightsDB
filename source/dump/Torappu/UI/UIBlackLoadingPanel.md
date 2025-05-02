# UIBlackLoadingPanel

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _alphaHandler`

- `Tween m_sharedTween`


## Methods

- `Void _ResetSharedTween()`

- `IEnumerator <>xLuaBaseProxy_ShowEffect()`

- `IEnumerator <>xLuaBaseProxy_HideEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBlackLoadingPanel : UIReentrantFloatPanel
{
	private CanvasGroup _alphaHandler; // 0x20
	private Tween m_sharedTween; // 0x28
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x0
	private static DelegateBridge __Hotfix0_HideEffect; // 0x8
	private static DelegateBridge __Hotfix0__ResetSharedTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x22415fc VA: 0x75948595fc
	protected override IEnumerator ShowEffect() { }
	// RVA: 0x22416d0 VA: 0x75948596d0
	protected override IEnumerator HideEffect() { }
	// RVA: 0x22417a4 VA: 0x75948597a4
	private Void _ResetSharedTween() { }
	// RVA: 0x2241854 VA: 0x7594859854
	public Void .ctor() { }
	// RVA: 0x22418c4 VA: 0x75948598c4
	private IEnumerator <>xLuaBaseProxy_ShowEffect() { }
	// RVA: 0x22418cc VA: 0x75948598cc
	private IEnumerator <>xLuaBaseProxy_HideEffect() { }
}
```