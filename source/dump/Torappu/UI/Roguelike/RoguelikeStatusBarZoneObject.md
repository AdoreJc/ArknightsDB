# RoguelikeStatusBarZoneObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GameObject _pnlContent`

- `Button _btnDetail`

- `Text _textZoneName`

- `Text _textZoneDesc`

- `VariationPanel _variationPanel1`

- `VariationPanel _variationPanel2`

- `UIAnimationLocation _animVariation`

- `UIAtlasImage _lightVariation`

- `RoguelikeMenuZoneViewModel m_cachedModel`

- `Tween m_lightTween`


## Methods

- `Void _Render()`

- `Void _EventOnShowVariationEffect(Object)`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarZoneObject : RoguelikeMenuObject`1
{
	private const Single LOOP_DURATION; // 0x0
	private const Single LOOP_ALPHA_MIN; // 0x0
	private const Single LOOP_ALPHA_MAX; // 0x0
	private static readonly Type[] STATES_NOT_SHOW; // 0x0
	private GameObject _pnlContent; // 0x28
	private Button _btnDetail; // 0x30
	private Text _textZoneName; // 0x38
	private Text _textZoneDesc; // 0x40
	private VariationPanel _variationPanel1; // 0x48
	private VariationPanel _variationPanel2; // 0x50
	private UIAnimationLocation _animVariation; // 0x58
	private UIAtlasImage _lightVariation; // 0x68
	private RoguelikeMenuZoneViewModel m_cachedModel; // 0x70
	private Tween m_lightTween; // 0x78
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_get_menuType; // 0x10
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__Render; // 0x28
	private static DelegateBridge __Hotfix0__EventOnShowVariationEffect; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a712c4 VA: 0x75950892c4
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2a713ec VA: 0x75950893ec
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a71464 VA: 0x7595089464
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2a71778 VA: 0x7595089778
	public override Void Render(RoguelikeMenuZoneViewModel viewModel) { }
	// RVA: 0x2a71560 VA: 0x7595089560
	private Void _Render() { }
	// RVA: 0x2a718d4 VA: 0x75950898d4
	private Void _EventOnShowVariationEffect(Object arg) { }
	// RVA: 0x2a71bf0 VA: 0x7595089bf0
	public Void .ctor() { }
	// RVA: 0x2a71c90 VA: 0x7595089c90
	private static Void .cctor() { }
	// RVA: 0x2a71e00 VA: 0x7595089e00
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2a71e04 VA: 0x7595089e04
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
}
```