# CreateCardBuffFilterByDeckBuff

**Namespace:** ` `


## Fields

- `String _buffKey`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffFilterByDeckBuff : BaseCreateCardBuff
{
	private String _buffKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f072d0 VA: 0x759451f2d0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f07338 VA: 0x759451f338
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f07568 VA: 0x759451f568
	public Void .ctor() { }
	// RVA: 0x1f075d4 VA: 0x759451f5d4
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f075d8 VA: 0x759451f5d8
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```