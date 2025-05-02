# CheckTileOptions

**Namespace:** ` `


## Fields

- `Boolean _ignoreAdvancedBuildableMask`

- `AdvancedBuildableMask _advancedBuildableMask`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTileOptions : ActionNode
{
	private Boolean _ignoreAdvancedBuildableMask; // 0x10
	private AdvancedBuildableMask _advancedBuildableMask; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe7890 VA: 0x75945ff890
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe78f8 VA: 0x75945ff8f8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe7a14 VA: 0x75945ffa14
	public Void .ctor() { }
}
```