# PlayAudio

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _audioSignal`


## Methods

- `Void GatherAudio(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayAudio : ActionNode, IAudioSource
{
	private ActionTargetType _target; // 0x10
	private String _audioSignal; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherAudio; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f99bb0 VA: 0x75945b1bb0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f99c18 VA: 0x75945b1c18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f99dd4 VA: 0x75945b1dd4
	public Void GatherAudio(List`1 results) { }
	// RVA: 0x1f99ee8 VA: 0x75945b1ee8
	public Void .ctor() { }
}
```