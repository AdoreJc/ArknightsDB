# FifthAnnivExploreGroupChooseConfirmDialog

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `CanvasGroup _canvasGroup`

- `UIRenderTextureImage _blurBkg`

- `FadeSwitchTween _fadeSwitchTween`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void OnConfirmBtnClick()`

- `Void OnCancelBtnClick()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreGroupChooseConfirmDialog : UICompDialog`1
{
	private CanvasGroup _canvasGroup; // 0x48
	private UIRenderTextureImage _blurBkg; // 0x50
	private FadeSwitchTween _fadeSwitchTween; // 0x58
	private Boolean m_isInited; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_OnCancelBtnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x291a268 VA: 0x7594f32268
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x291a2d0 VA: 0x7594f322d0
	private Void _InitIfNot() { }
	// RVA: 0x291a3b4 VA: 0x7594f323b4
	protected override Void OnRender(Options input) { }
	// RVA: 0x291a448 VA: 0x7594f32448
	public Void OnConfirmBtnClick() { }
	// RVA: 0x291a51c VA: 0x7594f3251c
	public Void OnCancelBtnClick() { }
	// RVA: 0x291a5f0 VA: 0x7594f325f0
	public Void .ctor() { }
	// RVA: 0x291a680 VA: 0x7594f32680
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```