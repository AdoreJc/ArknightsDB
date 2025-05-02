# RoguelikeEntryViewModel

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `String focusTopicId`

- `Int32 focusIndex`

- `Int32 entrySequenceId`

- `Boolean hasOnBattleTheme`


## Methods

- `Void LoadData()`

- `Boolean CheckIfTopicAccessible(String)`

- `Void SetFocusTopic(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryViewModel : IHotfixable
{
	public List`1 itemList; // 0x10
	public String focusTopicId; // 0x18
	public Int32 focusIndex; // 0x20
	public Int32 entrySequenceId; // 0x24
	public Boolean hasOnBattleTheme; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CheckIfTopicAccessible; // 0x8
	private static DelegateBridge __Hotfix0_SetFocusTopic; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x263207c VA: 0x7594c4a07c
	public Void LoadData() { }
	// RVA: 0x26326d8 VA: 0x7594c4a6d8
	public Boolean CheckIfTopicAccessible(String topicId) { }
	// RVA: 0x2632810 VA: 0x7594c4a810
	public Void SetFocusTopic(String topicId) { }
	// RVA: 0x2632a18 VA: 0x7594c4aa18
	public Void .ctor() { }
}
```