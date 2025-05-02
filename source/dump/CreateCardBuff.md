# CreateCardBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _target`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuff : BaseCreateCardBuff
{
	private ActionTargetType _target; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f075dc VA: 0x759451f5dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f07644 VA: 0x759451f644
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f07818 VA: 0x759451f818
	public Void .ctor() { }
	// RVA: 0x1f07884 VA: 0x759451f884
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f07888 VA: 0x759451f888
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```