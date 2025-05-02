# CreepTile

**Namespace:** `Torappu.Battle.Tiles`


## Fields

- `TargetOptions _stopCreepCharacterOption`

- `Range _creepRange`

- `Int32 _defaultMode`

- `Int32 _creepMode`

- `Single _creepProtectTime`

- `Int32 m_originMode`

- `FP m_creepModeStartTime`

- `FP m_creepProtectTime`

- `Direction m_switchDirection`

- `Boolean m_runeExtraCheck`

- `Int32 m_runeCheckBlockCnt`

- `Effect m_currentCreepEffect`


## Methods

- `Void _UpdateCreepEffects(Int32)`

- `Boolean _CheckTriggerable()`

- `Void _TryCastOnTile(CreepTile)`

- `Void _SwitchModeFromDirection(Int32, Direction)`

- `Boolean _ValidateTile(Tile)`

- `Int32 <>xLuaBaseProxy_get_maxTriggerCnt()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`

- `Void <>xLuaBaseProxy_PreloadAssets()`

- `Void <>xLuaBaseProxy_OnSwitchMode(Int32)`

- `Void <>xLuaBaseProxy_OnTrigger()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Tiles
public class CreepTile : DynamicBuffTile
{
	private const Int32 PRELOAD_EFFECT_SIZE; // 0x0
	private TargetOptions _stopCreepCharacterOption; // 0x1d0
	private Range _creepRange; // 0x230
	private Int32 _defaultMode; // 0x238
	private Int32 _creepMode; // 0x23c
	private Single _creepProtectTime; // 0x240
	private List`1 _creepDirectionEffects; // 0x248
	private Int32 m_originMode; // 0x250
	private FP m_creepModeStartTime; // 0x258
	private FP m_creepProtectTime; // 0x260
	private Direction m_switchDirection; // 0x268
	private Boolean m_runeExtraCheck; // 0x26c
	private Int32 m_runeCheckBlockCnt; // 0x270
	private Effect m_currentCreepEffect; // 0x278
	private static DelegateBridge __Hotfix0_get_maxTriggerCnt; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_PreloadAssets; // 0x10
	private static DelegateBridge __Hotfix0_OnSwitchMode; // 0x18
	private static DelegateBridge __Hotfix0__UpdateCreepEffects; // 0x20
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x28
	private static DelegateBridge __Hotfix0__CheckTriggerable; // 0x30
	private static DelegateBridge __Hotfix0__TryCastOnTile; // 0x38
	private static DelegateBridge __Hotfix0__SwitchModeFromDirection; // 0x40
	private static DelegateBridge __Hotfix0__ValidateTile; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected override Int32 maxTriggerCnt { get; }

	// RVA: 0x1daeda8 VA: 0x75943c6da8
	protected override Int32 get_maxTriggerCnt() { }
	// RVA: 0x1daee10 VA: 0x75943c6e10
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x1daf110 VA: 0x75943c7110
	protected override Void PreloadAssets() { }
	// RVA: 0x1daf3d8 VA: 0x75943c73d8
	protected override Void OnSwitchMode(Int32 mode) { }
	// RVA: 0x1daf4b0 VA: 0x75943c74b0
	private Void _UpdateCreepEffects(Int32 mode) { }
	// RVA: 0x1daf6a8 VA: 0x75943c76a8
	protected override Void OnTrigger() { }
	// RVA: 0x1daf930 VA: 0x75943c7930
	private Boolean _CheckTriggerable() { }
	// RVA: 0x1dafb08 VA: 0x75943c7b08
	private Void _TryCastOnTile(CreepTile creepTile) { }
	// RVA: 0x1dafc00 VA: 0x75943c7c00
	private Void _SwitchModeFromDirection(Int32 mode, Direction direction) { }
	// RVA: 0x1dafc98 VA: 0x75943c7c98
	private Boolean _ValidateTile(Tile tile) { }
	// RVA: 0x1dafdd4 VA: 0x75943c7dd4
	public Void .ctor() { }
	// RVA: 0x1dafea4 VA: 0x75943c7ea4
	private Int32 <>xLuaBaseProxy_get_maxTriggerCnt() { }
	// RVA: 0x1dafeac VA: 0x75943c7eac
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
	// RVA: 0x1dafeb4 VA: 0x75943c7eb4
	private Void <>xLuaBaseProxy_PreloadAssets() { }
	// RVA: 0x1dafebc VA: 0x75943c7ebc
	private Void <>xLuaBaseProxy_OnSwitchMode(Int32 P0) { }
	// RVA: 0x1dafec4 VA: 0x75943c7ec4
	private Void <>xLuaBaseProxy_OnTrigger() { }
}
```