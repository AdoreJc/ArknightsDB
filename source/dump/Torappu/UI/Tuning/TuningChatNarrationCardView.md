# TuningChatNarrationCardView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Text _title`

- `Text _formDesc`

- `Text _orcheDesc`

- `Text _hiddenDesc`

- `GameObject _panelNormal`

- `GameObject _panelHidden`

- `CanvasGroup _panelCard`

- `TuningCommonCard _cardViewPrefab`

- `Transform _cardContainer`

- `Single _cardScale`

- `UIAnimationLocation _cardAnim`

- `Boolean m_isInited`

- `String m_cachedProductId`

- `FadeSwitchTween m_cardSwitchTween`

- `Tween m_animTween`

- `TuningCommonCard m_cardView`


## Methods

- `Void Render(TuningChatBagItemViewModel, Boolean)`

- `Void _PlayAnim()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatNarrationCardView : MonoBehaviour, IHotfixable
{
	private Text _title; // 0x18
	private Text _formDesc; // 0x20
	private Text _orcheDesc; // 0x28
	private Text _hiddenDesc; // 0x30
	private Text[] _formDecos; // 0x38
	private GameObject _panelNormal; // 0x40
	private GameObject _panelHidden; // 0x48
	private CanvasGroup _panelCard; // 0x50
	private TuningCommonCard _cardViewPrefab; // 0x58
	private Transform _cardContainer; // 0x60
	private Single _cardScale; // 0x68
	private UIAnimationLocation _cardAnim; // 0x70
	private Boolean m_isInited; // 0x80
	private String m_cachedProductId; // 0x88
	private FadeSwitchTween m_cardSwitchTween; // 0x90
	private Tween m_animTween; // 0x98
	private TuningCommonCard m_cardView; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2318a04 VA: 0x7594930a04
	public Void Render(TuningChatBagItemViewModel viewModel, Boolean isOpenBag) { }
	// RVA: 0x2318eec VA: 0x7594930eec
	private Void _PlayAnim() { }
	// RVA: 0x2318d0c VA: 0x7594930d0c
	private Void _InitIfNot() { }
	// RVA: 0x23193d4 VA: 0x75949313d4
	public Void .ctor() { }
}
```