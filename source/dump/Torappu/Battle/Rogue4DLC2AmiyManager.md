# Rogue4DLC2AmiyManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _tileEffect`

- `Boolean _tileHoldEffect`

- `Options _tileVerifyOptions`

- `BuffData _buff`

- `BuildableType _buildableType`

- `Int32 m_nextSealCol`

- `Int32 m_endCol`

- `Int32 m_curCol`

- `Boolean m_isAffecting`

- `Single m_interval`

- `Single m_interruptInterval`

- `Boolean m_needEarlyStop`

- `Enemy m_boss`

- `PeriodicTimer m_sealTileTimer`

- `PeriodicTimer m_stopEffectTimer`

- `PeriodicTimer m_interruptTimer`

- `Int32 m_spellCnt`


## Methods

- `Void TriggerSealTile(Enemy, Int32, Int32, Single)`

- `Void StopSealTile()`

- `Void _StartTimer(Single)`

- `Void _StopTimer()`

- `Void _StartFinishOldEffectTimer(Single)`

- `Void _SealTile(Int32)`

- `Boolean _TileEffectApplicable(Tile)`

- `Boolean _VerifyTileKey(Tile)`

- `Void _StopOutOfDateEffect()`

- `Void GatherAudio(List`1)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Rogue4DLC2AmiyManager : EnvManager, IBuffSource, IHotfixable, IAudioSource
{
	private String _tileEffect; // 0x28
	private Boolean _tileHoldEffect; // 0x30
	private Options _tileVerifyOptions; // 0x38
	private BuffData _buff; // 0x70
	private BuildableType _buildableType; // 0x78
	private Int32 m_nextSealCol; // 0x7c
	private Int32 m_endCol; // 0x80
	private Int32 m_curCol; // 0x84
	private Boolean m_isAffecting; // 0x88
	private Single m_interval; // 0x8c
	private Single m_interruptInterval; // 0x90
	private Boolean m_needEarlyStop; // 0x94
	private Enemy m_boss; // 0x98
	private PeriodicTimer m_sealTileTimer; // 0xa0
	private PeriodicTimer m_stopEffectTimer; // 0xa8
	private PeriodicTimer m_interruptTimer; // 0xb0
	private const String m_tileKeyForbidden; // 0x0
	private const String m_tileKeyTelout; // 0x0
	private const String m_tileKeyTelin; // 0x0
	private const String m_tileKeyStart; // 0x0
	private const String m_tileKeyEnd; // 0x0
	private const String m_tileKeyHole; // 0x0
	private const String SEAL_TILE_AUDIO_SIGNAL; // 0x0
	private List`1 m_effectCollection1; // 0xb8
	private List`1 m_effectCollection2; // 0xc0
	private Int32 m_spellCnt; // 0xc8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_TriggerSealTile; // 0x18
	private static DelegateBridge __Hotfix0_StopSealTile; // 0x20
	private static DelegateBridge __Hotfix0__StartTimer; // 0x28
	private static DelegateBridge __Hotfix0__StopTimer; // 0x30
	private static DelegateBridge __Hotfix0__StartFinishOldEffectTimer; // 0x38
	private static DelegateBridge __Hotfix0__SealTile; // 0x40
	private static DelegateBridge __Hotfix0__TileEffectApplicable; // 0x48
	private static DelegateBridge __Hotfix0__VerifyTileKey; // 0x50
	private static DelegateBridge __Hotfix0__StopOutOfDateEffect; // 0x58
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x4064fa0 VA: 0x759667cfa0
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x406505c VA: 0x759667d05c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4065bb8 VA: 0x759667dbb8
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x4065c3c VA: 0x759667dc3c
	public Void TriggerSealTile(Enemy enemy, Int32 startCol, Int32 endCol, Single interval) { }
	// RVA: 0x406524c VA: 0x759667d24c
	public Void StopSealTile() { }
	// RVA: 0x40658b8 VA: 0x759667d8b8
	private Void _StartTimer(Single interval) { }
	// RVA: 0x4065d8c VA: 0x759667dd8c
	private Void _StopTimer() { }
	// RVA: 0x4065e10 VA: 0x759667de10
	private Void _StartFinishOldEffectTimer(Single interval) { }
	// RVA: 0x40652dc VA: 0x759667d2dc
	private Void _SealTile(Int32 col) { }
	// RVA: 0x4065ed4 VA: 0x759667ded4
	private Boolean _TileEffectApplicable(Tile tile) { }
	// RVA: 0x4065fa4 VA: 0x759667dfa4
	private Boolean _VerifyTileKey(Tile tile) { }
	// RVA: 0x40659a4 VA: 0x759667d9a4
	private Void _StopOutOfDateEffect() { }
	// RVA: 0x4066150 VA: 0x759667e150
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x4066258 VA: 0x759667e258
	public Void .ctor() { }
	// RVA: 0x4066488 VA: 0x759667e488
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4066490 VA: 0x759667e490
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x4066498 VA: 0x759667e498
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```