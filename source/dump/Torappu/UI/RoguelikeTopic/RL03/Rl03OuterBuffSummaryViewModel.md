# Rl03OuterBuffSummaryViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `String topicId`

- `Int32 buffCount`

- `Int32 unlockCount`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffSummaryViewModel : IHotfixable
{
	public String topicId; // 0x10
	public List`1 mergedItems; // 0x18
	public List`1 rawTextGroup; // 0x20
	public List`1 difficultyItems; // 0x28
	public Int32 buffCount; // 0x30
	public Int32 unlockCount; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x26a8adc VA: 0x7594cc0adc
	public Void LoadData(String topic) { }
	// RVA: 0x26af5d0 VA: 0x7594cc75d0
	public Void .ctor() { }
}
```