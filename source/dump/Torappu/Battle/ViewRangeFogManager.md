# ViewRangeFogManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _toLight`

- `String _toHidden`

- `String _toHasViewed`

- `String _toNotViewed`

- `Color _startColor`

- `String _remainOnFinishRange`

- `Single _remainOnFinishTime`

- `FogEdgeEffectHolder m_fogEdgeEffect`

- `RemainingTileTicker m_remainingTileTicker`

- `RangeTileViewHolder m_rangeTileViewHolder`

- `String m_extraViewRange`

- `Single m_remainOnFinishTime`

- `String m_forceViewRange`


## Methods

- `Void _OnUnitBorn(Object)`

- `Void _OnUnitFinish(Object)`

- `Void _RefreshRemainOnFinishTick(Tile)`

- `Void _OnGameOver(Object)`

- `Void _OnUnitRefresh(Object)`

- `Void OnTrigger(Character, Boolean)`

- `Void _UpdateTileByDiff()`

- `Boolean _ValidCharacter(Character)`

- `Void _GetInViewTile(Character, ref)`

- `Void _MarkInView(Boolean, Tile)`

- `Void AddTickTile(List`1, FP)`

- `Void AddTickTile(IDrawableRange, FP)`

- `Void MarkNotInView(String)`

- `Void MarkInView(String, Int32, Int32, Int32, Int32)`

- `Void MarkInView(Boolean, List`1)`

- `Void _ResetSandboxBuilder()`

- `String GetExploredMap()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnTrigger(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ViewRangeFogManager : EnvManager
{
	private String _toLight; // 0x28
	private String _toHidden; // 0x30
	private String _toHasViewed; // 0x38
	private String _toNotViewed; // 0x40
	private Color _startColor; // 0x48
	private ProfessionCategory[] _rootProfessions; // 0x58
	private ProfessionCategory[] _validEnemyProfessions; // 0x60
	private String _remainOnFinishRange; // 0x68
	private Single _remainOnFinishTime; // 0x70
	private ListDict`2 m_unitModeIndexCache; // 0x78
	private ListDict`2 m_tileInUnitAttackRangeBefore; // 0x80
	private FogEdgeEffectHolder m_fogEdgeEffect; // 0x88
	private RemainingTileTicker m_remainingTileTicker; // 0x90
	private RangeTileViewHolder m_rangeTileViewHolder; // 0x98
	private List`1 m_newInViewTile; // 0xa0
	private Int32[,] m_cacheTileStatus; // 0xa8
	private Int32[,] m_tileStatus; // 0xb0
	private Byte[] m_exploreBytes; // 0xb8
	private String m_extraViewRange; // 0xc0
	private Single m_remainOnFinishTime; // 0xc8
	private String m_forceViewRange; // 0xd0
	private const String EXTRA_VIEW_RANGE; // 0x0
	private const String VIEW_TIME_WHEN_FINISH; // 0x0
	private const String FORCE_VIEW_RANGE; // 0x0
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x10
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x18
	private static DelegateBridge __Hotfix0__RefreshRemainOnFinishTick; // 0x20
	private static DelegateBridge __Hotfix0__OnGameOver; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge __Hotfix0__OnUnitRefresh; // 0x38
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x40
	private static DelegateBridge __Hotfix1_OnTrigger; // 0x48
	private static DelegateBridge __Hotfix0__UpdateTileByDiff; // 0x50
	private static DelegateBridge __Hotfix0__ValidCharacter; // 0x58
	private static DelegateBridge __Hotfix0__GetInViewTile; // 0x60
	private static DelegateBridge __Hotfix0__MarkInView; // 0x68
	private static DelegateBridge __Hotfix0_AddTickTile; // 0x70
	private static DelegateBridge __Hotfix1_AddTickTile; // 0x78
	private static DelegateBridge __Hotfix0_MarkNotInView; // 0x80
	private static DelegateBridge __Hotfix0_MarkInView; // 0x88
	private static DelegateBridge __Hotfix1_MarkInView; // 0x90
	private static DelegateBridge __Hotfix0__ResetSandboxBuilder; // 0x98
	private static DelegateBridge __Hotfix0_GetExploredMap; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x406a540 VA: 0x7596682540
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x406a8f4 VA: 0x75966828f4
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x406b0b0 VA: 0x75966830b0
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x406b890 VA: 0x7596683890
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x406c304 VA: 0x7596684304
	private Void _RefreshRemainOnFinishTick(Tile tile) { }
	// RVA: 0x406c668 VA: 0x7596684668
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x406ca0c VA: 0x7596684a0c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x406caa8 VA: 0x7596684aa8
	private Void _OnUnitRefresh(Object arg) { }
	// RVA: 0x406cb74 VA: 0x7596684b74
	public override Void OnTrigger(Object param) { }
	// RVA: 0x406b3d0 VA: 0x75966833d0
	public Void OnTrigger(Character character, Boolean force) { }
	// RVA: 0x406c410 VA: 0x7596684410
	private Void _UpdateTileByDiff() { }
	// RVA: 0x406cc50 VA: 0x7596684c50
	private Boolean _ValidCharacter(Character character) { }
	// RVA: 0x406bd50 VA: 0x7596683d50
	private Void _GetInViewTile(Character character, ref List`1 newInViewTile) { }
	// RVA: 0x406bc5c VA: 0x7596683c5c
	private Void _MarkInView(Boolean inCharView, Tile tile) { }
	// RVA: 0x406cd84 VA: 0x7596684d84
	public Void AddTickTile(List`1 tiles, FP time) { }
	// RVA: 0x406cf14 VA: 0x7596684f14
	public Void AddTickTile(IDrawableRange range, FP time) { }
	// RVA: 0x406d0a0 VA: 0x75966850a0
	public Void MarkNotInView(String id) { }
	// RVA: 0x406d134 VA: 0x7596685134
	public Void MarkInView(String id, Int32 leftButtomX, Int32 leftButtomY, Int32 rightUpX, Int32 rightUpY) { }
	// RVA: 0x406d210 VA: 0x7596685210
	public Void MarkInView(Boolean inCharView, List`1 tiles) { }
	// RVA: 0x406aeb4 VA: 0x7596682eb4
	private Void _ResetSandboxBuilder() { }
	// RVA: 0x406c75c VA: 0x759668475c
	public String GetExploredMap() { }
	// RVA: 0x406d398 VA: 0x7596685398
	public Void .ctor() { }
	// RVA: 0x406d574 VA: 0x7596685574
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x406d57c VA: 0x759668557c
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x406d584 VA: 0x7596685584
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x406d58c VA: 0x759668558c
	private Void <>xLuaBaseProxy_OnTrigger(Object P0) { }
}
```