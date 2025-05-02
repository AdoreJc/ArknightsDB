# InterlockSquadModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `StageAdditionData additionData`

- `CharacterCardViewModel assistCharModel`

- `Boolean isExpand`


## Properties

- `Boolean isInterlock`


## Methods

- `Boolean get_isInterlock()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class InterlockSquadModel : IHotfixable
{
	public StageAdditionData additionData; // 0x10
	public List`1 interlockCharList; // 0x18
	public CharacterCardViewModel assistCharModel; // 0x20
	public Boolean isExpand; // 0x28
	private static DelegateBridge __Hotfix0_get_isInterlock; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean isInterlock { get; }

	// RVA: 0x33d412c VA: 0x75959ec12c
	public Boolean get_isInterlock() { }
	// RVA: 0x33d5004 VA: 0x75959ed004
	public Void .ctor() { }
}
```