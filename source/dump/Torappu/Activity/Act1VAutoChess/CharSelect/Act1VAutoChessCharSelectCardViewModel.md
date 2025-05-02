# Act1VAutoChessCharSelectCardViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `Int32 <localInstId>k__BackingField`

- `Act1VAutoChessShopCharChessCardViewModel chessModel`

- `ActivityAutoChessVerify1Data <activityData>k__BackingField`

- `Act1VAutoChessCharShopChessData <shopChessData>k__BackingField`

- `Act1VAutoChessCharChessStatusData <chessNormalStatusData>k__BackingField`

- `Act1VAutoChessCharChessStatusData <chessGoldenStatusData>k__BackingField`

- `Act1VAutoChessCharShopChessData <originChess>k__BackingField`

- `BasicCharInfoModel m_basicInfo`

- `String m_skillId`

- `Int32 m_skillIndex`

- `String m_equipId`

- `String m_skin`

- `CharQuery <charQuery>k__BackingField`

- `Int32 <potentialRank>k__BackingField`


## Properties

- `Int32 localInstId`

- `ActivityAutoChessVerify1Data activityData`

- `Act1VAutoChessCharShopChessData shopChessData`

- `Act1VAutoChessCharChessStatusData chessNormalStatusData`

- `Act1VAutoChessCharChessStatusData chessGoldenStatusData`

- `Act1VAutoChessCharShopChessData originChess`

- `CharQuery charQuery`

- `String skinId`

- `Int32 skillIndex`

- `String currentEquip`

- `Int32 potentialRank`

- `AutoChessCharType chessType`

- `Act1VAutoChessCharShopChessData originChessShopData`


## Methods

- `Int32 get_localInstId()`

- `Void set_localInstId(Int32)`

- `ActivityAutoChessVerify1Data get_activityData()`

- `Void set_activityData(ActivityAutoChessVerify1Data)`

- `Act1VAutoChessCharShopChessData get_shopChessData()`

- `Void set_shopChessData(Act1VAutoChessCharShopChessData)`

- `Act1VAutoChessCharChessStatusData get_chessNormalStatusData()`

- `Void set_chessNormalStatusData(Act1VAutoChessCharChessStatusData)`

- `Act1VAutoChessCharChessStatusData get_chessGoldenStatusData()`

- `Void set_chessGoldenStatusData(Act1VAutoChessCharChessStatusData)`

- `Act1VAutoChessCharShopChessData get_originChess()`

- `Void set_originChess(Act1VAutoChessCharShopChessData)`

- `Boolean Load(InitParam)`

- `Void _UpdateSkillIndex()`

- `CharQuery get_charQuery()`

- `Void set_charQuery(CharQuery)`

- `String get_skinId()`

- `Int32 get_skillIndex()`

- `String get_currentEquip()`

- `Int32 get_potentialRank()`

- `Void set_potentialRank(Int32)`

- `AutoChessCharType get_chessType()`

- `Act1VAutoChessCharShopChessData get_originChessShopData()`

- `Boolean LoadCharInfo()`

- `Void <>xLuaBaseProxy_OnSelectChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectCardViewModel : TemplateCharSelectCardViewModel, ICharInfo
{
	private Int32 <localInstId>k__BackingField; // 0x18
	public Act1VAutoChessShopCharChessCardViewModel chessModel; // 0x20
	private ActivityAutoChessVerify1Data <activityData>k__BackingField; // 0x28
	private Act1VAutoChessCharShopChessData <shopChessData>k__BackingField; // 0x30
	private Act1VAutoChessCharChessStatusData <chessNormalStatusData>k__BackingField; // 0x38
	private Act1VAutoChessCharChessStatusData <chessGoldenStatusData>k__BackingField; // 0x40
	private Act1VAutoChessCharShopChessData <originChess>k__BackingField; // 0x48
	private BasicCharInfoModel m_basicInfo; // 0x50
	private String m_skillId; // 0x58
	private Int32 m_skillIndex; // 0x60
	private String m_equipId; // 0x68
	private String m_skin; // 0x70
	private CharQuery <charQuery>k__BackingField; // 0x78
	private Int32 <potentialRank>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_localInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_localInstId; // 0x8
	private static DelegateBridge __Hotfix0_get_activityData; // 0x10
	private static DelegateBridge __Hotfix0_set_activityData; // 0x18
	private static DelegateBridge __Hotfix0_get_shopChessData; // 0x20
	private static DelegateBridge __Hotfix0_set_shopChessData; // 0x28
	private static DelegateBridge __Hotfix0_get_chessNormalStatusData; // 0x30
	private static DelegateBridge __Hotfix0_set_chessNormalStatusData; // 0x38
	private static DelegateBridge __Hotfix0_get_chessGoldenStatusData; // 0x40
	private static DelegateBridge __Hotfix0_set_chessGoldenStatusData; // 0x48
	private static DelegateBridge __Hotfix0_get_originChess; // 0x50
	private static DelegateBridge __Hotfix0_set_originChess; // 0x58
	private static DelegateBridge __Hotfix0_get_basicCharInfo; // 0x60
	private static DelegateBridge __Hotfix0_get_skillId; // 0x68
	private static DelegateBridge __Hotfix0_set_skillId; // 0x70
	private static DelegateBridge __Hotfix0_get_equipId; // 0x78
	private static DelegateBridge __Hotfix0_set_equipId; // 0x80
	private static DelegateBridge __Hotfix0_GetAttackRange; // 0x88
	private static DelegateBridge __Hotfix0_GetInstId; // 0x90
	private static DelegateBridge __Hotfix0_SynWithPlayerData; // 0x98
	private static DelegateBridge __Hotfix0_Load; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateSkillIndex; // 0xa8
	private static DelegateBridge __Hotfix0_OnSelectChanged; // 0xb0
	private static DelegateBridge __Hotfix0_get_charQuery; // 0xb8
	private static DelegateBridge __Hotfix0_set_charQuery; // 0xc0
	private static DelegateBridge __Hotfix0_get_skinId; // 0xc8
	private static DelegateBridge __Hotfix0_get_skillIndex; // 0xd0
	private static DelegateBridge __Hotfix0_get_currentEquip; // 0xd8
	private static DelegateBridge __Hotfix0_get_potentialRank; // 0xe0
	private static DelegateBridge __Hotfix0_set_potentialRank; // 0xe8
	private static DelegateBridge __Hotfix0_get_chessType; // 0xf0
	private static DelegateBridge __Hotfix0_get_originChessShopData; // 0xf8
	private static DelegateBridge __Hotfix0_LoadCharInfo; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public Int32 localInstId { get; set; }
	public ActivityAutoChessVerify1Data activityData { get; set; }
	public Act1VAutoChessCharShopChessData shopChessData { get; set; }
	public Act1VAutoChessCharChessStatusData chessNormalStatusData { get; set; }
	public Act1VAutoChessCharChessStatusData chessGoldenStatusData { get; set; }
	public Act1VAutoChessCharShopChessData originChess { get; set; }
	public override BasicCharInfoModel basicCharInfo { get; }
	public override String skillId { get; set; }
	public override String equipId { get; set; }
	public CharQuery charQuery { get; set; }
	public String skinId { get; }
	public Int32 skillIndex { get; }
	public String currentEquip { get; }
	public Int32 potentialRank { get; set; }
	public AutoChessCharType chessType { get; }
	public Act1VAutoChessCharShopChessData originChessShopData { get; }

	// RVA: 0x3385130 VA: 0x759599d130
	public Int32 get_localInstId() { }
	// RVA: 0x3385198 VA: 0x759599d198
	public Void set_localInstId(Int32 value) { }
	// RVA: 0x3385214 VA: 0x759599d214
	public ActivityAutoChessVerify1Data get_activityData() { }
	// RVA: 0x338527c VA: 0x759599d27c
	private Void set_activityData(ActivityAutoChessVerify1Data value) { }
	// RVA: 0x3385300 VA: 0x759599d300
	public Act1VAutoChessCharShopChessData get_shopChessData() { }
	// RVA: 0x3385368 VA: 0x759599d368
	private Void set_shopChessData(Act1VAutoChessCharShopChessData value) { }
	// RVA: 0x33853ec VA: 0x759599d3ec
	public Act1VAutoChessCharChessStatusData get_chessNormalStatusData() { }
	// RVA: 0x3385454 VA: 0x759599d454
	private Void set_chessNormalStatusData(Act1VAutoChessCharChessStatusData value) { }
	// RVA: 0x33854d8 VA: 0x759599d4d8
	public Act1VAutoChessCharChessStatusData get_chessGoldenStatusData() { }
	// RVA: 0x3385540 VA: 0x759599d540
	private Void set_chessGoldenStatusData(Act1VAutoChessCharChessStatusData value) { }
	// RVA: 0x33855c4 VA: 0x759599d5c4
	public Act1VAutoChessCharShopChessData get_originChess() { }
	// RVA: 0x338562c VA: 0x759599d62c
	private Void set_originChess(Act1VAutoChessCharShopChessData value) { }
	// RVA: 0x33856b0 VA: 0x759599d6b0
	public override BasicCharInfoModel get_basicCharInfo() { }
	// RVA: 0x3385718 VA: 0x759599d718
	public override String get_skillId() { }
	// RVA: 0x3385780 VA: 0x759599d780
	public override Void set_skillId(String value) { }
	// RVA: 0x3385a10 VA: 0x759599da10
	public override String get_equipId() { }
	// RVA: 0x3385a78 VA: 0x759599da78
	public override Void set_equipId(String value) { }
	// RVA: 0x3385b3c VA: 0x759599db3c
	public override AttackRangeDescModel GetAttackRange() { }
	// RVA: 0x3385bcc VA: 0x759599dbcc
	public override Int32 GetInstId() { }
	// RVA: 0x3385c34 VA: 0x759599dc34
	public override Void SynWithPlayerData() { }
	// RVA: 0x3385c98 VA: 0x759599dc98
	public Boolean Load(InitParam initParam) { }
	// RVA: 0x338584c VA: 0x759599d84c
	private Void _UpdateSkillIndex() { }
	// RVA: 0x33865f4 VA: 0x759599e5f4
	protected override Void OnSelectChanged(Boolean sel) { }
	// RVA: 0x33864fc VA: 0x759599e4fc
	public CharQuery get_charQuery() { }
	// RVA: 0x33863d0 VA: 0x759599e3d0
	private Void set_charQuery(CharQuery value) { }
	// RVA: 0x3386680 VA: 0x759599e680
	public String get_skinId() { }
	// RVA: 0x33866e8 VA: 0x759599e6e8
	public Int32 get_skillIndex() { }
	// RVA: 0x3386750 VA: 0x759599e750
	public String get_currentEquip() { }
	// RVA: 0x338658c VA: 0x759599e58c
	public Int32 get_potentialRank() { }
	// RVA: 0x3386480 VA: 0x759599e480
	private Void set_potentialRank(Int32 value) { }
	// RVA: 0x33867b8 VA: 0x759599e7b8
	public AutoChessCharType get_chessType() { }
	// RVA: 0x3386830 VA: 0x759599e830
	public Act1VAutoChessCharShopChessData get_originChessShopData() { }
	// RVA: 0x3386898 VA: 0x759599e898
	public Boolean LoadCharInfo() { }
	// RVA: 0x3386900 VA: 0x759599e900
	public Void .ctor() { }
	// RVA: 0x33869f8 VA: 0x759599e9f8
	private Void <>xLuaBaseProxy_OnSelectChanged(Boolean P0) { }
}
```