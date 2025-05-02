# GachaPhase1

**Namespace:** `Torappu.Gacha`


## Fields

- `Single _playTime`

- `ParticleSystem _particleSystem`

- `PanelCharacterIllust _characterillust`

- `PanelCharacterInfo _characterInfo`

- `PanelCharacterDialog _characterDialog`

- `RectTransform _interactivePanel`

- `RectTransform _skipAllBtn`

- `Animation _animation`

- `FxDelay _imageIllust`

- `GachaController m_controller`

- `CharacterData m_character`

- `Boolean m_canSkip`


## Properties

- `RectTransform interactivePanel`


## Methods

- `RectTransform get_interactivePanel()`

- `IEnumerator _PlayWithDynEntrance(GachaController, PlayMode, CharUISkinStruct)`

- `Void OnSkipAllBtnClicked()`

- `Void _DoSkipToDialog(GachaController, PlayMode)`

- `Void _Reset()`

- `Void _SetData(CharacterConfig, CharacterData, ItemBundle[], Boolean)`

- `Texture2D _GetDisplayLogo(String)`

- `Void _SetCanSkip(Boolean)`

- `Void _ResetPopStars()`

- `IEnumerator <>xLuaBaseProxy_SkipToEndAsync(GachaController, PlayMode)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnDisposeForReuse()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class GachaPhase1 : GachaPhase
{
	private const String MASK_TEXTURE; // 0x0
	private const Single FORWARD_PARTICLE_SYSTEM_SIMULATE_TIME_ON_SKIP; // 0x0
	private Single _playTime; // 0x18
	private ParticleSystem _particleSystem; // 0x20
	private Renderer[] _campRenderers; // 0x28
	private Renderer[] _characterMaskRenderers; // 0x30
	private PanelCharacterIllust _characterillust; // 0x38
	private PanelCharacterInfo _characterInfo; // 0x40
	private PanelCharacterDialog _characterDialog; // 0x48
	private RectTransform _interactivePanel; // 0x50
	private RectTransform _skipAllBtn; // 0x58
	private Animation _animation; // 0x60
	private AnimationClip[] _rarityAnimations; // 0x68
	private FxDelay _imageIllust; // 0x70
	private GameObject[] _inactiveWhenSkip; // 0x78
	private GameObject[] _popStarsToReset; // 0x80
	private GachaController m_controller; // 0x88
	private CharacterData m_character; // 0x90
	private Boolean m_canSkip; // 0x98
	private static DelegateBridge __Hotfix0_get_interactivePanel; // 0x0
	private static DelegateBridge __Hotfix0_get_canSkip; // 0x8
	private static DelegateBridge __Hotfix0_Play; // 0x10
	private static DelegateBridge __Hotfix0__PlayWithDynEntrance; // 0x18
	private static DelegateBridge __Hotfix0_SkipToEnd; // 0x20
	private static DelegateBridge __Hotfix0_SkipToEndAsync; // 0x28
	private static DelegateBridge __Hotfix0_PreloadSounds; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_OnSkipAllBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0__DoSkipToDialog; // 0x48
	private static DelegateBridge __Hotfix0__Reset; // 0x50
	private static DelegateBridge __Hotfix0__SetData; // 0x58
	private static DelegateBridge __Hotfix0__GetDisplayLogo; // 0x60
	private static DelegateBridge __Hotfix0__SetCanSkip; // 0x68
	private static DelegateBridge __Hotfix0__ResetPopStars; // 0x70
	private static DelegateBridge __Hotfix0_OnDisposeForReuse; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public RectTransform interactivePanel { get; }
	public override Boolean canSkip { get; }

	// RVA: 0x36ff5ec VA: 0x7595d175ec
	public RectTransform get_interactivePanel() { }
	// RVA: 0x36ff654 VA: 0x7595d17654
	public override Boolean get_canSkip() { }
	// RVA: 0x36ff6bc VA: 0x7595d176bc
	public override IEnumerator Play(GachaController controller, PlayMode playMode) { }
	// RVA: 0x36ff7c0 VA: 0x7595d177c0
	private IEnumerator _PlayWithDynEntrance(GachaController controller, PlayMode playMode, CharUISkinStruct skin) { }
	// RVA: 0x36ff8f4 VA: 0x7595d178f4
	public override Void SkipToEnd(GachaController controller, PlayMode playMode) { }
	// RVA: 0x36ffb74 VA: 0x7595d17b74
	public override IEnumerator SkipToEndAsync(GachaController controller, PlayMode playMode) { }
	// RVA: 0x36ffc78 VA: 0x7595d17c78
	public override Void PreloadSounds(PlayMode playMode, RarityRank rarity, Boolean isMultipleGacha) { }
	// RVA: 0x36ffdd4 VA: 0x7595d17dd4
	public override Void OnInit() { }
	// RVA: 0x36fff94 VA: 0x7595d17f94
	public Void OnSkipAllBtnClicked() { }
	// RVA: 0x36ffa50 VA: 0x7595d17a50
	private Void _DoSkipToDialog(GachaController controller, PlayMode playMode) { }
	// RVA: 0x3700050 VA: 0x7595d18050
	private Void _Reset() { }
	// RVA: 0x37000dc VA: 0x7595d180dc
	private Void _SetData(CharacterConfig charConfig, CharacterData character, ItemBundle[] items, Boolean isNew) { }
	// RVA: 0x3700394 VA: 0x7595d18394
	private Texture2D _GetDisplayLogo(String powerId) { }
	// RVA: 0x36ffeb8 VA: 0x7595d17eb8
	private Void _SetCanSkip(Boolean canSkip) { }
	// RVA: 0x3700480 VA: 0x7595d18480
	private Void _ResetPopStars() { }
	// RVA: 0x3700598 VA: 0x7595d18598
	protected override Void OnDisposeForReuse() { }
	// RVA: 0x3700630 VA: 0x7595d18630
	public Void .ctor() { }
	// RVA: 0x370076c VA: 0x7595d1876c
	private IEnumerator <>xLuaBaseProxy_SkipToEndAsync(GachaController P0, PlayMode P1) { }
	// RVA: 0x3700774 VA: 0x7595d18774
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x370077c VA: 0x7595d1877c
	private Void <>xLuaBaseProxy_OnDisposeForReuse() { }
}
```