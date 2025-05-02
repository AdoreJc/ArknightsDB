# UICharacterInfoStatusSubPanelInAutochess

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _costLabel`

- `Image _chessLvlIcon`

- `Image _basicCampIcon`

- `Text _basicCampText`


## Properties

- `AutoChessDataCenter center`


## Methods

- `AutoChessDataCenter get_center()`

- `Int32 _GetChessIconLevel(Character)`

- `Int32 _GetShopChessIconLevel(Character, GridPosition)`

- `Int32 _GetBattleOrHandChessIconLevel(GridPosition)`

- `Void _SetCampIcon(String, String, Image, Text)`

- `Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel)`

- `Void <>xLuaBaseProxy_SetData(ObjectPtr`1, ModeType, Card)`

- `Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1, ModeType, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterInfoStatusSubPanelInAutochess : UICharacterInfoStatusSubPanel
{
	private Text _costLabel; // 0xb0
	private Image _chessLvlIcon; // 0xb8
	private Image _basicCampIcon; // 0xc0
	private Text _basicCampText; // 0xc8
	private Image[] _extraCampIcons; // 0xd0
	private Text[] _extraCampTexts; // 0xd8
	private Sprite[] _chessLevelSprites; // 0xe0
	private List`1 m_extraFactionIds; // 0xe8
	private static DelegateBridge __Hotfix0_get_center; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge __Hotfix0__GetChessIconLevel; // 0x20
	private static DelegateBridge __Hotfix0__GetShopChessIconLevel; // 0x28
	private static DelegateBridge __Hotfix0__GetBattleOrHandChessIconLevel; // 0x30
	private static DelegateBridge __Hotfix0__SetCampIcon; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private AutoChessDataCenter center { get; }

	// RVA: 0x2036bb0 VA: 0x759464ebb0
	private AutoChessDataCenter get_center() { }
	// RVA: 0x2036c2c VA: 0x759464ec2c
	public override Void OnInit(UICharacterInfoPanel parent) { }
	// RVA: 0x2036e40 VA: 0x759464ee40
	public override Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2037754 VA: 0x759464f754
	public override Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x203753c VA: 0x759464f53c
	private Int32 _GetChessIconLevel(Character character) { }
	// RVA: 0x2037b14 VA: 0x759464fb14
	private Int32 _GetShopChessIconLevel(Character character, GridPosition pos) { }
	// RVA: 0x2037c8c VA: 0x759464fc8c
	private Int32 _GetBattleOrHandChessIconLevel(GridPosition pos) { }
	// RVA: 0x203762c VA: 0x759464f62c
	private Void _SetCampIcon(String factionId, String factionName, Image image, Text text) { }
	// RVA: 0x2037dd8 VA: 0x759464fdd8
	public Void .ctor() { }
	// RVA: 0x2037e98 VA: 0x759464fe98
	private Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel P0) { }
	// RVA: 0x2037e9c VA: 0x759464fe9c
	private Void <>xLuaBaseProxy_SetData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
	// RVA: 0x2037ea0 VA: 0x759464fea0
	private Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
}
```