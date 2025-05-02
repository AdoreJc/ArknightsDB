# RequestSquadSlot

**Namespace:** `Torappu`


## Fields

- `Int32 charInstId`

- `Int32 S_skillIndex`

- `String S_currentTmpl`

- `String S_currentEquip`


## Methods

- `Boolean ShouldSerializeS_currentTmpl()`

- `Boolean ShouldSerializeS_skillIndex()`

- `Boolean ShouldSerializeS_tmpl()`

- `Boolean ShouldSerializeS_currentEquip()`

- `Int32 GetSkillIndex()`

- `String GetEquipId()`

- `String GetCurTmpl()`

- `Patch _SafeTmpl(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RequestSquadSlot
{
	public Int32 charInstId; // 0x10
	public Int32 S_skillIndex; // 0x14
	public String S_currentTmpl; // 0x18
	public ListDict`2 S_tmpl; // 0x20
	public String S_currentEquip; // 0x28


	// RVA: 0x32cd60c VA: 0x75958e560c
	protected Void .ctor() { }
	// RVA: 0x32cd614 VA: 0x75958e5614
	public Boolean ShouldSerializeS_currentTmpl() { }
	// RVA: 0x32cd624 VA: 0x75958e5624
	public Boolean ShouldSerializeS_skillIndex() { }
	// RVA: 0x32cd634 VA: 0x75958e5634
	public Boolean ShouldSerializeS_tmpl() { }
	// RVA: 0x32cd644 VA: 0x75958e5644
	public Boolean ShouldSerializeS_currentEquip() { }
	// RVA: 0x32cd654 VA: 0x75958e5654
	public Int32 GetSkillIndex() { }
	// RVA: 0x32cd6e0 VA: 0x75958e56e0
	public String GetEquipId() { }
	// RVA: 0x32cd70c VA: 0x75958e570c
	public String GetCurTmpl() { }
	// RVA: 0x32cd680 VA: 0x75958e5680
	private Patch _SafeTmpl(String tmplId) { }
	// RVA: 0x32cd714 VA: 0x75958e5714
	public static RequestSquadSlot Create(Int32 instId, CharQuery query, Int32 skillIndex, String equipId, ISquadMemberCompInfo extraInfo) { }
}
```