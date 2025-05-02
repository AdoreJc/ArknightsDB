# UIBattleGameCityMinerCharacterMenuPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `MenuInfo _leftMenu`

- `MenuInfo _rightMenu`

- `Follower2D _follower`

- `Card m_card`

- `MenuInfo m_curMenu`

- `Boolean m_isSkillCasting`

- `Boolean m_isSkillAmountShown`

- `Boolean m_isOpen`


## Properties

- `Boolean isOpen`

- `Boolean isSkillCasting`


## Methods

- `Boolean get_isOpen()`

- `Void set_isOpen(Boolean)`

- `Boolean get_isSkillCasting()`

- `Void set_isSkillCasting(Boolean)`

- `Void OnInit()`

- `Void OnSkillButtonClicked()`

- `Void Show(Character)`

- `Void Hide()`

- `Void _SetSkillCastingInternal(Boolean, Boolean)`

- `Void _SetData(Character)`

- `Void _UpdateData()`

- `Void _UpdateSkillCount(Character, Boolean)`

- `Void _SetOpenInternal(Boolean, Boolean)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleGameCityMinerCharacterMenuPanel : MonoBehaviour, IUICharacterMenuPanel, IHotfixable
{
	private const String UI_LEFT_BLACKBOARD_KEY; // 0x0
	private MenuInfo _leftMenu; // 0x18
	private MenuInfo _rightMenu; // 0x20
	private Follower2D _follower; // 0x28
	private ObjectPtr`1 m_character; // 0x30
	private Card m_card; // 0x40
	private MenuInfo m_curMenu; // 0x48
	private Boolean m_isSkillCasting; // 0x50
	private Boolean m_isSkillAmountShown; // 0x51
	private Boolean m_isOpen; // 0x52
	private static DelegateBridge __Hotfix0_get_isOpen; // 0x0
	private static DelegateBridge __Hotfix0_set_isOpen; // 0x8
	private static DelegateBridge __Hotfix0_get_isSkillCasting; // 0x10
	private static DelegateBridge __Hotfix0_set_isSkillCasting; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnSkillButtonClicked; // 0x28
	private static DelegateBridge __Hotfix0_Show; // 0x30
	private static DelegateBridge __Hotfix0_Hide; // 0x38
	private static DelegateBridge __Hotfix0__SetSkillCastingInternal; // 0x40
	private static DelegateBridge __Hotfix0__SetData; // 0x48
	private static DelegateBridge __Hotfix0__UpdateData; // 0x50
	private static DelegateBridge __Hotfix0__UpdateSkillCount; // 0x58
	private static DelegateBridge __Hotfix0__SetOpenInternal; // 0x60
	private static DelegateBridge __Hotfix0_Update; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean isOpen { get; set; }
	protected Boolean isSkillCasting { get; set; }

	// RVA: 0x203bf00 VA: 0x7594653f00
	public Boolean get_isOpen() { }
	// RVA: 0x203bf68 VA: 0x7594653f68
	private Void set_isOpen(Boolean value) { }
	// RVA: 0x203c0ac VA: 0x75946540ac
	protected Boolean get_isSkillCasting() { }
	// RVA: 0x203c114 VA: 0x7594654114
	private Void set_isSkillCasting(Boolean value) { }
	// RVA: 0x203c278 VA: 0x7594654278
	public Void OnInit() { }
	// RVA: 0x203c2e8 VA: 0x75946542e8
	public Void OnSkillButtonClicked() { }
	// RVA: 0x203c428 VA: 0x7594654428
	public Void Show(Character character) { }
	// RVA: 0x203cafc VA: 0x7594654afc
	public Void Hide() { }
	// RVA: 0x203c198 VA: 0x7594654198
	private Void _SetSkillCastingInternal(Boolean value, Boolean force) { }
	// RVA: 0x203c594 VA: 0x7594654594
	private Void _SetData(Character character) { }
	// RVA: 0x203cdfc VA: 0x7594654dfc
	private Void _UpdateData() { }
	// RVA: 0x203cbdc VA: 0x7594654bdc
	private Void _UpdateSkillCount(Character character, Boolean force) { }
	// RVA: 0x203bfec VA: 0x7594653fec
	private Void _SetOpenInternal(Boolean value, Boolean force) { }
	// RVA: 0x203d4e0 VA: 0x75946554e0
	private Void Update() { }
	// RVA: 0x203d548 VA: 0x7594655548
	public Void .ctor() { }
}
```