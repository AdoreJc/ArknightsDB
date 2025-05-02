# YuS3EffectWithEdgeBehaviour

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _effectVerticalWhenAtWorldRight`

- `String _effectVerticalWhenAtWorldLeft`

- `String _effectWhenHorizontal`

- `String _effectEdgeWhenHorizontalLeft`

- `String _effectEdgeWhenHorizontalRight`

- `String _effectEdgeWhenVerticalWorldLeftUp`

- `String _effectEdgeWhenVerticalWorldLeftDown`

- `String _effectEdgeWhenVerticalWorldRightUp`

- `String _effectEdgeWhenVerticalWorldRightDown`

- `Single _edgeEffectInterval`

- `Single _edgeEffectIntervalFirstTick`

- `Single _offset`

- `Boolean m_inited`

- `Single m_lastEdgeEffectTime`

- `GridPosition m_playedPosition`


## Methods

- `Void Update()`

- `Void OnDestroy()`

- `Void _InitPlayersIfNot()`

- `Void GatherEffects(List`1)`

- `Void ChangeEffectsExt(String)`

- `String _ReplaceEffectName(String, String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class YuS3EffectWithEdgeBehaviour : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _effectVerticalWhenAtWorldRight; // 0x20
	private String _effectVerticalWhenAtWorldLeft; // 0x28
	private String _effectWhenHorizontal; // 0x30
	private String _effectEdgeWhenHorizontalLeft; // 0x38
	private String _effectEdgeWhenHorizontalRight; // 0x40
	private String _effectEdgeWhenVerticalWorldLeftUp; // 0x48
	private String _effectEdgeWhenVerticalWorldLeftDown; // 0x50
	private String _effectEdgeWhenVerticalWorldRightUp; // 0x58
	private String _effectEdgeWhenVerticalWorldRightDown; // 0x60
	private Single _edgeEffectInterval; // 0x68
	private Single _edgeEffectIntervalFirstTick; // 0x6c
	private Single _offset; // 0x70
	private Boolean m_inited; // 0x74
	private Single m_lastEdgeEffectTime; // 0x78
	private GridPosition m_playedPosition; // 0x7c
	private List`1 m_effectPlayers; // 0x88
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnFinish; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__InitPlayersIfNot; // 0x20
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x28
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x30
	private static DelegateBridge __Hotfix0__ReplaceEffectName; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x200b2ac VA: 0x75946232ac
	public override Void OnPlay() { }
	// RVA: 0x200b370 VA: 0x7594623370
	public override Void OnFinish() { }
	// RVA: 0x200b694 VA: 0x7594623694
	private Void Update() { }
	// RVA: 0x200c394 VA: 0x7594624394
	private Void OnDestroy() { }
	// RVA: 0x200b888 VA: 0x7594623888
	private Void _InitPlayersIfNot() { }
	// RVA: 0x200c970 VA: 0x7594624970
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x200cd44 VA: 0x7594624d44
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x200ce48 VA: 0x7594624e48
	private String _ReplaceEffectName(String effectName, String ext) { }
	// RVA: 0x200cee8 VA: 0x7594624ee8
	public Void .ctor() { }
	// RVA: 0x200cfc0 VA: 0x7594624fc0
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x200cfc8 VA: 0x7594624fc8
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```