# RL04AlchemyForecastView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `UIAnimationLocation _ensureAnim`

- `Single _durForWeightGuyShow`

- `UIAnimationLocation _weightGuyAnim`

- `CanvasGroup _canvasWeightGuy`

- `CanvasGroup _canvasRarityNotReady`

- `Text _txtRewardForecast`

- `CanvasGroup _canvasRarityReady`

- `SimpleLayoutContent _rarityStarList`

- `UIAnimationLocation _rarityNormalAnim`

- `UIAnimationLocation _rarityRareAnim`

- `UIAnimationLocation _raritySuperRareAnim`

- `Slider _sliderRelic`

- `Slider _sliderShield`

- `Slider _sliderPopulation`

- `Single _sliderTweenDuration`

- `RL04ItemIconWithFragment _definiteRewardItem`

- `Text _txtDefiniteRewardItemName`

- `Text _txtDefiniteRewardItemDesc`

- `Boolean m_hasInited`

- `PoolRarityStarListAdapter m_poolRarityStarListAdapter`

- `TweenWrapper m_weightSwitchTweenWrapper`

- `WeightSwitchTween m_weightSwitchTween`

- `AnimationSwitchTween m_ensureAnimTween`

- `AnimationSwitchTween m_rarityNormalAnimTween`

- `AnimationSwitchTween m_rarityRareAnimTween`

- `AnimationSwitchTween m_raritySuperRareAnimTween`

- `Tween m_sliderRelicTween`

- `Tween m_sliderShieldTween`

- `Tween m_sliderPopulationTween`

- `FadeSwitchTween m_rarityNotReady`

- `FadeSwitchTween m_rarityReady`


## Methods

- `Void Render(RL04AlchemyForecastViewModel, RL04AlchemyForecastRandomViewModel, Boolean)`

- `Void _InitIfNot()`

- `Void _RenderNotReadyPart(RL04AlchemyForecastRandomViewModel)`

- `Void _RenderRandomPart(RL04AlchemyForecastRandomViewModel)`

- `Void _RefreshRewardForecastTxt(AlchemyPoolRarityType)`

- `Void _RenderDefinitenessPart(RL04AlchemyForecastDefinitenessItemViewModel)`

- `Void _SlidePropToValue(Single, Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyForecastView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _ensureAnim; // 0x18
	private Single _durForWeightGuyShow; // 0x28
	private UIAnimationLocation _weightGuyAnim; // 0x30
	private CanvasGroup _canvasWeightGuy; // 0x40
	private CanvasGroup _canvasRarityNotReady; // 0x48
	private Text _txtRewardForecast; // 0x50
	private CanvasGroup _canvasRarityReady; // 0x58
	private SimpleLayoutContent _rarityStarList; // 0x60
	private UIAnimationLocation _rarityNormalAnim; // 0x68
	private UIAnimationLocation _rarityRareAnim; // 0x78
	private UIAnimationLocation _raritySuperRareAnim; // 0x88
	private Slider _sliderRelic; // 0x98
	private Slider _sliderShield; // 0xa0
	private Slider _sliderPopulation; // 0xa8
	private Single _sliderTweenDuration; // 0xb0
	private RL04ItemIconWithFragment _definiteRewardItem; // 0xb8
	private Text _txtDefiniteRewardItemName; // 0xc0
	private Text _txtDefiniteRewardItemDesc; // 0xc8
	private Boolean m_hasInited; // 0xd0
	private PoolRarityStarListAdapter m_poolRarityStarListAdapter; // 0xd8
	private TweenWrapper m_weightSwitchTweenWrapper; // 0xe0
	private WeightSwitchTween m_weightSwitchTween; // 0xe8
	private AnimationSwitchTween m_ensureAnimTween; // 0xf0
	private AnimationSwitchTween m_rarityNormalAnimTween; // 0xf8
	private AnimationSwitchTween m_rarityRareAnimTween; // 0x100
	private AnimationSwitchTween m_raritySuperRareAnimTween; // 0x108
	private Tween m_sliderRelicTween; // 0x110
	private Tween m_sliderShieldTween; // 0x118
	private Tween m_sliderPopulationTween; // 0x120
	private FadeSwitchTween m_rarityNotReady; // 0x128
	private FadeSwitchTween m_rarityReady; // 0x130
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderNotReadyPart; // 0x10
	private static DelegateBridge __Hotfix0__RenderRandomPart; // 0x18
	private static DelegateBridge __Hotfix0__RefreshRewardForecastTxt; // 0x20
	private static DelegateBridge __Hotfix0__RenderDefinitenessPart; // 0x28
	private static DelegateBridge __Hotfix0__SlidePropToValue; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2b06934 VA: 0x759511e934
	public Void Render(RL04AlchemyForecastViewModel forecastViewModel, RL04AlchemyForecastRandomViewModel emptyRandomViewModel, Boolean isMelded) { }
	// RVA: 0x2b06aec VA: 0x759511eaec
	private Void _InitIfNot() { }
	// RVA: 0x2b07158 VA: 0x759511f158
	private Void _RenderNotReadyPart(RL04AlchemyForecastRandomViewModel emptyRandomViewModel) { }
	// RVA: 0x2b06e2c VA: 0x759511ee2c
	private Void _RenderRandomPart(RL04AlchemyForecastRandomViewModel randomViewModel) { }
	// RVA: 0x2b07428 VA: 0x759511f428
	private Void _RefreshRewardForecastTxt(AlchemyPoolRarityType rarityType) { }
	// RVA: 0x2b06fe4 VA: 0x759511efe4
	private Void _RenderDefinitenessPart(RL04AlchemyForecastDefinitenessItemViewModel definitenessItemViewModel) { }
	// RVA: 0x2b07550 VA: 0x759511f550
	private Void _SlidePropToValue(Single relicProp, Single shieldProp, Single populationProp) { }
	// RVA: 0x2b07714 VA: 0x759511f714
	public Void .ctor() { }
}
```