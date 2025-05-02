# UICharacterInfoPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single m_tweenTime`

- `BattleIllustration _illustHandler`

- `UICharacterInfoSubPanel _statusSubPanel`

- `UICharacterInfoSubPanel _tabGroupSubPanel`

- `Boolean m_isOpen`

- `ModeType <mode>k__BackingField`

- `Card <card>k__BackingField`

- `UICharacterInfoSubPanel m_statusSubPanel`

- `UICharacterInfoSubPanel m_tabGroupSubPanel`

- `UICharacterInfoSubPanel m_additionSubPanel`

- `Image m_illust`


## Properties

- `ModeType mode`

- `Card card`

- `UICharacterInfoSubPanel statusSubPanel`

- `UICharacterInfoSubPanel tabGroupSubPanel`

- `UICharacterInfoSubPanel additionSubPanel`

- `UICharacterInfoTabGroupSubPanel tabGroupSubPanelCasted`

- `UICharacterTabGroup uiCharacterTabGroup`

- `BattleIllustration illustHandler`

- `Boolean isOpen`


## Methods

- `ModeType get_mode()`

- `Void set_mode(ModeType)`

- `Card get_card()`

- `Void set_card(Card)`

- `Void set_character(ObjectPtr`1)`

- `UICharacterInfoSubPanel get_statusSubPanel()`

- `UICharacterInfoSubPanel get_tabGroupSubPanel()`

- `UICharacterInfoSubPanel get_additionSubPanel()`

- `UICharacterInfoTabGroupSubPanel get_tabGroupSubPanelCasted()`

- `UICharacterTabGroup get_uiCharacterTabGroup()`

- `BattleIllustration get_illustHandler()`

- `Boolean get_isOpen()`

- `Void set_isOpen(Boolean)`

- `Void OnInit()`

- `Void ShowCard(Card, Boolean)`

- `Void ShowCharacter(Character, Boolean)`

- `Void Hide(Card)`

- `Void _SetData()`

- `Void _LoadIllust(BattleCharacterData, Boolean)`

- `Void Awake()`

- `Void Update()`

- `Void _UpdateData()`

- `Void RefreshHookedSubPanels()`

- `Void OnDestroy()`

- `Void <set_isOpen>b__37_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterInfoPanel : MonoBehaviour, IHotfixable
{
	private Single m_tweenTime; // 0x18
	private BattleIllustration _illustHandler; // 0x20
	private UICharacterInfoSubPanel _statusSubPanel; // 0x28
	private UICharacterInfoSubPanel _tabGroupSubPanel; // 0x30
	private CanvasGroup[] m_canvasGroup; // 0x38
	private Boolean m_isOpen; // 0x40
	private ModeType <mode>k__BackingField; // 0x44
	private Card <card>k__BackingField; // 0x48
	private ObjectPtr`1 <character>k__BackingField; // 0x50
	private UICharacterInfoSubPanel m_statusSubPanel; // 0x60
	private UICharacterInfoSubPanel m_tabGroupSubPanel; // 0x68
	private UICharacterInfoSubPanel m_additionSubPanel; // 0x70
	private Image m_illust; // 0x78
	private Dictionary`2 m_hookedSubPanels; // 0x80
	private static DelegateBridge __Hotfix0_get_mode; // 0x0
	private static DelegateBridge __Hotfix0_set_mode; // 0x8
	private static DelegateBridge __Hotfix0_get_card; // 0x10
	private static DelegateBridge __Hotfix0_set_card; // 0x18
	private static DelegateBridge __Hotfix0_get_character; // 0x20
	private static DelegateBridge __Hotfix0_set_character; // 0x28
	private static DelegateBridge __Hotfix0_get_statusSubPanel; // 0x30
	private static DelegateBridge __Hotfix0_get_tabGroupSubPanel; // 0x38
	private static DelegateBridge __Hotfix0_get_additionSubPanel; // 0x40
	private static DelegateBridge __Hotfix0_get_tabGroupSubPanelCasted; // 0x48
	private static DelegateBridge __Hotfix0_get_uiCharacterTabGroup; // 0x50
	private static DelegateBridge __Hotfix0_get_illustHandler; // 0x58
	private static DelegateBridge __Hotfix0_get_isOpen; // 0x60
	private static DelegateBridge __Hotfix0_set_isOpen; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x70
	private static DelegateBridge __Hotfix0_ShowCard; // 0x78
	private static DelegateBridge __Hotfix0_ShowCharacter; // 0x80
	private static DelegateBridge __Hotfix0_Hide; // 0x88
	private static DelegateBridge __Hotfix0__SetData; // 0x90
	private static DelegateBridge __Hotfix0__LoadIllust; // 0x98
	private static DelegateBridge __Hotfix0_Awake; // 0xa0
	private static DelegateBridge __Hotfix0_Update; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateData; // 0xb0
	private static DelegateBridge __Hotfix0_RefreshHookedSubPanels; // 0xb8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public ModeType mode { get; set; }
	private Card card { get; set; }
	private ObjectPtr`1 character { get; set; }
	private UICharacterInfoSubPanel statusSubPanel { get; }
	private UICharacterInfoSubPanel tabGroupSubPanel { get; }
	private UICharacterInfoSubPanel additionSubPanel { get; }
	public UICharacterInfoTabGroupSubPanel tabGroupSubPanelCasted { get; }
	public UICharacterTabGroup uiCharacterTabGroup { get; }
	public BattleIllustration illustHandler { get; }
	public Boolean isOpen { get; set; }

	// RVA: 0x20328a0 VA: 0x759464a8a0
	public ModeType get_mode() { }
	// RVA: 0x2032908 VA: 0x759464a908
	private Void set_mode(ModeType value) { }
	// RVA: 0x2032984 VA: 0x759464a984
	private Card get_card() { }
	// RVA: 0x20329ec VA: 0x759464a9ec
	private Void set_card(Card value) { }
	// RVA: 0x2032a70 VA: 0x759464aa70
	private ObjectPtr`1 get_character() { }
	// RVA: 0x2032ad4 VA: 0x759464aad4
	private Void set_character(ObjectPtr`1 value) { }
	// RVA: 0x2032b64 VA: 0x759464ab64
	private UICharacterInfoSubPanel get_statusSubPanel() { }
	// RVA: 0x2032bcc VA: 0x759464abcc
	private UICharacterInfoSubPanel get_tabGroupSubPanel() { }
	// RVA: 0x2032c34 VA: 0x759464ac34
	private UICharacterInfoSubPanel get_additionSubPanel() { }
	// RVA: 0x2032c9c VA: 0x759464ac9c
	public UICharacterInfoTabGroupSubPanel get_tabGroupSubPanelCasted() { }
	// RVA: 0x2032d54 VA: 0x759464ad54
	public UICharacterTabGroup get_uiCharacterTabGroup() { }
	// RVA: 0x2032e24 VA: 0x759464ae24
	public BattleIllustration get_illustHandler() { }
	// RVA: 0x2032e8c VA: 0x759464ae8c
	public Boolean get_isOpen() { }
	// RVA: 0x2032ef4 VA: 0x759464aef4
	private Void set_isOpen(Boolean value) { }
	// RVA: 0x203318c VA: 0x759464b18c
	public Void OnInit() { }
	// RVA: 0x20337d4 VA: 0x759464b7d4
	public Void ShowCard(Card card, Boolean foldIllust) { }
	// RVA: 0x2021704 VA: 0x7594639704
	public Void ShowCharacter(Character character, Boolean foldIllust) { }
	// RVA: 0x20201dc VA: 0x75946381dc
	public Void Hide(Card card) { }
	// RVA: 0x2033bcc VA: 0x759464bbcc
	private Void _SetData() { }
	// RVA: 0x20339d8 VA: 0x759464b9d8
	private Void _LoadIllust(BattleCharacterData data, Boolean fold) { }
	// RVA: 0x2034038 VA: 0x759464c038
	private Void Awake() { }
	// RVA: 0x203411c VA: 0x759464c11c
	private Void Update() { }
	// RVA: 0x2033dfc VA: 0x759464bdfc
	private Void _UpdateData() { }
	// RVA: 0x2033334 VA: 0x759464b334
	public Void RefreshHookedSubPanels() { }
	// RVA: 0x203419c VA: 0x759464c19c
	private Void OnDestroy() { }
	// RVA: 0x20342a4 VA: 0x759464c2a4
	public Void .ctor() { }
	// RVA: 0x2034374 VA: 0x759464c374
	private Void <set_isOpen>b__37_0() { }
}
```