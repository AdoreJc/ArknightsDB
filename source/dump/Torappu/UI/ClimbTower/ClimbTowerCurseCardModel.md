# ClimbTowerCurseCardModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerCurseCardData m_curseCardData`

- `Sprite m_iconSprite`


## Properties

- `String cardName`

- `String cardDesc`

- `Sprite iconSprite`


## Methods

- `String get_cardName()`

- `String get_cardDesc()`

- `Sprite get_iconSprite()`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerCurseCardModel : IHotfixable
{
	private ClimbTowerCurseCardData m_curseCardData; // 0x10
	private Sprite m_iconSprite; // 0x18
	private static DelegateBridge __Hotfix0_get_cardName; // 0x0
	private static DelegateBridge __Hotfix0_get_cardDesc; // 0x8
	private static DelegateBridge __Hotfix0_get_iconSprite; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String cardName { get; }
	public String cardDesc { get; }
	public Sprite iconSprite { get; }

	// RVA: 0x2ca80e0 VA: 0x75952c00e0
	public String get_cardName() { }
	// RVA: 0x2ca8174 VA: 0x75952c0174
	public String get_cardDesc() { }
	// RVA: 0x2ca8208 VA: 0x75952c0208
	public Sprite get_iconSprite() { }
	// RVA: 0x2ca8270 VA: 0x75952c0270
	public Void LoadData(String curseCardId) { }
	// RVA: 0x2ca8398 VA: 0x75952c0398
	public Void .ctor() { }
}
```