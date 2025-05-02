# ClimbTowerInitGodCardModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerMainCardData m_godCardData`

- `ClimbTowerSingleTowerData m_towerData`

- `Sprite m_iconSprite`

- `String m_seasonId`


## Properties

- `Boolean hasRelatedTower`

- `Sprite iconSprite`

- `String relatedTowerName`

- `String cardId`

- `Int32 sortId`

- `String cardName`

- `String cardDesc`


## Methods

- `Boolean get_hasRelatedTower()`

- `Sprite get_iconSprite()`

- `String get_relatedTowerName()`

- `String get_cardId()`

- `Int32 get_sortId()`

- `String get_cardName()`

- `String get_cardDesc()`

- `Void Init(UIPage, String)`

- `Void _TryGetRelatedTowerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitGodCardModel : IHotfixable
{
	private ClimbTowerMainCardData m_godCardData; // 0x10
	private ClimbTowerSingleTowerData m_towerData; // 0x18
	private Sprite m_iconSprite; // 0x20
	private String m_seasonId; // 0x28
	private static DelegateBridge __Hotfix0_get_hasRelatedTower; // 0x0
	private static DelegateBridge __Hotfix0_get_iconSprite; // 0x8
	private static DelegateBridge __Hotfix0_get_relatedTowerName; // 0x10
	private static DelegateBridge __Hotfix0_get_cardId; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_get_cardName; // 0x28
	private static DelegateBridge __Hotfix0_get_cardDesc; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x38
	private static DelegateBridge __Hotfix0__TryGetRelatedTowerData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean hasRelatedTower { get; }
	public Sprite iconSprite { get; }
	public String relatedTowerName { get; }
	public String cardId { get; }
	public Int32 sortId { get; }
	public String cardName { get; }
	public String cardDesc { get; }

	// RVA: 0x2caad64 VA: 0x75952c2d64
	public Boolean get_hasRelatedTower() { }
	// RVA: 0x2caadd4 VA: 0x75952c2dd4
	public Sprite get_iconSprite() { }
	// RVA: 0x2caae3c VA: 0x75952c2e3c
	public String get_relatedTowerName() { }
	// RVA: 0x2caa428 VA: 0x75952c2428
	public String get_cardId() { }
	// RVA: 0x2caaed0 VA: 0x75952c2ed0
	public Int32 get_sortId() { }
	// RVA: 0x2caaf48 VA: 0x75952c2f48
	public String get_cardName() { }
	// RVA: 0x2caafdc VA: 0x75952c2fdc
	public String get_cardDesc() { }
	// RVA: 0x2cab070 VA: 0x75952c3070
	public Void Init(UIPage page, String cardId) { }
	// RVA: 0x2cab290 VA: 0x75952c3290
	private Void _TryGetRelatedTowerData() { }
	// RVA: 0x2cab38c VA: 0x75952c338c
	public Void .ctor() { }
}
```