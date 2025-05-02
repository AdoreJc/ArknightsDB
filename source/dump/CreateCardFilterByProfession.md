# CreateCardFilterByProfession

**Namespace:** ` `


## Fields

- `ProfessionCategory _profession`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardFilterByProfession : BaseCreateCardBuff
{
	private ProfessionCategory _profession; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f06614 VA: 0x759451e614
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0667c VA: 0x759451e67c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f06a44 VA: 0x759451ea44
	public Void .ctor() { }
	// RVA: 0x1f06b20 VA: 0x759451eb20
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f06b8c VA: 0x759451eb8c
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```