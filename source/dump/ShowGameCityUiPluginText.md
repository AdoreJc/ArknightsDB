# ShowGameCityUiPluginText

**Namespace:** ` `


## Fields

- `String _indexKey`

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ShowGameCityUiPluginText : ActionNode
{
	private String _indexKey; // 0x10
	private ActionTargetType _target; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f558a8 VA: 0x759456d8a8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f55910 VA: 0x759456d910
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f55b84 VA: 0x759456db84
	public Void .ctor() { }
}
```