# LogExtraBattleInfoForBuff

**Namespace:** ` `


## Fields

- `InfoType _infoType`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfoForBuff : ActionNode
{
	private InfoType _infoType; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eea72c VA: 0x759450272c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eea794 VA: 0x7594502794
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eea9ec VA: 0x75945029ec
	public Void .ctor() { }
}
```