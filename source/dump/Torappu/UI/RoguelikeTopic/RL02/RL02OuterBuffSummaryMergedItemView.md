# RL02OuterBuffSummaryMergedItemView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `Image _imgIcon`

- `Text _textTokenDesc`

- `Text _textValue`

- `CanvasGroup _canvasGroup`

- `Single _alphaUnlock`

- `Single _alphaLocked`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(String, RL02OuterBuffListMergedItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffSummaryMergedItemView : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private Text _textTokenDesc; // 0x20
	private Text _textValue; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	private Single _alphaUnlock; // 0x38
	private Single _alphaLocked; // 0x3c
	private UIPage <page>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private UIPage page { get; set; }

	// RVA: 0x26c47d0 VA: 0x7594cdc7d0
	private UIPage get_page() { }
	// RVA: 0x26c4550 VA: 0x7594cdc550
	public Void set_page(UIPage value) { }
	// RVA: 0x26c45d4 VA: 0x7594cdc5d4
	public Void Render(String topicId, RL02OuterBuffListMergedItemModel viewModel) { }
	// RVA: 0x26c48b8 VA: 0x7594cdc8b8
	public Void .ctor() { }
}
```