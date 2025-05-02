# RewriteTileOptionsInSpecifiedArea

**Namespace:** ` `


## Fields

- `Boolean _SpecifyByGridColumn`

- `Boolean _useAnotherColEnd`

- `AdvancedBuildableMask _advancedBuildableMask`

- `Boolean _isExcludeMode`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RewriteTileOptionsInSpecifiedArea : ActionNode
{
	private Boolean _SpecifyByGridColumn; // 0x10
	private Boolean _useAnotherColEnd; // 0x11
	private AdvancedBuildableMask _advancedBuildableMask; // 0x14
	private Boolean _isExcludeMode; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef53c8 VA: 0x759450d3c8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef5430 VA: 0x759450d430
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef5664 VA: 0x759450d664
	public Void .ctor() { }
}
```