# FinishDerivedBuffById

**Namespace:** ` `


## Fields

- `String _buffKey`

- `Boolean _decCntIfStack`

- `Boolean _updateOverrideMap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishDerivedBuffById : ActionNode
{
	private String _buffKey; // 0x10
	private Boolean _decCntIfStack; // 0x18
	private Boolean _updateOverrideMap; // 0x19
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef7f70 VA: 0x759450ff70
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef7fd8 VA: 0x759450ffd8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef808c VA: 0x759451008c
	public Void .ctor() { }
}
```