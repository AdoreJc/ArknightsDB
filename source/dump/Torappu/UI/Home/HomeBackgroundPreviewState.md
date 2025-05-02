# HomeBackgroundPreviewState

**Namespace:** `Torappu.UI.Home`


## Fields

- `CanvasGroup _alphaHandler`

- `CanvasGroup _panelButtons`

- `GameObject _btnDynPreview`

- `HomeIllustEditFrame _editFrame`

- `RectTransform _rectBack`

- `IllustHandler m_illustHandler`

- `Boolean m_isInited`

- `Boolean m_illustFlagInited`

- `Boolean m_useIllustSetting`

- `Boolean m_isDynamicIllust`

- `CharUISkinStruct m_curSkin`

- `Tweener m_fadeIn`

- `Tweener m_fadeOut`

- `Boolean m_cancelBtnShowing`

- `Int32 m_instId`


## Methods

- `Void BtnPanelBlockClick()`

- `Void BtnPreviewClick()`

- `Void CloseButtonFadeIn()`

- `Void ClosePreview()`

- `Void ClickFromFrame(PointerEventData)`

- `Void _ResetTweener()`

- `Void _StartPreviewMode()`

- `Void _ExitPreviewMode()`

- `Void _InitIllustEditFrame()`

- `Void _InitIfNot()`

- `Void OnDestroy()`

- `Void <CloseButtonFadeIn>b__21_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeBackgroundPreviewState : HomeReplaceableState, IClickEvent
{
	private CanvasGroup _alphaHandler; // 0x60
	private CanvasGroup _panelButtons; // 0x68
	private GameObject _btnDynPreview; // 0x70
	private HomeIllustEditFrame _editFrame; // 0x78
	private RectTransform _rectBack; // 0x80
	private IllustHandler m_illustHandler; // 0x88
	private Boolean m_isInited; // 0x90
	private Boolean m_illustFlagInited; // 0x91
	private Boolean m_useIllustSetting; // 0x92
	private Boolean m_isDynamicIllust; // 0x93
	private CharUISkinStruct m_curSkin; // 0x98
	private Tweener m_fadeIn; // 0xa8
	private Tweener m_fadeOut; // 0xb0
	private Boolean m_cancelBtnShowing; // 0xb8
	private Int32 m_instId; // 0xbc
	private const Single FADE_IN_DELAY; // 0x0
	private const Single FADE_IN_TIME; // 0x0
	private const Single FADE_OUT_DELAY; // 0x0
	private const Single FADE_OUT_TIME; // 0x0
	private static DelegateBridge __Hotfix0_BtnPanelBlockClick; // 0x0
	private static DelegateBridge __Hotfix0_BtnPreviewClick; // 0x8
	private static DelegateBridge __Hotfix0_CloseButtonFadeIn; // 0x10
	private static DelegateBridge __Hotfix0_ClosePreview; // 0x18
	private static DelegateBridge __Hotfix0_ClickFromFrame; // 0x20
	private static DelegateBridge __Hotfix0__ResetTweener; // 0x28
	private static DelegateBridge __Hotfix0__StartPreviewMode; // 0x30
	private static DelegateBridge __Hotfix0__ExitPreviewMode; // 0x38
	private static DelegateBridge __Hotfix0__InitIllustEditFrame; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x50
	private static DelegateBridge __Hotfix0_OnExit; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x68
	private static DelegateBridge __Hotfix0_ShowEffect; // 0x70
	private static DelegateBridge __Hotfix0_HideEffect; // 0x78
	private static DelegateBridge __Hotfix0_ShowFastMode; // 0x80
	private static DelegateBridge __Hotfix0_HideFastMode; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x27e9910 VA: 0x7594e01910
	public Void BtnPanelBlockClick() { }
	// RVA: 0x27e9c0c VA: 0x7594e01c0c
	public Void BtnPreviewClick() { }
	// RVA: 0x27e9a14 VA: 0x7594e01a14
	public Void CloseButtonFadeIn() { }
	// RVA: 0x27e99a0 VA: 0x7594e019a0
	public Void ClosePreview() { }
	// RVA: 0x27e9e38 VA: 0x7594e01e38
	public Void ClickFromFrame(PointerEventData eventData) { }
	// RVA: 0x27e9d84 VA: 0x7594e01d84
	private Void _ResetTweener() { }
	// RVA: 0x27e9f44 VA: 0x7594e01f44
	private Void _StartPreviewMode() { }
	// RVA: 0x27ea03c VA: 0x7594e0203c
	private Void _ExitPreviewMode() { }
	// RVA: 0x27ea164 VA: 0x7594e02164
	private Void _InitIllustEditFrame() { }
	// RVA: 0x27ea37c VA: 0x7594e0237c
	private Void _InitIfNot() { }
	// RVA: 0x27ea490 VA: 0x7594e02490
	protected override Void OnEnter() { }
	// RVA: 0x27ea518 VA: 0x7594e02518
	protected override Void OnExit() { }
	// RVA: 0x27ea590 VA: 0x7594e02590
	protected Void OnDestroy() { }
	// RVA: 0x27ea5f8 VA: 0x7594e025f8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27ea65c VA: 0x7594e0265c
	protected override IEnumerator ShowEffect(HomeReplaceableState extractState) { }
	// RVA: 0x27ea744 VA: 0x7594e02744
	protected override IEnumerator HideEffect() { }
	// RVA: 0x27ea818 VA: 0x7594e02818
	protected override Void ShowFastMode() { }
	// RVA: 0x27ea8b0 VA: 0x7594e028b0
	protected override Void HideFastMode() { }
	// RVA: 0x27ea928 VA: 0x7594e02928
	public Void .ctor() { }
	// RVA: 0x27ea998 VA: 0x7594e02998
	private Void <CloseButtonFadeIn>b__21_0() { }
	// RVA: 0x27ea9cc VA: 0x7594e029cc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27ea9d4 VA: 0x7594e029d4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```