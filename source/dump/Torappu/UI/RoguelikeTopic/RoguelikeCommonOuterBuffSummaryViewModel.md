# RoguelikeCommonOuterBuffSummaryViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String topicId`

- `Int32 buffCount`

- `Int32 unlockCount`


## Methods

- `Void LoadData(String, RoguelikeCommonDevelopmentData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffSummaryViewModel : IHotfixable
{
	public String topicId; // 0x10
	public List`1 mergedItems; // 0x18
	public List`1 rawTextGroup; // 0x20
	public List`1 difficultyItems; // 0x28
	public Int32 buffCount; // 0x30
	public Int32 unlockCount; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x265f0bc VA: 0x7594c770bc
	public Void LoadData(String topic, RoguelikeCommonDevelopmentData developmentData) { }
	// RVA: 0x2666158 VA: 0x7594c7e158
	public Void .ctor() { }
}
```