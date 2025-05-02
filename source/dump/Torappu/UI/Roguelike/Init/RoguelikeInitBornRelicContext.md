# RoguelikeInitBornRelicContext

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `RoguelikeTopicMode m_preMode`

- `String m_prePredefinedId`

- `String m_preTheme`


## Methods

- `Void _AddRelic(String, RoguelikeTopicItemModel, Int32, Boolean, List`1, Int32)`

- `Boolean _CheckIsRogueGameActivityHideEnding()`

- `Void _FindAllBornRelic()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitBornRelicContext : RoguelikeInitOptionContext
{
	private List`1 m_list; // 0x28
	private List`1 m_relics; // 0x30
	private List`1 m_allBornRelic; // 0x38
	private RoguelikeTopicMode m_preMode; // 0x40
	private String m_prePredefinedId; // 0x48
	private String m_preTheme; // 0x50
	private static DelegateBridge __Hotfix0_get_list; // 0x0
	private static DelegateBridge __Hotfix0_get_name; // 0x8
	private static DelegateBridge __Hotfix0_Load; // 0x10
	private static DelegateBridge __Hotfix0__AddRelic; // 0x18
	private static DelegateBridge __Hotfix0__GetEndings; // 0x20
	private static DelegateBridge __Hotfix0__CheckIsRogueGameActivityHideEnding; // 0x28
	private static DelegateBridge __Hotfix0__GetEndingFromBandCnt; // 0x30
	private static DelegateBridge __Hotfix0__GetEndingFromBandGrade; // 0x38
	private static DelegateBridge __Hotfix0__FindAllBornRelic; // 0x40
	private static DelegateBridge __Hotfix0_OnSelect; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override List`1 list { get; }
	public override String name { get; }

	// RVA: 0x2b7cd54 VA: 0x7595194d54
	public override List`1 get_list() { }
	// RVA: 0x2b7cdbc VA: 0x7595194dbc
	public override String get_name() { }
	// RVA: 0x2b7ce48 VA: 0x7595194e48
	public override Void Load(PlayerRoguelikePendingEvent evt) { }
	// RVA: 0x2b7e080 VA: 0x7595196080
	private Void _AddRelic(String index, RoguelikeTopicItemModel itemData, Int32 count, Boolean isLocked, List`1 endings, Int32 level) { }
	// RVA: 0x2b7defc VA: 0x7595195efc
	private List`1 _GetEndings(String bandGrpId, OuterData outerData, List`1 allEndings, Boolean showGrade) { }
	// RVA: 0x2b7e60c VA: 0x759519660c
	private Boolean _CheckIsRogueGameActivityHideEnding() { }
	// RVA: 0x2b7ec2c VA: 0x7595196c2c
	private List`1 _GetEndingFromBandCnt(String bandGrpId, OuterData outerData, List`1 allEndings) { }
	// RVA: 0x2b7e6f8 VA: 0x75951966f8
	private List`1 _GetEndingFromBandGrade(String bandGrpId, OuterData outerData, List`1 allEndings) { }
	// RVA: 0x2b7dc24 VA: 0x7595195c24
	private Void _FindAllBornRelic() { }
	// RVA: 0x2b7efec VA: 0x7595196fec
	public override Void OnSelect(Int32 idx) { }
	// RVA: 0x2b7f474 VA: 0x7595197474
	public Void .ctor() { }
}
```