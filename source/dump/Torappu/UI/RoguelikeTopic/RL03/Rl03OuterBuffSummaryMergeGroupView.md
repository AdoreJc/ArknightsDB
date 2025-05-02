# Rl03OuterBuffSummaryMergeGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Rl03OuterBuffSummaryMergeItemView _leftItem`

- `Rl03OuterBuffSummaryMergeItemView _rightItem`

- `GameObject _panelLeft`

- `GameObject _panelRight`

- `GameObject _back`


## Methods

- `Void Render(String, Rl03OuterBuffSummaryMergedItemModel, Rl03OuterBuffSummaryMergedItemModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffSummaryMergeGroupView : MonoBehaviour, IHotfixable
{
	private Rl03OuterBuffSummaryMergeItemView _leftItem; // 0x18
	private Rl03OuterBuffSummaryMergeItemView _rightItem; // 0x20
	private GameObject _panelLeft; // 0x28
	private GameObject _panelRight; // 0x30
	private GameObject _back; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x26ad3c4 VA: 0x7594cc53c4
	public Void Render(String topicId, Rl03OuterBuffSummaryMergedItemModel leftModel, Rl03OuterBuffSummaryMergedItemModel rightModel, Boolean hasBack) { }
	// RVA: 0x26ad6d0 VA: 0x7594cc56d0
	public Void .ctor() { }
}
```