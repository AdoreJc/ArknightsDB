# RL02OuterBuffSummaryView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `RL02OuterBuffSummaryMergedGroupView _mergedBuffView`

- `RL02OuterBuffSummaryRawTextNodeGroupView _rawTextNodeNodeBuffView`

- `Text _textProgress`

- `String _formatProgress`

- `RectTransform _backBtnRaycast`

- `Action <onBackBtnClicked>k__BackingField`


## Properties

- `Action onBackBtnClicked`


## Methods

- `Action get_onBackBtnClicked()`

- `Void set_onBackBtnClicked(Action)`

- `Void OnInit(UIPage)`

- `Void OnBackClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffSummaryView : DataBinder`1, IHotfixable
{
	private RL02OuterBuffSummaryMergedGroupView _mergedBuffView; // 0x20
	private RL02OuterBuffSummaryRawTextNodeGroupView _rawTextNodeNodeBuffView; // 0x28
	private Text _textProgress; // 0x30
	private String _formatProgress; // 0x38
	private RectTransform _backBtnRaycast; // 0x40
	private Action <onBackBtnClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onBackBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onBackBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action onBackBtnClicked { get; set; }

	// RVA: 0x26c59a4 VA: 0x7594cdd9a4
	private Action get_onBackBtnClicked() { }
	// RVA: 0x26bb2a4 VA: 0x7594cd32a4
	public Void set_onBackBtnClicked(Action value) { }
	// RVA: 0x26bb328 VA: 0x7594cd3328
	public Void OnInit(UIPage page) { }
	// RVA: 0x26c5a0c VA: 0x7594cdda0c
	public override Void OnValueChanged(RL02OuterBuffListProperty property) { }
	// RVA: 0x26c5b40 VA: 0x7594cddb40
	public Void OnBackClicked() { }
	// RVA: 0x26c5bdc VA: 0x7594cddbdc
	public Void .ctor() { }
}
```