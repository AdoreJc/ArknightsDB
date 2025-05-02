# LogExtraBattleInfoForTile

**Namespace:** ` `


## Fields

- `InfoType _infoType`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfoForTile : ActionNode
{
	private InfoType _infoType; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eeaa5c VA: 0x7594502a5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eeaac4 VA: 0x7594502ac4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eead58 VA: 0x7594502d58
	public Void .ctor() { }
}
```