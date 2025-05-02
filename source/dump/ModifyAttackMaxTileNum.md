# ModifyAttackMaxTileNum

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _maxTileNum`

- `Int32 _modeIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyAttackMaxTileNum : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _maxTileNum; // 0x14
	private Int32 _modeIndex; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcea78 VA: 0x75945e6a78
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fceae0 VA: 0x75945e6ae0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcecd8 VA: 0x75945e6cd8
	public Void .ctor() { }
}
```