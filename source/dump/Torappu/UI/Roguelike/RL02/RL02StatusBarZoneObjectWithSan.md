# RL02StatusBarZoneObjectWithSan

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `GameObject _pnlContent`

- `Button _btnDetail`

- `Text _textZoneName`

- `UIAtlasImage _imageZoneNum`

- `UIAtlasObject _imageZoneNumAtlas`

- `GameObject _panelVariation`

- `GameObject _panelSan`

- `CanvasGroup _canvasSanBkg`

- `CanvasGroup _canvasSanEmpty`

- `Text _textSanNum`

- `RectTransform _maskSan`

- `RL02StatusBarSanEffect _effectPrefab`

- `Tween m_sanTween`

- `FadeSwitchTween m_sanBkgShowTween`

- `FadeSwitchTween m_sanEmptyShowTween`

- `RoguelikeStatusBarTextTweener m_sanTextTweener`

- `RL02ZoneWithSanViewModel m_cachedModel`

- `Boolean m_cachedStateShow`

- `Boolean m_cachedSanBkgShowStatus`

- `RL02StatusBarSanEffect m_effect`


## Methods

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Void _RenderSan(Int32, Boolean)`

- `Void _RenderSanEmpty(Boolean, Boolean)`

- `Void _RenderSanBkg(Boolean, Boolean)`

- `Void _RenderSanEffectRank(SanEffectRank, Boolean)`

- `Void _RenderZoneAndVariation(String, Boolean)`

- `Void _UpdateRenderers()`

- `Void _Render(Boolean, Boolean)`

- `Boolean <Init>b__34_0()`

- `String <Init>b__34_1()`

- `Int32 <Init>b__34_2()`

- `Boolean <Init>b__34_3()`

- `Boolean <Init>b__34_4()`

- `SanEffectRank <Init>b__34_5()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_DispatchMenuEffects(List`1)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02StatusBarZoneObjectWithSan : RoguelikeMenuObject`1
{
	private const Single SAN_CHANGE_TWEEN_DURATION; // 0x0
	private const Int32 SAN_MASK_BAR_WIDTH; // 0x0
	private const Int32 SAN_MASK_BAR_HEIGHT; // 0x0
	private static readonly Color SAN_TEXT_COLOR; // 0x0
	private static readonly Type[] STATES_NOT_SHOW; // 0x10
	private static readonly Type[] STATES_SAN_BKG_SHOW; // 0x18
	private GameObject _pnlContent; // 0x28
	private Button _btnDetail; // 0x30
	private Text _textZoneName; // 0x38
	private UIAtlasImage _imageZoneNum; // 0x40
	private UIAtlasObject _imageZoneNumAtlas; // 0x48
	private AtlasConfig[] _zoneNumAtlasConfigs; // 0x50
	private GameObject _panelVariation; // 0x58
	private VariationItem[] _variationItems; // 0x60
	private GameObject _panelSan; // 0x68
	private CanvasGroup _canvasSanBkg; // 0x70
	private CanvasGroup _canvasSanEmpty; // 0x78
	private Text _textSanNum; // 0x80
	private RectTransform _maskSan; // 0x88
	private RL02StatusBarSanEffect _effectPrefab; // 0x90
	private Dictionary`2 m_zoneNumAtlasNameDict; // 0x98
	private Tween m_sanTween; // 0xa0
	private FadeSwitchTween m_sanBkgShowTween; // 0xa8
	private FadeSwitchTween m_sanEmptyShowTween; // 0xb0
	private RoguelikeStatusBarTextTweener m_sanTextTweener; // 0xb8
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0xc0
	private RoguelikeMenuViewRenderer`1 m_zoneRenderer; // 0xc8
	private List`1 m_renderers; // 0xd0
	private RL02ZoneWithSanViewModel m_cachedModel; // 0xd8
	private Boolean m_cachedStateShow; // 0xe0
	private Boolean m_cachedSanBkgShowStatus; // 0xe1
	private RL02StatusBarSanEffect m_effect; // 0xe8
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_CollectMenuEffectPrefabs; // 0x28
	private static DelegateBridge __Hotfix0_DispatchMenuEffects; // 0x30
	private static DelegateBridge __Hotfix0_get_menuType; // 0x38
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x40
	private static DelegateBridge __Hotfix0__RenderSan; // 0x48
	private static DelegateBridge __Hotfix0__RenderSanEmpty; // 0x50
	private static DelegateBridge __Hotfix0__RenderSanBkg; // 0x58
	private static DelegateBridge __Hotfix0__RenderSanEffectRank; // 0x60
	private static DelegateBridge __Hotfix0__RenderZoneAndVariation; // 0x68
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0x70
	private static DelegateBridge __Hotfix0__Render; // 0x78
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b6cc0c VA: 0x7595184c0c
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b6d510 VA: 0x7595185510
	public override List`1 CollectMenuEffectPrefabs() { }
	// RVA: 0x2b6d63c VA: 0x759518563c
	public override Void DispatchMenuEffects(List`1 instanceList) { }
	// RVA: 0x2b6d778 VA: 0x7595185778
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b6d7f0 VA: 0x75951857f0
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b6d8f8 VA: 0x75951858f8
	private Void _RenderSan(Int32 value, Boolean fastMode) { }
	// RVA: 0x2b6dac0 VA: 0x7595185ac0
	private Void _RenderSanEmpty(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b6db88 VA: 0x7595185b88
	private Void _RenderSanBkg(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b6dca8 VA: 0x7595185ca8
	private Void _RenderSanEffectRank(SanEffectRank rank, Boolean fastMode) { }
	// RVA: 0x2b6dd94 VA: 0x7595185d94
	private Void _RenderZoneAndVariation(String zoneId, Boolean fastMode) { }
	// RVA: 0x2b6e224 VA: 0x7595186224
	private Void _UpdateRenderers() { }
	// RVA: 0x2b6e460 VA: 0x7595186460
	private Void _Render(Boolean fastMode, Boolean isFromAdapterChange) { }
	// RVA: 0x2b6e7ec VA: 0x75951867ec
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2b6e95c VA: 0x759518695c
	public override Void Render(RL02ZoneWithSanViewModel viewModel) { }
	// RVA: 0x2b6ea1c VA: 0x7595186a1c
	public Void .ctor() { }
	// RVA: 0x2b6eb10 VA: 0x7595186b10
	private static Void .cctor() { }
	// RVA: 0x2b6ed64 VA: 0x7595186d64
	private Boolean <Init>b__34_0() { }
	// RVA: 0x2b6eda4 VA: 0x7595186da4
	private String <Init>b__34_1() { }
	// RVA: 0x2b6edc0 VA: 0x7595186dc0
	private Int32 <Init>b__34_2() { }
	// RVA: 0x2b6eddc VA: 0x7595186ddc
	private Boolean <Init>b__34_3() { }
	// RVA: 0x2b6ee00 VA: 0x7595186e00
	private Boolean <Init>b__34_4() { }
	// RVA: 0x2b6ee08 VA: 0x7595186e08
	private SanEffectRank <Init>b__34_5() { }
	// RVA: 0x2b6ee24 VA: 0x7595186e24
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2b6ee2c VA: 0x7595186e2c
	private List`1 <>xLuaBaseProxy_CollectMenuEffectPrefabs() { }
	// RVA: 0x2b6ee34 VA: 0x7595186e34
	private Void <>xLuaBaseProxy_DispatchMenuEffects(List`1 P0) { }
	// RVA: 0x2b6ee3c VA: 0x7595186e3c
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
}
```