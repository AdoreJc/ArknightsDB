# GainToken

**Namespace:** ` `


## Fields

- `RechargeTiming _rechargeTiming`

- `Boolean _getPlayerSideFromActionTargetType`

- `ActionTargetType _targetType`

- `Boolean _spiltTokenKey`

- `String _extraLogKey`

- `String _extraAudioKey`


## Methods

- `Void GatherEffects(List`1)`

- `Void _GainToken(PlayerSide, String, Int32)`

- `Void GatherAudio(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GainToken : ActionNode, IEffectSource, IAudioSource
{
	private RechargeTiming _rechargeTiming; // 0x10
	private Boolean _getPlayerSideFromActionTargetType; // 0x14
	private ActionTargetType _targetType; // 0x18
	private Boolean _spiltTokenKey; // 0x1c
	private String[] _effectKeys; // 0x20
	private String _extraLogKey; // 0x28
	private String _extraAudioKey; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__GainToken; // 0x18
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe9498 VA: 0x7594601498
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe9500 VA: 0x7594601500
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1fe95d4 VA: 0x75946015d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe9b08 VA: 0x7594601b08
	private Void _GainToken(PlayerSide playerSide, String key, Int32 count) { }
	// RVA: 0x1fe9d84 VA: 0x7594601d84
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x1fe9e98 VA: 0x7594601e98
	public Void .ctor() { }
}
```