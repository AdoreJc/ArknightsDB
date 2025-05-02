# RoguelikeSacrificeViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean isInit`

- `PlayerRoguelikeSacrificeType m_sacrificeType`

- `String m_selectedIndexId`

- `IRoguelikeSacrifice m_selectedItem`

- `String m_emptyTip`

- `String m_defaultNameText`

- `String m_defaultUsageText`


## Properties

- `PlayerRoguelikeSacrificeType sacrificeType`

- `String selectedIndexId`

- `IRoguelikeSacrifice selectedItem`

- `String emptyTip`

- `String defaultNameText`

- `String defaultUsageText`


## Methods

- `PlayerRoguelikeSacrificeType get_sacrificeType()`

- `String get_selectedIndexId()`

- `IRoguelikeSacrifice get_selectedItem()`

- `String get_emptyTip()`

- `String get_defaultNameText()`

- `String get_defaultUsageText()`

- `Void LoadData(String, RoguelikeSacrificeModelParamBuilder)`

- `Boolean SelectItem(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSacrificeViewModel : IHotfixable
{
	public Boolean isInit; // 0x10
	private PlayerRoguelikeSacrificeType m_sacrificeType; // 0x14
	private ListDict`2 m_itemDict; // 0x18
	private List`1 m_itemList; // 0x20
	private String m_selectedIndexId; // 0x28
	private IRoguelikeSacrifice m_selectedItem; // 0x30
	private String m_emptyTip; // 0x38
	private String m_defaultNameText; // 0x40
	private String m_defaultUsageText; // 0x48
	private static DelegateBridge __Hotfix0_get_sacrificeType; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedIndexId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedItem; // 0x10
	private static DelegateBridge __Hotfix0_get_emptyTip; // 0x18
	private static DelegateBridge __Hotfix0_get_defaultNameText; // 0x20
	private static DelegateBridge __Hotfix0_get_defaultUsageText; // 0x28
	private static DelegateBridge __Hotfix0_get_itemList; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_SelectItem; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public PlayerRoguelikeSacrificeType sacrificeType { get; }
	public String selectedIndexId { get; }
	public IRoguelikeSacrifice selectedItem { get; }
	public String emptyTip { get; }
	public String defaultNameText { get; }
	public String defaultUsageText { get; }
	public List`1 itemList { get; }

	// RVA: 0x2ac1bc0 VA: 0x75950d9bc0
	public PlayerRoguelikeSacrificeType get_sacrificeType() { }
	// RVA: 0x2ac0f28 VA: 0x75950d8f28
	public String get_selectedIndexId() { }
	// RVA: 0x2abff00 VA: 0x75950d7f00
	public IRoguelikeSacrifice get_selectedItem() { }
	// RVA: 0x2ac0f90 VA: 0x75950d8f90
	public String get_emptyTip() { }
	// RVA: 0x2abff68 VA: 0x75950d7f68
	public String get_defaultNameText() { }
	// RVA: 0x2abffd0 VA: 0x75950d7fd0
	public String get_defaultUsageText() { }
	// RVA: 0x2ac1db0 VA: 0x75950d9db0
	public List`1 get_itemList() { }
	// RVA: 0x2ac1490 VA: 0x75950d9490
	public Void LoadData(String topicId, RoguelikeSacrificeModelParamBuilder builder) { }
	// RVA: 0x2ac16cc VA: 0x75950d96cc
	public Boolean SelectItem(String indexId) { }
	// RVA: 0x2ac2314 VA: 0x75950da314
	public Void .ctor() { }
}
```