# SkinPreviewPanel

**Namespace:** `Torappu.UI.Skin`


## Fields

- `Vector2 _wrapperStandardPos`

- `UIFadeFloatPanel _floatPanel`

- `UIWrappedScrollRect _scrollContainer`

- `CharacterInfoIllustWrapper _illustWrapper`

- `UITouchZoom _panelTouchZoom`

- `AdvancedAutoHideComponent _autoHideComp`

- `GameObject _animBtnPanelGo`

- `GameObject _btnAnimEnterGo`

- `RectTransform _btnBackRt`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `Boolean m_hasInited`

- `Vector2 m_initWrapperSize`

- `CharUISkinStruct m_skinStruct`

- `IllustType m_illustType`

- `Int32 m_cachedHideMessage`

- `Boolean m_cachedEnableMessage`


## Methods

- `Boolean IsShow()`

- `Void Show(Input)`

- `Void NotifySkinSelectChanged(CharUISkinStruct)`

- `Void Hide()`

- `Void _ResetPreviewArgs()`

- `Void _ResetIllustWrapperPos()`

- `Void _InitIfNot()`

- `IEnumerator _PlayDynEntranceCoro()`

- `Void _OnAnimEnterFinished()`

- `Void _OnScaleChanged(Single)`

- `Void _OnScaleStart(Single)`

- `Void _OnScaleEnd(Single)`

- `Void EventOnBtnBack()`

- `Void EventOnBtnAnimEnter()`

- `Void EventOnBtnAnimSpecial()`

- `Void EventOnBtnAnimInteract()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinPreviewPanel : MonoBehaviour, IHotfixable
{
	private Vector2 _wrapperStandardPos; // 0x18
	private UIFadeFloatPanel _floatPanel; // 0x20
	private UIWrappedScrollRect _scrollContainer; // 0x28
	private CharacterInfoIllustWrapper _illustWrapper; // 0x30
	private UITouchZoom _panelTouchZoom; // 0x38
	private AdvancedAutoHideComponent _autoHideComp; // 0x40
	private GameObject _animBtnPanelGo; // 0x48
	private GameObject _btnAnimEnterGo; // 0x50
	private RectTransform _btnBackRt; // 0x58
	private const Single DEFAULT_SCALE; // 0x0
	private static readonly Vector2 ILLUST_PADDING; // 0x0
	private UIStateFinder m_stateFinder; // 0x60
	private UIPageFinder m_pageFinder; // 0x70
	private Boolean m_hasInited; // 0x80
	private Vector2 m_initWrapperSize; // 0x84
	private CharUISkinStruct m_skinStruct; // 0x90
	private IllustType m_illustType; // 0xa0
	private Int32 m_cachedHideMessage; // 0xa4
	private Boolean m_cachedEnableMessage; // 0xa8
	private static DelegateBridge __Hotfix0_IsShow; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_NotifySkinSelectChanged; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge __Hotfix0__ResetPreviewArgs; // 0x28
	private static DelegateBridge __Hotfix0__ResetIllustWrapperPos; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__PlayDynEntranceCoro; // 0x40
	private static DelegateBridge __Hotfix0__OnAnimEnterFinished; // 0x48
	private static DelegateBridge __Hotfix0__OnScaleChanged; // 0x50
	private static DelegateBridge __Hotfix0__OnScaleStart; // 0x58
	private static DelegateBridge __Hotfix0__OnScaleEnd; // 0x60
	private static DelegateBridge __Hotfix0_EventOnBtnBack; // 0x68
	private static DelegateBridge __Hotfix0_EventOnBtnAnimEnter; // 0x70
	private static DelegateBridge __Hotfix0_EventOnBtnAnimSpecial; // 0x78
	private static DelegateBridge __Hotfix0_EventOnBtnAnimInteract; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x23d1954 VA: 0x75949e9954
	public Boolean IsShow() { }
	// RVA: 0x23d1d28 VA: 0x75949e9d28
	public Void Show(Input input) { }
	// RVA: 0x23d19d8 VA: 0x75949e99d8
	public Void NotifySkinSelectChanged(CharUISkinStruct curSelection) { }
	// RVA: 0x23d3638 VA: 0x75949eb638
	public Void Hide() { }
	// RVA: 0x23d34b4 VA: 0x75949eb4b4
	private Void _ResetPreviewArgs() { }
	// RVA: 0x23d33f8 VA: 0x75949eb3f8
	private Void _ResetIllustWrapperPos() { }
	// RVA: 0x23d31dc VA: 0x75949eb1dc
	private Void _InitIfNot() { }
	// RVA: 0x23d37b8 VA: 0x75949eb7b8
	private IEnumerator _PlayDynEntranceCoro() { }
	// RVA: 0x23d3874 VA: 0x75949eb874
	private Void _OnAnimEnterFinished() { }
	// RVA: 0x23d397c VA: 0x75949eb97c
	private Void _OnScaleChanged(Single scale) { }
	// RVA: 0x23d3a40 VA: 0x75949eba40
	private Void _OnScaleStart(Single scale) { }
	// RVA: 0x23d3adc VA: 0x75949ebadc
	private Void _OnScaleEnd(Single scale) { }
	// RVA: 0x23d3b78 VA: 0x75949ebb78
	public Void EventOnBtnBack() { }
	// RVA: 0x23d3bf0 VA: 0x75949ebbf0
	public Void EventOnBtnAnimEnter() { }
	// RVA: 0x23d3d60 VA: 0x75949ebd60
	public Void EventOnBtnAnimSpecial() { }
	// RVA: 0x23d3e6c VA: 0x75949ebe6c
	public Void EventOnBtnAnimInteract() { }
	// RVA: 0x23d3f78 VA: 0x75949ebf78
	public Void .ctor() { }
	// RVA: 0x23d3ff8 VA: 0x75949ebff8
	private static Void .cctor() { }
}
```