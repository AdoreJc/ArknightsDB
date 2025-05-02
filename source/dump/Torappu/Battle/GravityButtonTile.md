# GravityButtonTile

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _activateMass`

- `Int32 _activateBlockCnt`

- `String _activateBlockCntKey`

- `String _sourceDirectionKey`

- `String _buttonSignalKey`

- `String _infoKey`

- `BuffData _buff`

- `Int32 m_activateBlockCnt`

- `Int32 m_buttonDirection`

- `Character m_gractrl`


## Properties

- `Character gractrl`

- `Int32 buttonDirection`


## Methods

- `Character get_gractrl()`

- `Int32 get_buttonDirection()`

- `Void _SetDirection(Int32)`

- `Boolean _IsButtonPressed()`

- `Boolean _CheckSingleEnemyMass(Enemy)`

- `Boolean _CheckEnemiesMass()`

- `Boolean _CheckCharacterBlockCount()`

- `Void _PressButton()`

- `Void _CreateBtnEffectIfNot()`

- `Void _ReleaseButton()`

- `Void _FinishEffectIfNot()`

- `Void GatherEffects(List`1)`

- `Void TryAddBuff()`

- `Void GatherBuffs(List`1)`

- `Void <Init>b__19_0(Object)`

- `Boolean <>xLuaBaseProxy_get_triggerable()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`

- `Void <>xLuaBaseProxy_OnTrigger()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GravityButtonTile : Tile, IEffectSource, IBuffSource
{
	private Int32 _activateMass; // 0x10c
	private Int32 _activateBlockCnt; // 0x110
	private String _activateBlockCntKey; // 0x118
	private String _sourceDirectionKey; // 0x120
	private String _buttonSignalKey; // 0x128
	private String _infoKey; // 0x130
	protected BuffData _buff; // 0x138
	private List`1 _effects; // 0x140
	private Int32 m_activateBlockCnt; // 0x148
	private Int32 m_buttonDirection; // 0x14c
	private Character m_gractrl; // 0x150
	private ObjectPtr`1 m_effect; // 0x158
	private static DelegateBridge __Hotfix0_get_gractrl; // 0x0
	private static DelegateBridge __Hotfix0_get_buttonDirection; // 0x8
	private static DelegateBridge __Hotfix0_get_triggerable; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0__SetDirection; // 0x20
	private static DelegateBridge __Hotfix0__IsButtonPressed; // 0x28
	private static DelegateBridge __Hotfix0__CheckSingleEnemyMass; // 0x30
	private static DelegateBridge __Hotfix0__CheckEnemiesMass; // 0x38
	private static DelegateBridge __Hotfix0__CheckCharacterBlockCount; // 0x40
	private static DelegateBridge __Hotfix0__PressButton; // 0x48
	private static DelegateBridge __Hotfix0__CreateBtnEffectIfNot; // 0x50
	private static DelegateBridge __Hotfix0__ReleaseButton; // 0x58
	private static DelegateBridge __Hotfix0__FinishEffectIfNot; // 0x60
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x68
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x70
	private static DelegateBridge __Hotfix0_TryAddBuff; // 0x78
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	private Character gractrl { get; }
	private Int32 buttonDirection { get; }
	public override Boolean triggerable { get; }

	// RVA: 0x408f28c VA: 0x75966a728c
	private Character get_gractrl() { }
	// RVA: 0x408f380 VA: 0x75966a7380
	private Int32 get_buttonDirection() { }
	// RVA: 0x408f418 VA: 0x75966a7418
	public override Boolean get_triggerable() { }
	// RVA: 0x408f54c VA: 0x75966a754c
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x408f6a4 VA: 0x75966a76a4
	private Void _SetDirection(Int32 direction) { }
	// RVA: 0x408f480 VA: 0x75966a7480
	private Boolean _IsButtonPressed() { }
	// RVA: 0x408fee4 VA: 0x75966a7ee4
	private Boolean _CheckSingleEnemyMass(Enemy enemy) { }
	// RVA: 0x409003c VA: 0x75966a803c
	private Boolean _CheckEnemiesMass() { }
	// RVA: 0x40903d8 VA: 0x75966a83d8
	private Boolean _CheckCharacterBlockCount() { }
	// RVA: 0x4090518 VA: 0x75966a8518
	private Void _PressButton() { }
	// RVA: 0x40906c4 VA: 0x75966a86c4
	private Void _CreateBtnEffectIfNot() { }
	// RVA: 0x408fd54 VA: 0x75966a7d54
	private Void _ReleaseButton() { }
	// RVA: 0x4090a04 VA: 0x75966a8a04
	private Void _FinishEffectIfNot() { }
	// RVA: 0x4090b24 VA: 0x75966a8b24
	protected override Void OnTrigger() { }
	// RVA: 0x4090bbc VA: 0x75966a8bbc
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x408f91c VA: 0x75966a791c
	private Void TryAddBuff() { }
	// RVA: 0x4090de4 VA: 0x75966a8de4
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x4090eec VA: 0x75966a8eec
	public Void .ctor() { }
	// RVA: 0x409101c VA: 0x75966a901c
	private Void <Init>b__19_0(Object obj) { }
	// RVA: 0x40910cc VA: 0x75966a90cc
	private Boolean <>xLuaBaseProxy_get_triggerable() { }
	// RVA: 0x40910d0 VA: 0x75966a90d0
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
	// RVA: 0x40910d4 VA: 0x75966a90d4
	private Void <>xLuaBaseProxy_OnTrigger() { }
}
```