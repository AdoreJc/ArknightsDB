# TuningChatNarrationView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Text _content`

- `Text _selectContent`

- `CanvasGroup _contentAlphaHandler`

- `CanvasGroup _selectContentAlphaHandler`

- `CanvasGroup _emptyContent`

- `CanvasGroup _selectEmptyContent`

- `CanvasGroup _panelNormal`

- `CanvasGroup _panelBackPack`

- `CanvasGroup _btnSkip`

- `CanvasGroup _btnNext`

- `CanvasGroup _btnOpen`

- `CanvasGroup _btnUnselect`

- `CanvasGroup _btnSubmit`

- `CanvasGroup _btnFinish`

- `TuningChatNarrationCardView _cardView`

- `TuningChatItemViewModel m_cachedViewModel`

- `TuningChatBagItemViewModel m_cachedCardViewModel`

- `UIStateFinder m_stateFinder`

- `Boolean m_isInited`

- `Boolean m_alreadySkip`

- `Int32 m_cachedIndex`

- `String m_cachedContent`

- `ShowType m_showType`

- `FadeTween m_contentSwitchTween`

- `FadeTween m_selectContentSwitchTween`

- `FadeTween m_emptySwitchTween`

- `FadeTween m_selectEmptySwitchTween`

- `FadeTween m_normalSwitchTween`

- `FadeTween m_backpackSwitchTween`

- `FadeTween m_skipSwitchTween`

- `FadeTween m_nextSwitchTween`

- `FadeTween m_openSwitchTween`

- `FadeTween m_unselectSwitchTween`

- `FadeTween m_submitSwitchTween`

- `FadeTween m_finishSwitchTween`


## Methods

- `Void Render(Options)`

- `Void UpdateData(TuningChatItemViewModel)`

- `Void UpdateCardData(TuningChatBagItemViewModel)`

- `Void _InitIfNot()`

- `Void _RenderImpl(String, ShowType, Boolean, Boolean)`

- `Void _RenderNormal(String, ShowType, Boolean)`

- `Void _RenderBackpack(String, ShowType, Boolean, Boolean)`

- `Void OnHandleSkip()`

- `Void OnNextNarration()`

- `Void OnHandleOpen()`

- `Void OnHandleSubmit()`

- `Void OnHandleFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatNarrationView : MonoBehaviour, IHotfixable
{
	private const Single CONTENT_FADE_DURATION; // 0x0
	private Text _content; // 0x18
	private Text _selectContent; // 0x20
	private CanvasGroup _contentAlphaHandler; // 0x28
	private CanvasGroup _selectContentAlphaHandler; // 0x30
	private CanvasGroup _emptyContent; // 0x38
	private CanvasGroup _selectEmptyContent; // 0x40
	private CanvasGroup _panelNormal; // 0x48
	private CanvasGroup _panelBackPack; // 0x50
	private CanvasGroup _btnSkip; // 0x58
	private CanvasGroup _btnNext; // 0x60
	private CanvasGroup _btnOpen; // 0x68
	private CanvasGroup _btnUnselect; // 0x70
	private CanvasGroup _btnSubmit; // 0x78
	private CanvasGroup _btnFinish; // 0x80
	private TuningChatNarrationCardView _cardView; // 0x88
	private TuningChatItemViewModel m_cachedViewModel; // 0x90
	private TuningChatBagItemViewModel m_cachedCardViewModel; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private Boolean m_isInited; // 0xb0
	private Boolean m_alreadySkip; // 0xb1
	private Int32 m_cachedIndex; // 0xb4
	private String m_cachedContent; // 0xb8
	private ShowType m_showType; // 0xc0
	private FadeTween m_contentSwitchTween; // 0xc8
	private FadeTween m_selectContentSwitchTween; // 0xd0
	private FadeTween m_emptySwitchTween; // 0xd8
	private FadeTween m_selectEmptySwitchTween; // 0xe0
	private FadeTween m_normalSwitchTween; // 0xe8
	private FadeTween m_backpackSwitchTween; // 0xf0
	private FadeTween m_skipSwitchTween; // 0xf8
	private FadeTween m_nextSwitchTween; // 0x100
	private FadeTween m_openSwitchTween; // 0x108
	private FadeTween m_unselectSwitchTween; // 0x110
	private FadeTween m_submitSwitchTween; // 0x118
	private FadeTween m_finishSwitchTween; // 0x120
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCardData; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RenderImpl; // 0x20
	private static DelegateBridge __Hotfix0__RenderNormal; // 0x28
	private static DelegateBridge __Hotfix0__RenderBackpack; // 0x30
	private static DelegateBridge __Hotfix0_OnHandleSkip; // 0x38
	private static DelegateBridge __Hotfix0_OnNextNarration; // 0x40
	private static DelegateBridge __Hotfix0_OnHandleOpen; // 0x48
	private static DelegateBridge __Hotfix0_OnHandleSubmit; // 0x50
	private static DelegateBridge __Hotfix0_OnHandleFinish; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2319444 VA: 0x7594931444
	public Void Render(Options options) { }
	// RVA: 0x23196f0 VA: 0x75949316f0
	public Void UpdateData(TuningChatItemViewModel viewModel) { }
	// RVA: 0x23197b4 VA: 0x75949317b4
	public Void UpdateCardData(TuningChatBagItemViewModel cardModel) { }
	// RVA: 0x2319868 VA: 0x7594931868
	private Void _InitIfNot() { }
	// RVA: 0x2319558 VA: 0x7594931558
	private Void _RenderImpl(String content, ShowType showType, Boolean isOpenBag, Boolean isFastMode) { }
	// RVA: 0x2319d90 VA: 0x7594931d90
	private Void _RenderNormal(String content, ShowType showType, Boolean isFastMode) { }
	// RVA: 0x2319f98 VA: 0x7594931f98
	private Void _RenderBackpack(String content, ShowType showType, Boolean isOpenBag, Boolean isFastMode) { }
	// RVA: 0x231a1b4 VA: 0x75949321b4
	public Void OnHandleSkip() { }
	// RVA: 0x231a278 VA: 0x7594932278
	public Void OnNextNarration() { }
	// RVA: 0x231a380 VA: 0x7594932380
	public Void OnHandleOpen() { }
	// RVA: 0x231a434 VA: 0x7594932434
	public Void OnHandleSubmit() { }
	// RVA: 0x231a53c VA: 0x759493253c
	public Void OnHandleFinish() { }
	// RVA: 0x231a5f0 VA: 0x75949325f0
	public Void .ctor() { }
}
```