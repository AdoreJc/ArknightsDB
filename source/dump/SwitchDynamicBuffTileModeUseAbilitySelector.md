# SwitchDynamicBuffTileModeUseAbilitySelector

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `String _abilityName`

- `Operation _operation`

- `Int32 _modeIndex`

- `String _audioSignal`


## Methods

- `Void GatherAudio(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchDynamicBuffTileModeUseAbilitySelector : ActionNode, IAudioSource
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _abilityName; // 0x18
	private Operation _operation; // 0x20
	private Int32 _modeIndex; // 0x24
	private String _audioSignal; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe6fc0 VA: 0x75945fefc0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe7028 VA: 0x75945ff028
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe7618 VA: 0x75945ff618
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x1fe772c VA: 0x75945ff72c
	public Void .ctor() { }
}
```