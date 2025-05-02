# ClimbTowerEntryGodCardModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String id`

- `String name`

- `ClimbTowerCardType cardType`

- `String bindTowerName`

- `Int32 sortId`

- `String desc`

- `Boolean isNew`

- `Boolean isComplete`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryGodCardModel : IHotfixable, IComparable
{
	public String id; // 0x10
	public String name; // 0x18
	public ClimbTowerCardType cardType; // 0x20
	public String bindTowerName; // 0x28
	public Int32 sortId; // 0x30
	public String desc; // 0x38
	public Boolean isNew; // 0x40
	public Boolean isComplete; // 0x41
	public List`1 towerStatus; // 0x48
	public List`1 subCardList; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2cd59c4 VA: 0x75952ed9c4
	public static ClimbTowerEntryGodCardModel LoadData(String cardId, String seasonId) { }
	// RVA: 0x2cd68e0 VA: 0x75952ee8e0
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2cd6a4c VA: 0x75952eea4c
	public Void .ctor() { }
}
```