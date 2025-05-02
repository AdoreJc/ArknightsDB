# LegionModeOnlyGetGoldViaProfessionBuffCount

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _goldPerBuff`

- `Boolean _loadFromBlackboard`

- `String _goldPerBuffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyGetGoldViaProfessionBuffCount : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _goldPerBuff; // 0x14
	private Boolean _loadFromBlackboard; // 0x18
	private String _goldPerBuffKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f63e50 VA: 0x759457be50
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f63eb8 VA: 0x759457beb8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f640d0 VA: 0x759457c0d0
	public Void .ctor() { }
}
```