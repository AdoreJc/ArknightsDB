# CreateCardBuffFilterByCardState

**Namespace:** ` `


## Fields

- `State _cardState`

- `Boolean _ignoreNullOwner`

- `Boolean _randomCard`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffFilterByCardState : BaseCreateCardBuff
{
	private State _cardState; // 0x20
	private Boolean _ignoreNullOwner; // 0x24
	private Boolean _randomCard; // 0x25
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f09f88 VA: 0x7594521f88
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f09ff0 VA: 0x7594521ff0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0a404 VA: 0x7594522404
	public Void .ctor() { }
	// RVA: 0x1f0a478 VA: 0x7594522478
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f0a47c VA: 0x759452247c
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```