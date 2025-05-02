# Act1VAutoChessFriendAssistPlugin

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <activityId>k__BackingField`

- `CharQuery <charQuery>k__BackingField`

- `String <chessId>k__BackingField`


## Properties

- `String activityId`

- `CharQuery charQuery`

- `String chessId`

- `String tips`

- `Boolean profValid`


## Methods

- `String get_activityId()`

- `Void set_activityId(String)`

- `CharQuery get_charQuery()`

- `Void set_charQuery(CharQuery)`

- `String get_chessId()`

- `Void set_chessId(String)`

- `String get_tips()`

- `Boolean get_profValid()`

- `Void ApplyAssistChoose(SquadAssistData, Action)`

- `Void FetchAssistData(ProfessionCategory, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessFriendAssistPlugin : ICommonFriendAssistPlugin
{
	private String <activityId>k__BackingField; // 0x10
	private CharQuery <charQuery>k__BackingField; // 0x18
	private String <chessId>k__BackingField; // 0x30

	public String activityId { get; set; }
	public CharQuery charQuery { get; set; }
	public String chessId { get; set; }
	public String tips { get; }
	public Boolean profValid { get; }

	// RVA: 0x3312740 VA: 0x759592a740
	public String get_activityId() { }
	// RVA: 0x3312748 VA: 0x759592a748
	public Void set_activityId(String value) { }
	// RVA: 0x3312750 VA: 0x759592a750
	public CharQuery get_charQuery() { }
	// RVA: 0x3312764 VA: 0x759592a764
	public Void set_charQuery(CharQuery value) { }
	// RVA: 0x3312784 VA: 0x759592a784
	public String get_chessId() { }
	// RVA: 0x331278c VA: 0x759592a78c
	public Void set_chessId(String value) { }
	// RVA: 0x3312794 VA: 0x759592a794
	public String get_tips() { }
	// RVA: 0x33127e4 VA: 0x759592a7e4
	public Boolean get_profValid() { }
	// RVA: 0x33127ec VA: 0x759592a7ec
	public Void ApplyAssistChoose(SquadAssistData assist, Action done) { }
	// RVA: 0x3312a14 VA: 0x759592aa14
	public Void FetchAssistData(ProfessionCategory profession, Action`1 result) { }
	// RVA: 0x330d1a8 VA: 0x75959251a8
	public Void .ctor() { }
}
```