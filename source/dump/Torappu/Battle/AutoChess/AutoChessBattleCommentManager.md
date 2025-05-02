# AutoChessBattleCommentManager

**Namespace:** `Torappu.Battle.AutoChess`


## Fields

- `CommentContext m_context`


## Methods

- `Void _RegisterCommentClasses()`

- `Void _Register(String)`

- `Void Init(List`1)`

- `Void Reset()`

- `Void ReportUnitBorn(Unit)`

- `Void ReportUnitFinished(UInt32, Unit, FinishReason)`

- `Void OnTick(FP)`

- `Boolean _TryRecordCharKillCntInternal(UInt32, Enemy, FinishReason)`

- `Void _CheckRepoters(CommentType, CommentContext)`

- `Void _BattleStatsLog(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.AutoChess
public class AutoChessBattleCommentManager : IHotfixable
{
	private Dictionary`2 m_commentClasses; // 0x10
	private List`1 m_commentReporter; // 0x18
	private Dictionary`2 m_characterKillCountDict; // 0x20
	private CommentContext m_context; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_characterKillCountDict; // 0x8
	private static DelegateBridge __Hotfix0__RegisterCommentClasses; // 0x10
	private static DelegateBridge __Hotfix0__Register; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0_ReportUnitBorn; // 0x30
	private static DelegateBridge __Hotfix0_ReportUnitFinished; // 0x38
	private static DelegateBridge __Hotfix0_OnTick; // 0x40
	private static DelegateBridge __Hotfix0__TryRecordCharKillCntInternal; // 0x48
	private static DelegateBridge __Hotfix0__CheckRepoters; // 0x50
	private static DelegateBridge __Hotfix0__BattleStatsLog; // 0x58

	public Dictionary`2 characterKillCountDict { get; }

	// RVA: 0x1c660d0 VA: 0x759427e0d0
	public Void .ctor() { }
	// RVA: 0x1c66490 VA: 0x759427e490
	public Dictionary`2 get_characterKillCountDict() { }
	// RVA: 0x1c66278 VA: 0x759427e278
	private Void _RegisterCommentClasses() { }
	// RVA: 0x VA: 0x0
	private Void _Register(String key) { }
	// RVA: 0x1c664f8 VA: 0x759427e4f8
	public Void Init(List`1 dataList) { }
	// RVA: 0x1c66750 VA: 0x759427e750
	public Void Reset() { }
	// RVA: 0x1c66868 VA: 0x759427e868
	public Void ReportUnitBorn(Unit unit) { }
	// RVA: 0x1c66a54 VA: 0x759427ea54
	public Void ReportUnitFinished(UInt32 cardUid, Unit unit, FinishReason finishReason) { }
	// RVA: 0x1c66fa0 VA: 0x759427efa0
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x1c66be0 VA: 0x759427ebe0
	private Boolean _TryRecordCharKillCntInternal(UInt32 cardUid, Enemy enemy, FinishReason finishReason) { }
	// RVA: 0x1c66914 VA: 0x759427e914
	private Void _CheckRepoters(CommentType type, CommentContext context) { }
	// RVA: 0x1c67024 VA: 0x759427f024
	private Void _BattleStatsLog(String message) { }
}
```