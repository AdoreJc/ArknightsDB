# FootballEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `FootBallHudPluginTalent _footBallHudPluginTalent`

- `String _collideSignalId`

- `String _takeDamageSignalId`

- `String _unbalancedSignalId`

- `Boolean _disableIdleAnimation`

- `ActionArray _actionsWhenCollide`

- `FP m_attenuation`

- `Boolean m_isSelected`

- `Boolean m_isUnStoppable`

- `Tile m_cacheRootTile`

- `Boolean <isSelected>k__BackingField`


## Properties

- `Boolean isSelected`


## Methods

- `Boolean get_isSelected()`

- `Void set_isSelected(Boolean)`

- `Void KickByEnemy(Vector2, FP)`

- `Void _FindSurroundingTiles()`

- `Void _UpdateUnbalanceAnimation()`

- `Void UpdateRestitutionFactor(FP)`

- `Boolean StopBall(Boolean)`

- `Void OnLandFootball()`

- `Void ModifyKickValue(FP)`

- `Void OnCollisionEnter2D(Collision2D)`

- `Void _RunActionsWhenCollide(Entity)`

- `Boolean <>xLuaBaseProxy_get_disableUIUnitHud()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnTakeDamage(ref, Boolean)`

- `Void <>xLuaBaseProxy_KnockBack(Vector2, Single, Boolean)`

- `Boolean <>xLuaBaseProxy_BeginPull(BObject, Vector2, Single)`

- `Void <>xLuaBaseProxy_PlayUnbalanceAnimation()`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FootballEnemy : BounceEnemy
{
	private FootBallHudPluginTalent _footBallHudPluginTalent; // 0x4c0
	private String _collideSignalId; // 0x4c8
	private String _takeDamageSignalId; // 0x4d0
	private String _unbalancedSignalId; // 0x4d8
	private Boolean _disableIdleAnimation; // 0x4e0
	private ActionArray _actionsWhenCollide; // 0x4e8
	private const Single UNSTOPPABLE_TIME; // 0x0
	private readonly HashSet`1 m_surroundTiles; // 0x4f0
	private FP m_attenuation; // 0x4f8
	private Boolean m_isSelected; // 0x500
	private Boolean m_isUnStoppable; // 0x501
	private readonly Vector2[] m_directionVectors; // 0x508
	private readonly String MOVE_LEFT_KEY; // 0x510
	private readonly String MOVE_RIGHT_KEY; // 0x518
	private readonly PeriodicTimer m_unstoppableTicker; // 0x520
	private Tile m_cacheRootTile; // 0x528
	private Boolean <isSelected>k__BackingField; // 0x530
	private static DelegateBridge __Hotfix0_get_disableUIUnitHud; // 0x0
	private static DelegateBridge __Hotfix0_get_isSelected; // 0x8
	private static DelegateBridge __Hotfix0_set_isSelected; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x20
	private static DelegateBridge __Hotfix0_KnockBack; // 0x28
	private static DelegateBridge __Hotfix0_BeginPull; // 0x30
	private static DelegateBridge __Hotfix0_PlayUnbalanceAnimation; // 0x38
	private static DelegateBridge __Hotfix0_KickByEnemy; // 0x40
	private static DelegateBridge __Hotfix0__FindSurroundingTiles; // 0x48
	private static DelegateBridge __Hotfix0__UpdateUnbalanceAnimation; // 0x50
	private static DelegateBridge __Hotfix0_UpdateRestitutionFactor; // 0x58
	private static DelegateBridge __Hotfix0_StopBall; // 0x60
	private static DelegateBridge __Hotfix0_OnLandFootball; // 0x68
	private static DelegateBridge __Hotfix0_ModifyKickValue; // 0x70
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x78
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x80
	private static DelegateBridge __Hotfix0_OnCollisionEnter2D; // 0x88
	private static DelegateBridge __Hotfix0__RunActionsWhenCollide; // 0x90
	private static DelegateBridge __Hotfix0_OnReset; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public override Boolean disableUIUnitHud { get; }
	public Boolean isSelected { get; set; }

	// RVA: 0x1c1bd28 VA: 0x7594233d28
	public override Boolean get_disableUIUnitHud() { }
	// RVA: 0x1c1bd8c VA: 0x7594233d8c
	public Boolean get_isSelected() { }
	// RVA: 0x1c1bdf4 VA: 0x7594233df4
	public Void set_isSelected(Boolean value) { }
	// RVA: 0x1c1be74 VA: 0x7594233e74
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x1c1c124 VA: 0x7594234124
	protected override Void OnTakeDamage(ref Modifier modifier, Boolean force) { }
	// RVA: 0x1c1c968 VA: 0x7594234968
	public override Void KnockBack(Vector2 direction, Single force, Boolean changeFaceByDirection) { }
	// RVA: 0x1c1cab0 VA: 0x7594234ab0
	public override Boolean BeginPull(BObject source, Vector2 direction, Single force) { }
	// RVA: 0x1c1cbf0 VA: 0x7594234bf0
	public override Void PlayUnbalanceAnimation() { }
	// RVA: 0x1c1cc58 VA: 0x7594234c58
	public Void KickByEnemy(Vector2 direction, FP forceScale) { }
	// RVA: 0x1c1c7cc VA: 0x75942347cc
	private Void _FindSurroundingTiles() { }
	// RVA: 0x1c1c024 VA: 0x7594234024
	private Void _UpdateUnbalanceAnimation() { }
	// RVA: 0x1c1cd24 VA: 0x7594234d24
	public Void UpdateRestitutionFactor(FP value) { }
	// RVA: 0x1c1ce94 VA: 0x7594234e94
	public Boolean StopBall(Boolean force) { }
	// RVA: 0x1c1cf7c VA: 0x7594234f7c
	public Void OnLandFootball() { }
	// RVA: 0x1c1cff4 VA: 0x7594234ff4
	public Void ModifyKickValue(FP value) { }
	// RVA: 0x1c1d080 VA: 0x7594235080
	public override Void GatherActionNodes(List`1 actions) { }
	// RVA: 0x1c1d138 VA: 0x7594235138
	public override Void PreloadSpecialAudioSignals(String unitId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1c1d244 VA: 0x7594235244
	private Void OnCollisionEnter2D(Collision2D other) { }
	// RVA: 0x1c1d49c VA: 0x759423549c
	private Void _RunActionsWhenCollide(Entity target) { }
	// RVA: 0x1c1d74c VA: 0x759423574c
	protected override Void OnReset() { }
	// RVA: 0x1c1d7f0 VA: 0x75942357f0
	public Void .ctor() { }
	// RVA: 0x1c1da98 VA: 0x7594235a98
	private Boolean <>xLuaBaseProxy_get_disableUIUnitHud() { }
	// RVA: 0x1c1daa0 VA: 0x7594235aa0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1c1daa8 VA: 0x7594235aa8
	private Void <>xLuaBaseProxy_OnTakeDamage(ref Modifier P0, Boolean P1) { }
	// RVA: 0x1c1dab4 VA: 0x7594235ab4
	private Void <>xLuaBaseProxy_KnockBack(Vector2 P0, Single P1, Boolean P2) { }
	// RVA: 0x1c1dac0 VA: 0x7594235ac0
	private Boolean <>xLuaBaseProxy_BeginPull(BObject P0, Vector2 P1, Single P2) { }
	// RVA: 0x1c1dac8 VA: 0x7594235ac8
	private Void <>xLuaBaseProxy_PlayUnbalanceAnimation() { }
	// RVA: 0x1c1dad0 VA: 0x7594235ad0
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
	// RVA: 0x1c1dad8 VA: 0x7594235ad8
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
	// RVA: 0x1c1dae0 VA: 0x7594235ae0
	private Void <>xLuaBaseProxy_OnReset() { }
}
```