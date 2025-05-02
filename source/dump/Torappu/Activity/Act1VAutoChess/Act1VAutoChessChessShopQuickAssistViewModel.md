# Act1VAutoChessChessShopQuickAssistViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <activityId>k__BackingField`

- `Int32 <curAssistCnt>k__BackingField`

- `Int32 <maxCanAssistCnt>k__BackingField`

- `ActivityAutoChessVerify1Data m_cachedActData`

- `Int32 m_enterSequenceNum`


## Properties

- `String activityId`

- `Int32 enterSequenceNum`

- `Int32 curAssistCnt`

- `Int32 maxCanAssistCnt`


## Methods

- `String get_activityId()`

- `Void set_activityId(String)`

- `Int32 get_enterSequenceNum()`

- `Int32 get_curAssistCnt()`

- `Void set_curAssistCnt(Int32)`

- `Int32 get_maxCanAssistCnt()`

- `Void set_maxCanAssistCnt(Int32)`

- `Void LoadData(String)`

- `Void RefreshAssistInfoByPlayerData(String)`

- `Boolean IsChessAssistInfoChanged()`

- `Void _LoadDisplayLevelItemsData(Act1VAutoChessShopLevelDisplayData, Boolean, ListDict`2, ActivityAutoChessVerify1Data, Dictionary`2)`

- `Boolean _RefreshChessAssistInfoDictByPlayerData(Dictionary`2)`

- `Act1VAutoChessShopCharChessCardViewModel _CreateCharChessCardViewModel(String, ListDict`2, ActivityAutoChessVerify1Data, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopQuickAssistViewModel : IHotfixable
{
	private String <activityId>k__BackingField; // 0x10
	private Int32 <curAssistCnt>k__BackingField; // 0x18
	private Int32 <maxCanAssistCnt>k__BackingField; // 0x1c
	private List`1 m_assistItemsViewList; // 0x20
	private ListDict`2 m_cachedChessAssistInfoListDict; // 0x28
	private ListDict`2 m_cachedChessAssistInfoInitListDict; // 0x30
	private ActivityAutoChessVerify1Data m_cachedActData; // 0x38
	private Int32 m_enterSequenceNum; // 0x40
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_set_activityId; // 0x8
	private static DelegateBridge __Hotfix0_get_assistItemsViewList; // 0x10
	private static DelegateBridge __Hotfix0_get_enterSequenceNum; // 0x18
	private static DelegateBridge __Hotfix0_get_cachedChessAssistInfoListDict; // 0x20
	private static DelegateBridge __Hotfix0_get_curAssistCnt; // 0x28
	private static DelegateBridge __Hotfix0_set_curAssistCnt; // 0x30
	private static DelegateBridge __Hotfix0_get_maxCanAssistCnt; // 0x38
	private static DelegateBridge __Hotfix0_set_maxCanAssistCnt; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_RefreshAssistInfoByPlayerData; // 0x50
	private static DelegateBridge __Hotfix0_IsChessAssistInfoChanged; // 0x58
	private static DelegateBridge __Hotfix0__LoadDisplayLevelItemsData; // 0x60
	private static DelegateBridge __Hotfix0__RefreshChessAssistInfoDictByPlayerData; // 0x68
	private static DelegateBridge __Hotfix0__CreateCharChessCardViewModel; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String activityId { get; set; }
	public List`1 assistItemsViewList { get; }
	public Int32 enterSequenceNum { get; }
	public ListDict`2 cachedChessAssistInfoListDict { get; }
	public Int32 curAssistCnt { get; set; }
	public Int32 maxCanAssistCnt { get; set; }

	// RVA: 0x3326ce4 VA: 0x759593ece4
	public String get_activityId() { }
	// RVA: 0x3326d4c VA: 0x759593ed4c
	private Void set_activityId(String value) { }
	// RVA: 0x332175c VA: 0x759593975c
	public List`1 get_assistItemsViewList() { }
	// RVA: 0x33203b4 VA: 0x75959383b4
	public Int32 get_enterSequenceNum() { }
	// RVA: 0x3326dd0 VA: 0x759593edd0
	public ListDict`2 get_cachedChessAssistInfoListDict() { }
	// RVA: 0x33202e4 VA: 0x75959382e4
	public Int32 get_curAssistCnt() { }
	// RVA: 0x3326e38 VA: 0x759593ee38
	private Void set_curAssistCnt(Int32 value) { }
	// RVA: 0x332034c VA: 0x759593834c
	public Int32 get_maxCanAssistCnt() { }
	// RVA: 0x3326eb4 VA: 0x759593eeb4
	private Void set_maxCanAssistCnt(Int32 value) { }
	// RVA: 0x3326f30 VA: 0x759593ef30
	public Void LoadData(String actId) { }
	// RVA: 0x3327b88 VA: 0x759593fb88
	public Void RefreshAssistInfoByPlayerData(String chessId) { }
	// RVA: 0x3328188 VA: 0x7595940188
	public Boolean IsChessAssistInfoChanged() { }
	// RVA: 0x33277b4 VA: 0x759593f7b4
	private Void _LoadDisplayLevelItemsData(Act1VAutoChessShopLevelDisplayData shopLevelData, Boolean canAssistMore, ListDict`2 showingAssistChessIdDict, ActivityAutoChessVerify1Data actData, Dictionary`2 chessPlayerDataPool) { }
	// RVA: 0x33274f4 VA: 0x759593f4f4
	private Boolean _RefreshChessAssistInfoDictByPlayerData(Dictionary`2 chessPool) { }
	// RVA: 0x3327e18 VA: 0x759593fe18
	private Act1VAutoChessShopCharChessCardViewModel _CreateCharChessCardViewModel(String chessId, ListDict`2 showingAssistChessIdDict, ActivityAutoChessVerify1Data actData, Dictionary`2 chessPlayerDataPool) { }
	// RVA: 0x332847c VA: 0x759594047c
	public Void .ctor() { }
}
```