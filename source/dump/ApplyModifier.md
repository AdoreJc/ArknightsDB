# ApplyModifier

**Namespace:** ` `


## Fields

- `Modifier m_modifier`


## Properties

- `Modifier modifier`


## Methods

- `Modifier get_modifier()`

- `Void set_modifier(Modifier)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ApplyModifier : ActionNode
{
	private Modifier m_modifier; // 0x10
	private static DelegateBridge __Hotfix0_get_modifier; // 0x0
	private static DelegateBridge __Hotfix0_set_modifier; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge _c__Hotfix1_ctor; // 0x28

	public Modifier modifier { get; set; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f71d58 VA: 0x7594589d58
	public Modifier get_modifier() { }
	// RVA: 0x1f71dfc VA: 0x7594589dfc
	public Void set_modifier(Modifier value) { }
	// RVA: 0x1f71eb4 VA: 0x7594589eb4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f71f1c VA: 0x7594589f1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f72044 VA: 0x759458a044
	public Void .ctor() { }
	// RVA: 0x1f720b4 VA: 0x759458a0b4
	public Void .ctor(ref Modifier modifier) { }
}
```