# CheckUnitCurrentMode

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _checkCurModeIndex`

- `String _loadCurModeBbKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckUnitCurrentMode : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _checkCurModeIndex; // 0x14
	private String _loadCurModeBbKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f23b40 VA: 0x759453bb40
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f23ba8 VA: 0x759453bba8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f23d54 VA: 0x759453bd54
	public Void .ctor() { }
}
```