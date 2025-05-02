# TileMapEffectOnPlayEmitter

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean m_hasPlayed`


## Methods

- `Void _OnPlayInternal()`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class TileMapEffectOnPlayEmitter : Behaviour, IEffectSource
{
	private MapEffectData[] _mapEffectData; // 0x20
	private Boolean m_hasPlayed; // 0x28
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0__OnPlayInternal; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_OnFinish; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2013e10 VA: 0x759462be10
	public override Void OnPlay() { }
	// RVA: 0x2013e94 VA: 0x759462be94
	protected Void _OnPlayInternal() { }
	// RVA: 0x20140b8 VA: 0x759462c0b8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x20141e8 VA: 0x759462c1e8
	public override Void OnFinish() { }
	// RVA: 0x201425c VA: 0x759462c25c
	public Void .ctor() { }
	// RVA: 0x20142cc VA: 0x759462c2cc
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x20142d4 VA: 0x759462c2d4
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```