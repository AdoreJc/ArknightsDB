# CreateCardBuffFilterByBuildableType

**Namespace:** ` `


## Fields

- `BuildableType _buildableType`

- `Boolean _expectToken`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffFilterByBuildableType : BaseCreateCardBuff
{
	private BuildableType _buildableType; // 0x20
	private Boolean _expectToken; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f09678 VA: 0x7594521678
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f096e0 VA: 0x75945216e0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f09940 VA: 0x7594521940
	public Void .ctor() { }
	// RVA: 0x1f099ac VA: 0x75945219ac
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f099b0 VA: 0x75945219b0
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```