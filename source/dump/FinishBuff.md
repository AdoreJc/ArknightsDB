# FinishBuff

**Namespace:** ` `


## Fields

- `Boolean _decCntIfStack`

- `Boolean _updateOverrideMap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishBuff : ActionNode
{
	private Boolean _decCntIfStack; // 0x10
	private Boolean _updateOverrideMap; // 0x11
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef684c VA: 0x759450e84c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef68b4 VA: 0x759450e8b4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef6980 VA: 0x759450e980
	public Void .ctor() { }
}
```