# RL02OuterBuffListModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `String topicId`

- `Int32 buffCount`

- `Int32 unlockCount`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffListModel : IHotfixable
{
	public List`1 mergedItems; // 0x10
	public List`1 rawTextGroup; // 0x18
	public String topicId; // 0x20
	public Int32 buffCount; // 0x28
	public Int32 unlockCount; // 0x2c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x26bc0b4 VA: 0x7594cd40b4
	public Void LoadData() { }
	// RVA: 0x26c6690 VA: 0x7594cde690
	public Void .ctor() { }
}
```