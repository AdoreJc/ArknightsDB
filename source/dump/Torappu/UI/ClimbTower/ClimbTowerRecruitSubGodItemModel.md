# ClimbTowerRecruitSubGodItemModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSubCardData m_subCardData`

- `Sprite m_cardSprite`


## Properties

- `String cardId`

- `String cardName`

- `String cardDesc`

- `Sprite cardSprite`


## Methods

- `String get_cardId()`

- `String get_cardName()`

- `String get_cardDesc()`

- `Sprite get_cardSprite()`

- `Void LoadData(UIPage, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRecruitSubGodItemModel : IHotfixable
{
	private ClimbTowerSubCardData m_subCardData; // 0x10
	private Sprite m_cardSprite; // 0x18
	private static DelegateBridge __Hotfix0_get_cardId; // 0x0
	private static DelegateBridge __Hotfix0_get_cardName; // 0x8
	private static DelegateBridge __Hotfix0_get_cardDesc; // 0x10
	private static DelegateBridge __Hotfix0_get_cardSprite; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String cardId { get; }
	public String cardName { get; }
	public String cardDesc { get; }
	public Sprite cardSprite { get; }

	// RVA: 0x2cac864 VA: 0x75952c4864
	public String get_cardId() { }
	// RVA: 0x2cac600 VA: 0x75952c4600
	public String get_cardName() { }
	// RVA: 0x2cac694 VA: 0x75952c4694
	public String get_cardDesc() { }
	// RVA: 0x2cac728 VA: 0x75952c4728
	public Sprite get_cardSprite() { }
	// RVA: 0x2cadb94 VA: 0x75952c5b94
	public Void LoadData(UIPage page, String subCardId) { }
	// RVA: 0x2cadcb8 VA: 0x75952c5cb8
	public Void .ctor() { }
}
```