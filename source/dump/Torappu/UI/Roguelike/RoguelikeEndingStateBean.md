# RoguelikeEndingStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeEndingViewModel viewModel`

- `String topicId`

- `RoguelikeTopicMode mode`


## Methods

- `Void LoadData(RoguelikeEndingControllerBase)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeEndingStateBean : IStateBean, IHotfixable
{
	public RoguelikeEndingViewModel viewModel; // 0x10
	public String topicId; // 0x18
	public RoguelikeTopicMode mode; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2a30d38 VA: 0x7595048d38
	public Void LoadData(RoguelikeEndingControllerBase controller) { }
	// RVA: 0x2a318a0 VA: 0x75950498a0
	public Void .ctor() { }
}
```