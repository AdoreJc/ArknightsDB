# GlowingLoopTween

**Namespace:** ` `


## Fields

- `Tween m_cachedLoopTween`

- `CanvasGroup m_canvasGroup`

- `Single m_loopDuration`

- `Single m_alphaTarget`


## Methods

- `Void ShowGlowing(Boolean)`

- `Void _GenerateLoopTween()`

- `Void _ClearLoopTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GlowingLoopTween : IHotfixable
{
	private Tween m_cachedLoopTween; // 0x10
	private CanvasGroup m_canvasGroup; // 0x18
	private Single m_loopDuration; // 0x20
	private Single m_alphaTarget; // 0x24
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ShowGlowing; // 0x8
	private static DelegateBridge __Hotfix0__GenerateLoopTween; // 0x10
	private static DelegateBridge __Hotfix0__ClearLoopTween; // 0x18


	// RVA: 0x24e1ed8 VA: 0x7594af9ed8
	public Void .ctor(CanvasGroup canvasGroup, Single loopDuration, Single alphaTarget) { }
	// RVA: 0x24e1f90 VA: 0x7594af9f90
	public Void ShowGlowing(Boolean show) { }
	// RVA: 0x24e2020 VA: 0x7594afa020
	private Void _GenerateLoopTween() { }
	// RVA: 0x24e2164 VA: 0x7594afa164
	private Void _ClearLoopTween() { }
}
```