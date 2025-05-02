# SetPlayerCharacterCnt

**Namespace:** ` `


## Fields

- `Int32 _cnt`

- `PlayerSide _playerSide`

- `Boolean _loadCntFromBlackboard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetPlayerCharacterCnt : ActionNode
{
	private Int32 _cnt; // 0x10
	private PlayerSide _playerSide; // 0x14
	private Boolean _loadCntFromBlackboard; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcdeb4 VA: 0x75945e5eb4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcdf1c VA: 0x75945e5f1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fce030 VA: 0x75945e6030
	public Void .ctor() { }
}
```