# UICharacterMenuPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Button _skillButton`

- `Button _withdrawButton`

- `Transform _withdrawPanel`

- `Slider _skillToNextSlider`

- `Slider _skillCastingSlider`

- `Image _skillIcon`

- `Image _skillReadyMark`

- `Image _skillNotReadyMark`

- `Image _skillStopMark`

- `Image _skillBulletMark`

- `Text _skillBulletLabel`

- `Image _skillReadyButShowStackProcessMark`

- `MaskableGraphic _skillAutoMark`

- `Transform _skillAmountPanel`

- `Text _skillAmountNum`

- `Text _skillProgressLabel`

- `Color _skillProgressLabelNormalColor`

- `Color _skillProgressLabelStackColor`

- `Toggle _skillRangeToggle`

- `Transform _skillPanel`

- `Follower2D _follower`

- `Card m_card`

- `Boolean m_isSkillCasting`

- `Boolean m_isSkillAmountShown`

- `Boolean m_isOpen`


## Properties

- `Boolean isOpen`

- `Transform withdrawPanel`

- `Button withdrawButton`

- `Boolean isSkillCasting`


## Methods

- `Boolean get_isOpen()`

- `Void set_isOpen(Boolean)`

- `Transform get_withdrawPanel()`

- `Button get_withdrawButton()`

- `Boolean get_isSkillCasting()`

- `Void set_isSkillCasting(Boolean)`

- `Void OnInit()`

- `Void OnWithdrawButtonClicked()`

- `Void OnSkillButtonClicked()`

- `Void OnSkillRangeToggled()`

- `Void Show(Character)`

- `Void Hide()`

- `Void _SetSkillCastingInternal(Boolean, Boolean)`

- `Void _SetData(Character)`

- `Void _UpdateSkillToggle(Character)`

- `Void _UpdateWithDrawablePanel(Character, Boolean)`

- `Void _UpdateData()`

- `Void _UpdateSkillCount(Character, Boolean)`

- `Void _SetOpenInternal(Boolean, Boolean)`

- `Void _DoUpdateRangeToShow(Character)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterMenuPanel : MonoBehaviour, IUICharacterMenuPanel, IHotfixable
{
	private Button _skillButton; // 0x18
	private Button _withdrawButton; // 0x20
	private Transform _withdrawPanel; // 0x28
	private Slider _skillToNextSlider; // 0x30
	private Slider _skillCastingSlider; // 0x38
	private Image _skillIcon; // 0x40
	private Image _skillReadyMark; // 0x48
	private Image _skillNotReadyMark; // 0x50
	private Image _skillStopMark; // 0x58
	private Image _skillBulletMark; // 0x60
	private Text _skillBulletLabel; // 0x68
	private Image _skillReadyButShowStackProcessMark; // 0x70
	private MaskableGraphic _skillAutoMark; // 0x78
	private Transform _skillAmountPanel; // 0x80
	private Text _skillAmountNum; // 0x88
	private Text _skillProgressLabel; // 0x90
	private Color _skillProgressLabelNormalColor; // 0x98
	private Color _skillProgressLabelStackColor; // 0xa8
	private Toggle _skillRangeToggle; // 0xb8
	private Transform _skillPanel; // 0xc0
	private Follower2D _follower; // 0xc8
	private ObjectPtr`1 m_character; // 0xd0
	private Card m_card; // 0xe0
	private Boolean m_isSkillCasting; // 0xe8
	private Boolean m_isSkillAmountShown; // 0xe9
	private Boolean m_isOpen; // 0xea
	private static DelegateBridge __Hotfix0_get_isOpen; // 0x0
	private static DelegateBridge __Hotfix0_set_isOpen; // 0x8
	private static DelegateBridge __Hotfix0_get_withdrawPanel; // 0x10
	private static DelegateBridge __Hotfix0_get_withdrawButton; // 0x18
	private static DelegateBridge __Hotfix0_get_isSkillCasting; // 0x20
	private static DelegateBridge __Hotfix0_set_isSkillCasting; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnWithdrawButtonClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnSkillButtonClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnSkillRangeToggled; // 0x48
	private static DelegateBridge __Hotfix0_Show; // 0x50
	private static DelegateBridge __Hotfix0_Hide; // 0x58
	private static DelegateBridge __Hotfix0__SetSkillCastingInternal; // 0x60
	private static DelegateBridge __Hotfix0__SetData; // 0x68
	private static DelegateBridge __Hotfix0__UpdateSkillToggle; // 0x70
	private static DelegateBridge __Hotfix0__UpdateWithDrawablePanel; // 0x78
	private static DelegateBridge __Hotfix0__UpdateData; // 0x80
	private static DelegateBridge __Hotfix0__UpdateSkillCount; // 0x88
	private static DelegateBridge __Hotfix0__SetOpenInternal; // 0x90
	private static DelegateBridge __Hotfix0__DoUpdateRangeToShow; // 0x98
	private static DelegateBridge __Hotfix0_Update; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Boolean isOpen { get; set; }
	public Transform withdrawPanel { get; }
	public Button withdrawButton { get; }
	protected Boolean isSkillCasting { get; set; }

	// RVA: 0x2048e5c VA: 0x7594660e5c
	public Boolean get_isOpen() { }
	// RVA: 0x2048ec4 VA: 0x7594660ec4
	private Void set_isOpen(Boolean value) { }
	// RVA: 0x2049008 VA: 0x7594661008
	public Transform get_withdrawPanel() { }
	// RVA: 0x2049070 VA: 0x7594661070
	public Button get_withdrawButton() { }
	// RVA: 0x20490d8 VA: 0x75946610d8
	protected Boolean get_isSkillCasting() { }
	// RVA: 0x2049140 VA: 0x7594661140
	private Void set_isSkillCasting(Boolean value) { }
	// RVA: 0x20492d0 VA: 0x75946612d0
	public Void OnInit() { }
	// RVA: 0x2049340 VA: 0x7594661340
	public Void OnWithdrawButtonClicked() { }
	// RVA: 0x2049480 VA: 0x7594661480
	public Void OnSkillButtonClicked() { }
	// RVA: 0x20495c0 VA: 0x75946615c0
	public Void OnSkillRangeToggled() { }
	// RVA: 0x20497e0 VA: 0x75946617e0
	public Void Show(Character character) { }
	// RVA: 0x2049e8c VA: 0x7594661e8c
	public Void Hide() { }
	// RVA: 0x20491c4 VA: 0x75946611c4
	private Void _SetSkillCastingInternal(Boolean value, Boolean force) { }
	// RVA: 0x2049958 VA: 0x7594661958
	private Void _SetData(Character character) { }
	// RVA: 0x2049f6c VA: 0x7594661f6c
	private Void _UpdateSkillToggle(Character character) { }
	// RVA: 0x204a06c VA: 0x759466206c
	private Void _UpdateWithDrawablePanel(Character character, Boolean force) { }
	// RVA: 0x204a454 VA: 0x7594662454
	private Void _UpdateData() { }
	// RVA: 0x204a240 VA: 0x7594662240
	private Void _UpdateSkillCount(Character character, Boolean force) { }
	// RVA: 0x2048f48 VA: 0x7594660f48
	private Void _SetOpenInternal(Boolean value, Boolean force) { }
	// RVA: 0x20496c0 VA: 0x75946616c0
	private Void _DoUpdateRangeToShow(Character character) { }
	// RVA: 0x204ac60 VA: 0x7594662c60
	private Void Update() { }
	// RVA: 0x204acc8 VA: 0x7594662cc8
	public Void .ctor() { }
}
```