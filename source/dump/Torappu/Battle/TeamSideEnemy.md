# TeamSideEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _hasSummonee`

- `SideTypeIndex m_teamSide`

- `BaseTraceTargetAbility m_enemyTraceEnemyAbility`

- `TracePositionCursor m_emptyCursor`

- `SideType m_oppositeSide`

- `Boolean m_hasTargetInRange`


## Properties

- `SideTypeIndex teamSide`

- `SideType oppositeSide`

- `Boolean hasTargetInRange`

- `Boolean hasSummoneeAfterDeath`

- `DirectionCursor emptyCursor`

- `BaseTraceTargetAbility enemyTraceEnemyAbility`


## Methods

- `SideTypeIndex get_teamSide()`

- `SideType get_oppositeSide()`

- `Boolean get_hasTargetInRange()`

- `Boolean get_hasSummoneeAfterDeath()`

- `DirectionCursor get_emptyCursor()`

- `BaseTraceTargetAbility get_enemyTraceEnemyAbility()`

- `Void set_enemyTraceEnemyAbility(BaseTraceTargetAbility)`

- `Void UpdateTargetInRange()`

- `Void _SetSideData()`

- `SideTypeIndex <>xLuaBaseProxy_get_sideTypeIndex()`

- `DirectionCursor <>xLuaBaseProxy_get_moveCursor()`

- `Boolean <>xLuaBaseProxy_get_usingTraceCursor()`

- `Entity <>xLuaBaseProxy_get_traceTarget()`

- `Void <>xLuaBaseProxy_Init(EnemyData, EnemyHandBookData, SchedulerSnapshot, Route)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TeamSideEnemy : Enemy
{
	private Boolean _hasSummonee; // 0x4b8
	private SideTypeIndex m_teamSide; // 0x4bc
	private BaseTraceTargetAbility m_enemyTraceEnemyAbility; // 0x4c0
	private TracePositionCursor m_emptyCursor; // 0x4c8
	private SideType m_oppositeSide; // 0x4d0
	private Boolean m_hasTargetInRange; // 0x4d4
	private static DelegateBridge __Hotfix0_get_teamSide; // 0x0
	private static DelegateBridge __Hotfix0_get_oppositeSide; // 0x8
	private static DelegateBridge __Hotfix0_get_hasTargetInRange; // 0x10
	private static DelegateBridge __Hotfix0_get_hasSummoneeAfterDeath; // 0x18
	private static DelegateBridge __Hotfix0_get_sideTypeIndex; // 0x20
	private static DelegateBridge __Hotfix0_get_emptyCursor; // 0x28
	private static DelegateBridge __Hotfix0_get_moveCursor; // 0x30
	private static DelegateBridge __Hotfix0_get_enemyTraceEnemyAbility; // 0x38
	private static DelegateBridge __Hotfix0_set_enemyTraceEnemyAbility; // 0x40
	private static DelegateBridge __Hotfix0_get_usingTraceCursor; // 0x48
	private static DelegateBridge __Hotfix0_get_traceTarget; // 0x50
	private static DelegateBridge __Hotfix0_UpdateTargetInRange; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x60
	private static DelegateBridge __Hotfix0_OnReset; // 0x68
	private static DelegateBridge __Hotfix0__SetSideData; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public SideTypeIndex teamSide { get; }
	public SideType oppositeSide { get; }
	public Boolean hasTargetInRange { get; }
	public Boolean hasSummoneeAfterDeath { get; }
	protected override SideTypeIndex sideTypeIndex { get; }
	private DirectionCursor emptyCursor { get; }
	public override DirectionCursor moveCursor { get; }
	public BaseTraceTargetAbility enemyTraceEnemyAbility { get; set; }
	public override Boolean usingTraceCursor { get; }
	public override Entity traceTarget { get; }

	// RVA: 0x1c28240 VA: 0x7594240240
	public SideTypeIndex get_teamSide() { }
	// RVA: 0x1c282a8 VA: 0x75942402a8
	public SideType get_oppositeSide() { }
	// RVA: 0x1c2832c VA: 0x759424032c
	public Boolean get_hasTargetInRange() { }
	// RVA: 0x1c28394 VA: 0x7594240394
	public Boolean get_hasSummoneeAfterDeath() { }
	// RVA: 0x1c283fc VA: 0x75942403fc
	protected override SideTypeIndex get_sideTypeIndex() { }
	// RVA: 0x1c28464 VA: 0x7594240464
	private DirectionCursor get_emptyCursor() { }
	// RVA: 0x1c285f8 VA: 0x75942405f8
	public override DirectionCursor get_moveCursor() { }
	// RVA: 0x1c286cc VA: 0x75942406cc
	public BaseTraceTargetAbility get_enemyTraceEnemyAbility() { }
	// RVA: 0x1c28734 VA: 0x7594240734
	public Void set_enemyTraceEnemyAbility(BaseTraceTargetAbility value) { }
	// RVA: 0x1c287b8 VA: 0x75942407b8
	public override Boolean get_usingTraceCursor() { }
	// RVA: 0x1c28890 VA: 0x7594240890
	public override Entity get_traceTarget() { }
	// RVA: 0x1c28968 VA: 0x7594240968
	public Void UpdateTargetInRange() { }
	// RVA: 0x1c294ac VA: 0x75942414ac
	protected override Void Init(EnemyData enemyData, EnemyHandBookData handbookData, SchedulerSnapshot snapshot, Route route) { }
	// RVA: 0x1c296ac VA: 0x75942416ac
	protected override Void OnReset() { }
	// RVA: 0x1c29588 VA: 0x7594241588
	private Void _SetSideData() { }
	// RVA: 0x1c29744 VA: 0x7594241744
	public Void .ctor() { }
	// RVA: 0x1c297e0 VA: 0x75942417e0
	private SideTypeIndex <>xLuaBaseProxy_get_sideTypeIndex() { }
	// RVA: 0x1c297e8 VA: 0x75942417e8
	private DirectionCursor <>xLuaBaseProxy_get_moveCursor() { }
	// RVA: 0x1c297f0 VA: 0x75942417f0
	private Boolean <>xLuaBaseProxy_get_usingTraceCursor() { }
	// RVA: 0x1c297f8 VA: 0x75942417f8
	private Entity <>xLuaBaseProxy_get_traceTarget() { }
	// RVA: 0x1c29800 VA: 0x7594241800
	private Void <>xLuaBaseProxy_Init(EnemyData P0, EnemyHandBookData P1, SchedulerSnapshot P2, Route P3) { }
	// RVA: 0x1c29830 VA: 0x7594241830
	private Void <>xLuaBaseProxy_OnReset() { }
}
```