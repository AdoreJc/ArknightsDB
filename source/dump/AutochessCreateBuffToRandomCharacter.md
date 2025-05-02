# AutochessCreateBuffToRandomCharacter

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `Boolean _isDerivedBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessCreateBuffToRandomCharacter : ActionNode
{
	private BuffData _buff; // 0x10
	private Boolean _isDerivedBuff; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee5ac8 VA: 0x75944fdac8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee5b30 VA: 0x75944fdb30
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee60bc VA: 0x75944fe0bc
	public Void .ctor() { }
}
```