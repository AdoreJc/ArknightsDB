# CreateCardBuffFilterByTag

**Namespace:** ` `


## Fields

- `String _tag`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffFilterByTag : BaseCreateCardBuff
{
	private String _tag; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f093a8 VA: 0x75945213a8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f09410 VA: 0x7594521410
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f09604 VA: 0x7594521604
	public Void .ctor() { }
	// RVA: 0x1f09670 VA: 0x7594521670
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f09674 VA: 0x7594521674
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```