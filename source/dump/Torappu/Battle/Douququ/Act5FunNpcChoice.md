# Act5FunNpcChoice

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `Boolean m_hasChosen`

- `Boolean m_choiceIsRight`

- `Boolean result`


## Properties

- `Boolean choiceIsRight`


## Methods

- `Boolean get_choiceIsRight()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class Act5FunNpcChoice
{
	public readonly String npcId; // 0x10
	private readonly Single m_scoreRight; // 0x18
	private readonly Single m_scoreLeft; // 0x1c
	private Boolean m_hasChosen; // 0x20
	private Boolean m_choiceIsRight; // 0x21
	public Boolean result; // 0x22

	public Boolean choiceIsRight { get; }

	// RVA: 0x1dd72e4 VA: 0x75943ef2e4
	public Void .ctor(String npcNpcId) { }
	// RVA: 0x1dd7320 VA: 0x75943ef320
	public Void .ctor(String npc, Single scoreRight, Single scoreLeft) { }
	// RVA: 0x1dd7368 VA: 0x75943ef368
	public Boolean get_choiceIsRight() { }
}
```