# FinishDeckBuffByCardUIDAndKey

**Namespace:** ` `


## Fields

- `String _blackBoardKey`

- `String _deckBuffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishDeckBuffByCardUIDAndKey : ActionNode
{
	private String _blackBoardKey; // 0x10
	private String _deckBuffKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4e944 VA: 0x7594566944
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4e9ac VA: 0x75945669ac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4ec3c VA: 0x7594566c3c
	public Void .ctor() { }
}
```