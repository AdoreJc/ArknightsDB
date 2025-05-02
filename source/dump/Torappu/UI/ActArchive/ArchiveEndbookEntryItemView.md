# ArchiveEndbookEntryItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _cardImg`

- `Image _cardTitleImg`

- `GameObject _panelUnlock`

- `GameObject _panelLock`

- `GameObject _panelNew`

- `Slider _collectSlider`

- `GameObject _panelAllCollect`

- `RectTransform _behindLineFrontRect`

- `RectTransform _behindLineBackRect`

- `CanvasGroup _backCanvasGroup`

- `CanvasGroup _titleCanvasGroup`

- `CanvasGroup _circleCanvasGroup`

- `CanvasGroup _cardCanvasGroup`

- `CanvasGroup _lockCardCanvasGroup`

- `GameObject _panelLeft`

- `GameObject _panelRight`

- `GameObject _hotspot`

- `UIAnimationLocation _switchAnim`

- `Single _animDuration`

- `Int32 m_cachedIndex`

- `Boolean m_isInited`

- `Single m_cachedWidth`

- `EndbookSwitchTween m_switchTween`


## Methods

- `Void Render(Param)`

- `Void _RereshWithFocusPage(Single)`

- `Void _OnFocusPageChanged(Single)`

- `Void _InitIfNot()`

- `Void _PlaySwitchAnim(Single)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookEntryItemView : MonoBehaviour, IHotfixable
{
	private Image _cardImg; // 0x18
	private Image _cardTitleImg; // 0x20
	private GameObject _panelUnlock; // 0x28
	private GameObject _panelLock; // 0x30
	private GameObject _panelNew; // 0x38
	private Slider _collectSlider; // 0x40
	private GameObject _panelAllCollect; // 0x48
	private RectTransform _behindLineFrontRect; // 0x50
	private RectTransform _behindLineBackRect; // 0x58
	private CanvasGroup _backCanvasGroup; // 0x60
	private CanvasGroup _titleCanvasGroup; // 0x68
	private CanvasGroup _circleCanvasGroup; // 0x70
	private CanvasGroup _cardCanvasGroup; // 0x78
	private CanvasGroup _lockCardCanvasGroup; // 0x80
	private GameObject _panelLeft; // 0x88
	private GameObject _panelRight; // 0x90
	private GameObject _hotspot; // 0x98
	private UIAnimationLocation _switchAnim; // 0xa0
	private Single _animDuration; // 0xb0
	private Action`1 m_onItemClick; // 0xb8
	private Int32 m_cachedIndex; // 0xc0
	private Boolean m_isInited; // 0xc4
	private Single m_cachedWidth; // 0xc8
	private EndbookSwitchTween m_switchTween; // 0xd0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RereshWithFocusPage; // 0x8
	private static DelegateBridge __Hotfix0__OnFocusPageChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlaySwitchAnim; // 0x20
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x304e238 VA: 0x7595666238
	public Void Render(Param param) { }
	// RVA: 0x304e688 VA: 0x7595666688
	private Void _RereshWithFocusPage(Single pageIndex) { }
	// RVA: 0x304e7c4 VA: 0x75956667c4
	private Void _OnFocusPageChanged(Single pageIndex) { }
	// RVA: 0x304e590 VA: 0x7595666590
	private Void _InitIfNot() { }
	// RVA: 0x304e8f0 VA: 0x75956668f0
	private Void _PlaySwitchAnim(Single position) { }
	// RVA: 0x304e9dc VA: 0x75956669dc
	public Void OnItemClick() { }
	// RVA: 0x304ea64 VA: 0x7595666a64
	public Void .ctor() { }
}
```