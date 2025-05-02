# LegionUICharacterMenuDetailItem

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GameObject _bgPanel`

- `GameObject _detailPanel`

- `Text _levelLabel`

- `Text _levelLabelHL`

- `GameObject _normalPanel`

- `GameObject _highlightPanel`

- `Image _highLightImage`

- `Image _professionImage`

- `Image _backProfessionImage`

- `Image _backGroundImage`

- `ProfessionCategory m_currentProfession`

- `Tween m_hlEffectTween`

- `Tween m_hlTextEffectTween`

- `Color m_defaultBgColor`

- `Color m_maxLevelBgColor`


## Properties

- `ProfessionCategory currentProfession`


## Methods

- `ProfessionCategory get_currentProfession()`

- `Void Awake()`

- `Void SetData(Int32, ProfessionCategory)`

- `Void ApplyBgMaxLevel(Boolean)`

- `Void ShowHighLight()`

- `Void _ShowHighLightEffect()`

- `Void OnDestroy()`

- `Void _SetProfessionIcon(Image, ProfessionCategory, ProfessionSpritePair[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class LegionUICharacterMenuDetailItem : MonoBehaviour, IHotfixable
{
	private GameObject _bgPanel; // 0x18
	private GameObject _detailPanel; // 0x20
	private Text _levelLabel; // 0x28
	private Text _levelLabelHL; // 0x30
	private GameObject _normalPanel; // 0x38
	private GameObject _highlightPanel; // 0x40
	private Image _highLightImage; // 0x48
	private Image _professionImage; // 0x50
	private Image _backProfessionImage; // 0x58
	private Image _backGroundImage; // 0x60
	private ProfessionSpritePair[] _professionIcons; // 0x68
	private ProfessionSpritePair[] _backProfessionIcons; // 0x70
	private ProfessionCategory m_currentProfession; // 0x78
	private Tween m_hlEffectTween; // 0x80
	private Tween m_hlTextEffectTween; // 0x88
	private Color m_defaultBgColor; // 0x90
	private Color m_maxLevelBgColor; // 0xa0
	private readonly String TWEEN_BG_DEFAULT_COLOR; // 0xb0
	private readonly String TWEEN_BG_MAX_LEVEL_COLOR; // 0xb8
	private readonly Single TWEEN_BG_MAX_LEVEL_DOCOLOR_DURATION; // 0xc0
	private readonly Single TWEEN_MAX_LEVEL_SHINING_ALPHA_START; // 0xc4
	private readonly Single TWEEN_MAX_LEVEL_SHINING_ALPHA_STEP1; // 0xc8
	private readonly Single TWEEN_MAX_LEVEL_SHINING_ALPHA_STEP1_DURATION; // 0xcc
	private readonly Single TWEEN_MAX_LEVEL_SHINING_ALPHA_STEP2; // 0xd0
	private readonly Single TWEEN_MAX_LEVEL_SHINING_ALPHA_STEP2_DURATION; // 0xd4
	private readonly Single TWEEN_MAX_LEVEL_TEXT_ALPHA_START; // 0xd8
	private readonly Single TWEEN_MAX_LEVEL_TEXT_ALPHA_STEP1; // 0xdc
	private readonly Single TWEEN_MAX_LEVEL_TEXT_ALPHA_STEP1_DURATION; // 0xe0
	private readonly Single TWEEN_MAX_LEVEL_TEXT_ALPHA_STEP2; // 0xe4
	private readonly Single TWEEN_MAX_LEVEL_TEXT_ALPHA_STEP2_DURATION; // 0xe8
	private readonly Single TWEEN_MAX_LEVEL_TEXT_ALPHA_STEP3; // 0xec
	private readonly Single TWEEN_MAX_LEVEL_TEXT_ALPHA_STEP3_DURATION; // 0xf0
	private static DelegateBridge __Hotfix0_get_currentProfession; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyBgMaxLevel; // 0x18
	private static DelegateBridge __Hotfix0_ShowHighLight; // 0x20
	private static DelegateBridge __Hotfix0__ShowHighLightEffect; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0__SetProfessionIcon; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public ProfessionCategory currentProfession { get; }

	// RVA: 0x203e890 VA: 0x7594656890
	public ProfessionCategory get_currentProfession() { }
	// RVA: 0x203f4f0 VA: 0x75946574f0
	private Void Awake() { }
	// RVA: 0x203e1d0 VA: 0x75946561d0
	public Void SetData(Int32 level, ProfessionCategory profession) { }
	// RVA: 0x203e6b8 VA: 0x75946566b8
	public Void ApplyBgMaxLevel(Boolean showTween) { }
	// RVA: 0x203e8f8 VA: 0x75946568f8
	public Void ShowHighLight() { }
	// RVA: 0x203f6b8 VA: 0x75946576b8
	private Void _ShowHighLightEffect() { }
	// RVA: 0x203fd70 VA: 0x7594657d70
	private Void OnDestroy() { }
	// RVA: 0x203f5a4 VA: 0x75946575a4
	private Void _SetProfessionIcon(Image professionImage, ProfessionCategory profession, ProfessionSpritePair[] professionIcons) { }
	// RVA: 0x203fe04 VA: 0x7594657e04
	public Void .ctor() { }
}
```