# HandBookV2GroupCharViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `CharData charData`

- `String charId`

- `PlayerCharacter playerChar`

- `CharacterData data`

- `NPCData npcData`

- `Boolean isNpc`

- `HandBookCardState state`

- `Boolean isAvail`

- `ForceData forceData`

- `String forceId`


## Properties

- `String name`

- `String displayNumber`

- `Boolean canShowInOtherForce`


## Methods

- `String get_name()`

- `String get_displayNumber()`

- `Boolean get_canShowInOtherForce()`

- `Void SetState(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2GroupCharViewModel
{
	public CharData charData; // 0x10
	public String charId; // 0x18
	public PlayerCharacter playerChar; // 0x20
	public CharacterData data; // 0x28
	public NPCData npcData; // 0x30
	public Boolean isNpc; // 0x38
	public HandBookCardState state; // 0x3c
	public Boolean isAvail; // 0x40
	public List`1 connectList; // 0x48
	public List`1 lineList; // 0x50
	public ForceData forceData; // 0x58
	public String forceId; // 0x60

	public String name { get; }
	public String displayNumber { get; }
	public Boolean canShowInOtherForce { get; }

	// RVA: 0x2ede268 VA: 0x75954f6268
	public String get_name() { }
	// RVA: 0x2ede2d4 VA: 0x75954f62d4
	public String get_displayNumber() { }
	// RVA: 0x2ede340 VA: 0x75954f6340
	public Boolean get_canShowInOtherForce() { }
	// RVA: 0x2eddff4 VA: 0x75954f5ff4
	public Void SetState(Single avgFavor) { }
	// RVA: 0x2eddfb4 VA: 0x75954f5fb4
	public Void .ctor() { }
}
```