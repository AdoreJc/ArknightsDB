# CharacterInst

**Namespace:** `Torappu`


## Fields

- `Metadata inst`

- `Int32 skillIndex`

- `Int32 mainSkillLvl`

- `String skinId`

- `String tmplId`

- `Blackboard overrideSkillBlackboard`


## Properties

- `Boolean isValid`


## Methods

- `Boolean get_isValid()`

- `CharQuery GetCharQuery()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharacterInst
{
	public Metadata inst; // 0x10
	public Int32 skillIndex; // 0x30
	public Int32 mainSkillLvl; // 0x34
	public String skinId; // 0x38
	public String tmplId; // 0x40
	public Blackboard overrideSkillBlackboard; // 0x48

	public virtual Boolean isPredefined { get; }
	public virtual Boolean isHidden { get; }
	public Boolean isValid { get; }

	// RVA: 0x33c9c88 VA: 0x75959e1c88
	public virtual Boolean get_isPredefined() { }
	// RVA: 0x33c9c90 VA: 0x75959e1c90
	public virtual Boolean get_isHidden() { }
	// RVA: 0x33c9c98 VA: 0x75959e1c98
	public Boolean get_isValid() { }
	// RVA: 0x33c9cb8 VA: 0x75959e1cb8
	public override String ToString() { }
	// RVA: 0x33c9f94 VA: 0x75959e1f94
	public virtual String GetAliasId() { }
	// RVA: 0x33c9f9c VA: 0x75959e1f9c
	public CharQuery GetCharQuery() { }
	// RVA: 0x33c9ff8 VA: 0x75959e1ff8
	public Void .ctor() { }
}
```