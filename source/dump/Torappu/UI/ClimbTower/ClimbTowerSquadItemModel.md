# ClimbTowerSquadItemModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `CharacterCardViewModel m_cardModel`

- `String m_defaultEquipId`

- `TowerCardType m_cardType`

- `Int32 m_cardId`

- `Sprite m_charMarkSprite`


## Properties

- `CharacterCardViewModel cardModel`

- `Int32 cardId`

- `TowerCardType cardType`

- `Sprite charMarkSprite`


## Methods

- `CharacterCardViewModel get_cardModel()`

- `Int32 get_cardId()`

- `TowerCardType get_cardType()`

- `Sprite get_charMarkSprite()`

- `Int32 _GetCurSkillIndex()`

- `Void LoadData(UIPage, GameCard, ClimbTowerCharEditCacheModel)`

- `Void _LoadCharMarkSprite(UIPage)`

- `Void LoadDataFromPredefined(CharacterCardViewModel)`

- `Void UpdateEditInfo(ClimbTowerCharEditCacheModel)`

- `Int32 ExtraTmplCount()`

- `String GetDefaultEquipId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadItemModel : ISquadMemberCompInfo, IHotfixable
{
	private CharacterCardViewModel m_cardModel; // 0x10
	private String m_defaultEquipId; // 0x18
	private TowerCardType m_cardType; // 0x20
	private Int32 m_cardId; // 0x24
	private Sprite m_charMarkSprite; // 0x28
	private static DelegateBridge __Hotfix0_get_cardModel; // 0x0
	private static DelegateBridge __Hotfix0_get_cardId; // 0x8
	private static DelegateBridge __Hotfix0_get_cardType; // 0x10
	private static DelegateBridge __Hotfix0_get_charMarkSprite; // 0x18
	private static DelegateBridge __Hotfix0__GetCurSkillIndex; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0__LoadCharMarkSprite; // 0x30
	private static DelegateBridge __Hotfix0_LoadDataFromPredefined; // 0x38
	private static DelegateBridge __Hotfix0_UpdateEditInfo; // 0x40
	private static DelegateBridge __Hotfix0_ExtraTmplCount; // 0x48
	private static DelegateBridge __Hotfix0_ExtraTmplInfo; // 0x50
	private static DelegateBridge __Hotfix0_GetDefaultEquipId; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public CharacterCardViewModel cardModel { get; }
	public Int32 cardId { get; }
	public TowerCardType cardType { get; }
	public Sprite charMarkSprite { get; }

	// RVA: 0x2cb9338 VA: 0x75952d1338
	public CharacterCardViewModel get_cardModel() { }
	// RVA: 0x2cbf838 VA: 0x75952d7838
	public Int32 get_cardId() { }
	// RVA: 0x2cc0328 VA: 0x75952d8328
	public TowerCardType get_cardType() { }
	// RVA: 0x2cc0390 VA: 0x75952d8390
	public Sprite get_charMarkSprite() { }
	// RVA: 0x2cc03f8 VA: 0x75952d83f8
	private Int32 _GetCurSkillIndex() { }
	// RVA: 0x2cbf9b8 VA: 0x75952d79b8
	public Void LoadData(UIPage page, GameCard playerCard, ClimbTowerCharEditCacheModel editModel) { }
	// RVA: 0x2cc0510 VA: 0x75952d8510
	private Void _LoadCharMarkSprite(UIPage page) { }
	// RVA: 0x2cbf910 VA: 0x75952d7910
	public Void LoadDataFromPredefined(CharacterCardViewModel charModel) { }
	// RVA: 0x2cc0120 VA: 0x75952d8120
	public Void UpdateEditInfo(ClimbTowerCharEditCacheModel editModel) { }
	// RVA: 0x2cc06dc VA: 0x75952d86dc
	public Int32 ExtraTmplCount() { }
	// RVA: 0x2cc0764 VA: 0x75952d8764
	public IEnumerator`1 ExtraTmplInfo() { }
	// RVA: 0x2cc0838 VA: 0x75952d8838
	public String GetDefaultEquipId() { }
	// RVA: 0x2cbf8a0 VA: 0x75952d78a0
	public Void .ctor() { }
}
```