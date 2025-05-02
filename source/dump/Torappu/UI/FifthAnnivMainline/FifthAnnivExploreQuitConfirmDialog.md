# FifthAnnivExploreQuitConfirmDialog

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `CanvasGroup _canvasGroup`

- `UIRenderTextureImage _blurBkg`

- `GameObject _restartObj`

- `CanvasGroup _quitCanvasGroup`

- `CanvasGroup _restartCanvasGroup`

- `FadeSwitchTween m_mainFadeSwitchTween`

- `FadeSwitchTween m_quitFadeSwitchTween`

- `FadeSwitchTween m_restartFadeSwitchTween`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `FifthAnnivExploreMapController m_mapController`

- `Boolean m_needRestartBtn`

- `Boolean m_isShowingRestart`

- `Int32 m_restartConfirmInstId`


## Methods

- `Void _InitIfNot()`

- `Void _LoadData()`

- `Boolean _CheckNeedRestartBtn()`

- `Void Render()`

- `Void OnConfirmBtnClick()`

- `Void OnCancelBtnClick()`

- `Void OnRestartBtnClick()`

- `Void OnRestartCancelBtnClick()`

- `Void OnRestartConfirmBtnClick()`

- `Void <OnRestartConfirmBtnClick>b__26_0(ExploreGiveUpGameResponse)`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreQuitConfirmDialog : UICompDialog`1
{
	public const Int32 CONFIRM_RESTART; // 0x0
	private CanvasGroup _canvasGroup; // 0x48
	private UIRenderTextureImage _blurBkg; // 0x50
	private GameObject _restartObj; // 0x58
	private CanvasGroup _quitCanvasGroup; // 0x60
	private CanvasGroup _restartCanvasGroup; // 0x68
	private FadeSwitchTween m_mainFadeSwitchTween; // 0x70
	private FadeSwitchTween m_quitFadeSwitchTween; // 0x78
	private FadeSwitchTween m_restartFadeSwitchTween; // 0x80
	private Boolean m_isInited; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private FifthAnnivExploreMapController m_mapController; // 0xa0
	private Boolean m_needRestartBtn; // 0xa8
	private Boolean m_isShowingRestart; // 0xa9
	private Int32 m_restartConfirmInstId; // 0xac
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__LoadData; // 0x10
	private static DelegateBridge __Hotfix0__CheckNeedRestartBtn; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_OnCancelBtnClick; // 0x38
	private static DelegateBridge __Hotfix0_OnRestartBtnClick; // 0x40
	private static DelegateBridge __Hotfix0_OnRestartCancelBtnClick; // 0x48
	private static DelegateBridge __Hotfix0_OnRestartConfirmBtnClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x29318ec VA: 0x7594f498ec
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2931954 VA: 0x7594f49954
	private Void _InitIfNot() { }
	// RVA: 0x2931b34 VA: 0x7594f49b34
	private Void _LoadData() { }
	// RVA: 0x2931bac VA: 0x7594f49bac
	private Boolean _CheckNeedRestartBtn() { }
	// RVA: 0x2931d30 VA: 0x7594f49d30
	protected override Void OnRender(Options input) { }
	// RVA: 0x2931dbc VA: 0x7594f49dbc
	private Void Render() { }
	// RVA: 0x2931e74 VA: 0x7594f49e74
	public Void OnConfirmBtnClick() { }
	// RVA: 0x2932078 VA: 0x7594f4a078
	public Void OnCancelBtnClick() { }
	// RVA: 0x293211c VA: 0x7594f4a11c
	public Void OnRestartBtnClick() { }
	// RVA: 0x2932250 VA: 0x7594f4a250
	public Void OnRestartCancelBtnClick() { }
	// RVA: 0x2932380 VA: 0x7594f4a380
	public Void OnRestartConfirmBtnClick() { }
	// RVA: 0x2932584 VA: 0x7594f4a584
	public Void .ctor() { }
	// RVA: 0x2932614 VA: 0x7594f4a614
	private Void <OnRestartConfirmBtnClick>b__26_0(ExploreGiveUpGameResponse response) { }
	// RVA: 0x2932698 VA: 0x7594f4a698
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```