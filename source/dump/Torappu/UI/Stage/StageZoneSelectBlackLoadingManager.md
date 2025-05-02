# StageZoneSelectBlackLoadingManager

**Namespace:** `Torappu.UI.Stage`


## Fields

- `FadeSwitchTween m_fadeSwitchTween`


## Properties

- `Boolean isShowing`


## Methods

- `Boolean get_isShowing()`

- `Void SetShow(Int64, Boolean)`

- `Void SetHide(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneSelectBlackLoadingManager : IHotfixable
{
	private FadeSwitchTween m_fadeSwitchTween; // 0x10
	private HashSet`1 m_showInstSet; // 0x18
	private static DelegateBridge __Hotfix0_get_isShowing; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_SetShow; // 0x10
	private static DelegateBridge __Hotfix0_SetHide; // 0x18

	public Boolean isShowing { get; }

	// RVA: 0x2fb04b0 VA: 0x75955c84b0
	public Boolean get_isShowing() { }
	// RVA: 0x2fb0548 VA: 0x75955c8548
	public Void .ctor(CanvasGroup alphaHandler) { }
	// RVA: 0x2fb0684 VA: 0x75955c8684
	public Void SetShow(Int64 instId, Boolean fastMode) { }
	// RVA: 0x2fb0790 VA: 0x75955c8790
	public Void SetHide(Int64 instId) { }
}
```