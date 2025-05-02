# LegionModeOnlyDrawCardViaProfession

**Namespace:** ` `


## Fields

- `Boolean _randomDrawCard`

- `Boolean _addCardBuff`

- `Boolean _drawCardFromUsedAndPending`

- `ProfessionCategory m_targetProfessionGroup`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyDrawCardViaProfession : ActionNode
{
	private List`1 _professions; // 0x10
	private Boolean _randomDrawCard; // 0x18
	private Boolean _addCardBuff; // 0x19
	private Boolean _drawCardFromUsedAndPending; // 0x1a
	private ProfessionCategory m_targetProfessionGroup; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f68380 VA: 0x7594580380
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f683e8 VA: 0x75945803e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f68728 VA: 0x7594580728
	public Void .ctor() { }
}
```