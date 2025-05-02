# RoguelikeTopicBattlePassPurchaseGrandPrizeView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Image _imgPrize`

- `Text _textLevel`

- `Text _textType`

- `Text _textName`

- `CanvasGroup _canvasUnavailable`

- `CanvasGroup _canvasSelected`

- `CanvasGroup _canvasUnselected`

- `CanvasGroup _canvasRoot`

- `CanvasGroup _canvasLight`

- `UIAtlasImage _line`

- `GameObject _unavailableMask`

- `Text _disabledReason`

- `UIAtlasImage _iconSelected`

- `UIAtlasImage _imgLight`

- `Text _textLv`

- `Single _alphaUnavailable`

- `Single _alphaSelected`

- `Single _alphaUnselected`

- `Color _colorUnavailable`

- `Color _colorUnselected`

- `Single _animDuration`

- `Tween m_stateTween`

- `Int64 m_cachedWidgetId`

- `String m_cachedGrandPrizeId`

- `State m_cachedState`

- `Color m_colorSelected`

- `RoguelikeTopicBattlePassStyle m_style`


## Methods

- `Void Render(RoguelikeTopicBPPrizeViewModel, RoguelikeTopicBattlePassPurchaseViewModel, RoguelikeTopicBattlePassStyle)`

- `Void _RenderGrandPrizeStatus(RoguelikeTopicBPPrizeViewModel, RoguelikeTopicBattlePassPurchaseViewModel)`

- `Void _RenderState(RoguelikeTopicBPPrizeViewModel, RoguelikeTopicBattlePassPurchaseViewModel, Boolean)`

- `Void _SwitchToState(State, Boolean)`

- `Void _SetStyleIfNeeded(RoguelikeTopicBattlePassStyle)`

- `Void OnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseGrandPrizeView : MonoBehaviour, IHotfixable
{
	private const String GRAND_PRIZE_CARD_IMAGE_PREFIX; // 0x0
	private Image _imgPrize; // 0x18
	private Text _textLevel; // 0x20
	private Text _textType; // 0x28
	private Text _textName; // 0x30
	private CanvasGroup _canvasUnavailable; // 0x38
	private CanvasGroup _canvasSelected; // 0x40
	private CanvasGroup _canvasUnselected; // 0x48
	private CanvasGroup _canvasRoot; // 0x50
	private CanvasGroup _canvasLight; // 0x58
	private UIAtlasImage _line; // 0x60
	private GameObject _unavailableMask; // 0x68
	private Text _disabledReason; // 0x70
	private UIAtlasImage _iconSelected; // 0x78
	private UIAtlasImage _imgLight; // 0x80
	private Text _textLv; // 0x88
	private Single _alphaUnavailable; // 0x90
	private Single _alphaSelected; // 0x94
	private Single _alphaUnselected; // 0x98
	private Color _colorUnavailable; // 0x9c
	private Color _colorUnselected; // 0xac
	private Single _animDuration; // 0xbc
	private Tween m_stateTween; // 0xc0
	private Int64 m_cachedWidgetId; // 0xc8
	private String m_cachedGrandPrizeId; // 0xd0
	private State m_cachedState; // 0xd8
	private Color m_colorSelected; // 0xdc
	private RoguelikeTopicBattlePassStyle m_style; // 0xf0
	public Action`1 onBtnClicked; // 0xf8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderGrandPrizeStatus; // 0x8
	private static DelegateBridge __Hotfix0__RenderState; // 0x10
	private static DelegateBridge __Hotfix0__SwitchToState; // 0x18
	private static DelegateBridge __Hotfix0__SetStyleIfNeeded; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2638bb0 VA: 0x7594c50bb0
	public Void Render(RoguelikeTopicBPPrizeViewModel itemModel, RoguelikeTopicBattlePassPurchaseViewModel outerModel, RoguelikeTopicBattlePassStyle style) { }
	// RVA: 0x2638ec4 VA: 0x7594c50ec4
	private Void _RenderGrandPrizeStatus(RoguelikeTopicBPPrizeViewModel itemModel, RoguelikeTopicBattlePassPurchaseViewModel outerModel) { }
	// RVA: 0x26390bc VA: 0x7594c510bc
	private Void _RenderState(RoguelikeTopicBPPrizeViewModel itemModel, RoguelikeTopicBattlePassPurchaseViewModel outerModel, Boolean isInit) { }
	// RVA: 0x26391a0 VA: 0x7594c511a0
	private Void _SwitchToState(State state, Boolean isInit) { }
	// RVA: 0x2638cb0 VA: 0x7594c50cb0
	private Void _SetStyleIfNeeded(RoguelikeTopicBattlePassStyle style) { }
	// RVA: 0x263968c VA: 0x7594c5168c
	public Void OnBtnClicked() { }
	// RVA: 0x263971c VA: 0x7594c5171c
	public Void .ctor() { }
}
```