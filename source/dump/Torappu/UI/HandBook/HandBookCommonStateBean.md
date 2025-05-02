# HandBookCommonStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookLineGroup m_relationViewModel`

- `HandBookScrollViewProperty scrollViewModel`

- `HandBookCardDB _handbookCardDBComponent`

- `HandBookLineDB _handbookLineDBComponent`

- `HandBookTeamIconDB _handbookTeamDBComonent`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Start()`

- `Sprite GetSprite(String)`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookCommonStateBean : PageComponent, IStateBean, IHotfixable, IDataBindWrapper
{
	public Dictionary`2 cardList; // 0x20
	private HandBookLineGroup m_relationViewModel; // 0x28
	public HandBookScrollViewProperty scrollViewModel; // 0x30
	private HandBookCardDB _handbookCardDBComponent; // 0x38
	private HandBookLineDB _handbookLineDBComponent; // 0x40
	private HandBookTeamIconDB _handbookTeamDBComonent; // 0x48
	public Dictionary`2 friendshipTeamData; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0_get_lineData; // 0x0
	private static DelegateBridge __Hotfix0_get_cardDatas; // 0x8
	private static DelegateBridge __Hotfix0_get_teamDatas; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_GetSprite; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Dictionary`2 lineData { get; }
	public Dictionary`2 cardDatas { get; }
	public Dictionary`2 teamDatas { get; }

	// RVA: 0x2eb4b80 VA: 0x75954ccb80
	public Dictionary`2 get_lineData() { }
	// RVA: 0x2eb4998 VA: 0x75954cc998
	public Dictionary`2 get_cardDatas() { }
	// RVA: 0x2eb4470 VA: 0x75954cc470
	public Dictionary`2 get_teamDatas() { }
	// RVA: 0x2eb88e8 VA: 0x75954d08e8
	private Void _InitIfNot() { }
	// RVA: 0x2eb895c VA: 0x75954d095c
	protected Void Start() { }
	// RVA: 0x2eb44f8 VA: 0x75954cc4f8
	public Sprite GetSprite(String powerId) { }
	// RVA: 0x2eb89c4 VA: 0x75954d09c4
	public Void LoadData() { }
	// RVA: 0x2eba868 VA: 0x75954d2868
	public Void .ctor() { }
}
```