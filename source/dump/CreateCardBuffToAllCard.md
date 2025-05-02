# CreateCardBuffToAllCard

**Namespace:** ` `


## Fields

- `Boolean _exceptOwner`

- `Boolean _exceptTokenAndTrap`

- `Boolean _buffAsSource`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffToAllCard : BaseCreateCardBuff
{
	private Boolean _exceptOwner; // 0x20
	private Boolean _exceptTokenAndTrap; // 0x21
	private Boolean _buffAsSource; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f099b4 VA: 0x75945219b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f09a1c VA: 0x7594521a1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f09d24 VA: 0x7594521d24
	public Void .ctor() { }
	// RVA: 0x1f09d90 VA: 0x7594521d90
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f09d94 VA: 0x7594521d94
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```