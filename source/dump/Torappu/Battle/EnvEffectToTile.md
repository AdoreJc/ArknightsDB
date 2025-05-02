# EnvEffectToTile

**Namespace:** `Torappu.Battle`


## Fields

- `EffectSetting _effectSettings`

- `String m_effectKey`


## Properties

- `String effectKey`


## Methods

- `String get_effectKey()`

- `Void <>xLuaBaseProxy_OnEnvChanged(Tile, String)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvEffectToTile : EnvEventExecutor
{
	private EffectSetting _effectSettings; // 0x28
	private ListDict`2 m_tileEffectDict; // 0x50
	private String m_effectKey; // 0x58
	private static DelegateBridge __Hotfix0_get_effectKey; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private String effectKey { get; }

	// RVA: 0x401fd80 VA: 0x7596637d80
	private String get_effectKey() { }
	// RVA: 0x401fe34 VA: 0x7596637e34
	public override Void OnEnvChanged(Tile tile, String status) { }
	// RVA: 0x402003c VA: 0x759663803c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x40201a4 VA: 0x75966381a4
	public Void .ctor() { }
	// RVA: 0x4020268 VA: 0x7596638268
	private Void <>xLuaBaseProxy_OnEnvChanged(Tile P0, String P1) { }
	// RVA: 0x4020270 VA: 0x7596638270
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```