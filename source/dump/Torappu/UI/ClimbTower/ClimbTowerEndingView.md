# ClimbTowerEndingView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textTowerName`

- `Text _textTowerSubName`

- `Text _textFinishTime`

- `TwoStateToggle _finishToggle`

- `Image _imgTowerIcon`

- `Text _textFloorCurr`

- `Text _textFloorTarget`

- `GameObject _imgHard`

- `Color _colorHard`

- `Color _colorNormal`

- `Color _colorTowerIconHard`

- `Color _colorTowerIconNormal`

- `GameObject _panelGodCard`

- `Image _imgMainCard`

- `GameObject _prefabCharCard`

- `GameObject _prefabCurseCardAndTrapCard`

- `AnimationWrapper _animationWrapper`

- `CanvasGroup _blackMask`

- `CanvasGroup _panelUI`

- `Boolean m_isLowerItemMax`

- `Boolean m_isHigherItemMax`

- `Boolean m_hasInited`

- `Int32 m_cachedCharCardRowCount`

- `ClimbTowerEndingState <state>k__BackingField`

- `Boolean <hasPlayedAnim>k__BackingField`

- `FadeSwitchTween <blackMaskSwitch>k__BackingField`

- `FadeSwitchTween <uiPanelSwitchTween>k__BackingField`

- `UIPage <page>k__BackingField`


## Properties

- `ClimbTowerEndingState state`

- `Boolean hasPlayedAnim`

- `FadeSwitchTween blackMaskSwitch`

- `FadeSwitchTween uiPanelSwitchTween`

- `UIPage page`


## Methods

- `ClimbTowerEndingState get_state()`

- `Void set_state(ClimbTowerEndingState)`

- `Boolean get_hasPlayedAnim()`

- `Void set_hasPlayedAnim(Boolean)`

- `FadeSwitchTween get_blackMaskSwitch()`

- `Void set_blackMaskSwitch(FadeSwitchTween)`

- `FadeSwitchTween get_uiPanelSwitchTween()`

- `Void set_uiPanelSwitchTween(FadeSwitchTween)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void ShowBlackMask()`

- `Void Render(ClimbTowerEndingViewModel, Int32)`

- `IEnumerator ShowCoroutine()`

- `IEnumerator BeforeShowTopState()`

- `IEnumerator _PlayCharacterPopUpSound(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndingView : MonoBehaviour, IHotfixable
{
	private const String FLOOR_TARGET_FORMAT; // 0x0
	private const String CHAR_CARD_ANIM_NAME; // 0x0
	public const Int32 CHAR_CARD_NUM_PER_ROW; // 0x0
	private const String ITEM_GAIN_COUNT_FORMAT; // 0x0
	private Text _textTowerName; // 0x18
	private Text _textTowerSubName; // 0x20
	private Text _textFinishTime; // 0x28
	private TwoStateToggle _finishToggle; // 0x30
	private Image _imgTowerIcon; // 0x38
	private Text _textFloorCurr; // 0x40
	private Text _textFloorTarget; // 0x48
	private GameObject _imgHard; // 0x50
	private Color _colorHard; // 0x58
	private Color _colorNormal; // 0x68
	private Color _colorTowerIconHard; // 0x78
	private Color _colorTowerIconNormal; // 0x88
	private GameObject _panelGodCard; // 0x98
	private Image _imgMainCard; // 0xa0
	private GameObject[] _panelSubCardBranches; // 0xa8
	private Image[] _imgSubcards; // 0xb0
	private RectTransform[] _characterCardTrans; // 0xb8
	private RectTransform[] _curseCardAndTrapCardTrans; // 0xc0
	private GameObject _prefabCharCard; // 0xc8
	private GameObject _prefabCurseCardAndTrapCard; // 0xd0
	private AnimationWrapper _animationWrapper; // 0xd8
	private CanvasGroup _blackMask; // 0xe0
	private CanvasGroup _panelUI; // 0xe8
	private Boolean m_isLowerItemMax; // 0xf0
	private Boolean m_isHigherItemMax; // 0xf1
	private Boolean m_hasInited; // 0xf2
	private Int32 m_cachedCharCardRowCount; // 0xf4
	private ClimbTowerEndingCharacterCardView[] m_characterCard; // 0xf8
	private ClimbTowerEndingTrapCardView[] m_curseCardAndTrapCard; // 0x100
	private ClimbTowerEndingState <state>k__BackingField; // 0x108
	private Boolean <hasPlayedAnim>k__BackingField; // 0x110
	private FadeSwitchTween <blackMaskSwitch>k__BackingField; // 0x118
	private FadeSwitchTween <uiPanelSwitchTween>k__BackingField; // 0x120
	private UIPage <page>k__BackingField; // 0x128
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_get_hasPlayedAnim; // 0x10
	private static DelegateBridge __Hotfix0_set_hasPlayedAnim; // 0x18
	private static DelegateBridge __Hotfix0_get_blackMaskSwitch; // 0x20
	private static DelegateBridge __Hotfix0_set_blackMaskSwitch; // 0x28
	private static DelegateBridge __Hotfix0_get_uiPanelSwitchTween; // 0x30
	private static DelegateBridge __Hotfix0_set_uiPanelSwitchTween; // 0x38
	private static DelegateBridge __Hotfix0_get_page; // 0x40
	private static DelegateBridge __Hotfix0_set_page; // 0x48
	private static DelegateBridge __Hotfix0_ShowBlackMask; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x58
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_BeforeShowTopState; // 0x68
	private static DelegateBridge __Hotfix0__PlayCharacterPopUpSound; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	private ClimbTowerEndingState state { get; set; }
	public Boolean hasPlayedAnim { get; set; }
	public FadeSwitchTween blackMaskSwitch { get; set; }
	public FadeSwitchTween uiPanelSwitchTween { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2ca0be4 VA: 0x75952b8be4
	private ClimbTowerEndingState get_state() { }
	// RVA: 0x2c9bf28 VA: 0x75952b3f28
	public Void set_state(ClimbTowerEndingState value) { }
	// RVA: 0x2c9c85c VA: 0x75952b485c
	public Boolean get_hasPlayedAnim() { }
	// RVA: 0x2ca0c4c VA: 0x75952b8c4c
	private Void set_hasPlayedAnim(Boolean value) { }
	// RVA: 0x2ca0ccc VA: 0x75952b8ccc
	public FadeSwitchTween get_blackMaskSwitch() { }
	// RVA: 0x2ca0d34 VA: 0x75952b8d34
	private Void set_blackMaskSwitch(FadeSwitchTween value) { }
	// RVA: 0x2ca0db8 VA: 0x75952b8db8
	public FadeSwitchTween get_uiPanelSwitchTween() { }
	// RVA: 0x2ca0e20 VA: 0x75952b8e20
	private Void set_uiPanelSwitchTween(FadeSwitchTween value) { }
	// RVA: 0x2ca0ea4 VA: 0x75952b8ea4
	private UIPage get_page() { }
	// RVA: 0x2c9bfac VA: 0x75952b3fac
	public Void set_page(UIPage value) { }
	// RVA: 0x2c9c030 VA: 0x75952b4030
	public Void ShowBlackMask() { }
	// RVA: 0x2c9cda8 VA: 0x75952b4da8
	public Void Render(ClimbTowerEndingViewModel viewModel, Int32 rowCount) { }
	// RVA: 0x2c9c410 VA: 0x75952b4410
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x2c9d60c VA: 0x75952b560c
	public IEnumerator BeforeShowTopState() { }
	// RVA: 0x2ca1308 VA: 0x75952b9308
	private IEnumerator _PlayCharacterPopUpSound(Int32 rowCount) { }
	// RVA: 0x2ca0f0c VA: 0x75952b8f0c
	private Void _InitIfNot() { }
	// RVA: 0x2ca13e4 VA: 0x75952b93e4
	public Void .ctor() { }
}
```