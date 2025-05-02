# DefendCharModel

**Namespace:** `Torappu.Activity.Act1Lock.BattleFinish`


## Fields

- `CharacterCardViewModel cardModel`

- `Boolean isAssist`

- `Boolean isEvacuate`

- `Boolean isEnter`


## Properties

- `String charId`


## Methods

- `String get_charId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.BattleFinish
public class DefendCharModel : IHotfixable
{
	public CharacterCardViewModel cardModel; // 0x10
	public Boolean isAssist; // 0x18
	public Boolean isEvacuate; // 0x19
	public Boolean isEnter; // 0x1a
	private static DelegateBridge __Hotfix0_get_charId; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public String charId { get; }

	// RVA: 0x33e1e78 VA: 0x75959f9e78
	public String get_charId() { }
	// RVA: 0x33e1ca8 VA: 0x75959f9ca8
	public Void .ctor() { }
}
```