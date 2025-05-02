# RL02OuterBuffDetailView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `TwoStateToggle _toggleButtonBannedText`

- `TwoStateToggle _toggleAllComplete`

- `GameObject _panelBtnCanUpgrade`

- `GameObject _panelBtnBanned`

- `GameObject _panelBtnNodeActivated`

- `Text _textProgress`

- `Text _textTokenCount`

- `Text _textTokenCost`

- `String _formatProgress`

- `String _formatNodeActivateCost`

- `Text _textNodeName`

- `Text _textNodeDesc`

- `Image _imgNodeIcon`

- `UIAnimationLocation _animLocation`

- `Single _animDuration`

- `Action <onNodeActivateClicked>k__BackingField`

- `Action <onSummaryClicked>k__BackingField`

- `AnimationSwitchTween m_switchTween`

- `RL02OuterBuffItemModel m_selectNode`

- `UIPage m_cachePage`


## Properties

- `Action onNodeActivateClicked`

- `Action onSummaryClicked`


## Methods

- `Action get_onNodeActivateClicked()`

- `Void set_onNodeActivateClicked(Action)`

- `Action get_onSummaryClicked()`

- `Void set_onSummaryClicked(Action)`

- `Void OnInit(UIPage)`

- `Void OnNodeActivateClicked()`

- `Void OnSummaryClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffDetailView : DataBinder`1, IHotfixable
{
	private TwoStateToggle _toggleButtonBannedText; // 0x20
	private TwoStateToggle _toggleAllComplete; // 0x28
	private GameObject _panelBtnCanUpgrade; // 0x30
	private GameObject _panelBtnBanned; // 0x38
	private GameObject _panelBtnNodeActivated; // 0x40
	private Text _textProgress; // 0x48
	private Text _textTokenCount; // 0x50
	private Text _textTokenCost; // 0x58
	private String _formatProgress; // 0x60
	private String _formatNodeActivateCost; // 0x68
	private Text _textNodeName; // 0x70
	private Text _textNodeDesc; // 0x78
	private Image _imgNodeIcon; // 0x80
	private UIAnimationLocation _animLocation; // 0x88
	private Single _animDuration; // 0x98
	private Action <onNodeActivateClicked>k__BackingField; // 0xa0
	private Action <onSummaryClicked>k__BackingField; // 0xa8
	private AnimationSwitchTween m_switchTween; // 0xb0
	private RL02OuterBuffItemModel m_selectNode; // 0xb8
	private UIPage m_cachePage; // 0xc0
	private static DelegateBridge __Hotfix0_get_onNodeActivateClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNodeActivateClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onSummaryClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onSummaryClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_OnNodeActivateClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnSummaryClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action onNodeActivateClicked { get; set; }
	private Action onSummaryClicked { get; set; }

	// RVA: 0x26c02b8 VA: 0x7594cd82b8
	private Action get_onNodeActivateClicked() { }
	// RVA: 0x26bb094 VA: 0x7594cd3094
	public Void set_onNodeActivateClicked(Action value) { }
	// RVA: 0x26c0320 VA: 0x7594cd8320
	private Action get_onSummaryClicked() { }
	// RVA: 0x26bb118 VA: 0x7594cd3118
	public Void set_onSummaryClicked(Action value) { }
	// RVA: 0x26bb19c VA: 0x7594cd319c
	public Void OnInit(UIPage page) { }
	// RVA: 0x26c0388 VA: 0x7594cd8388
	public override Void OnValueChanged(RL02OuterBuffProperty property) { }
	// RVA: 0x26c08f0 VA: 0x7594cd88f0
	public Void OnNodeActivateClicked() { }
	// RVA: 0x26c098c VA: 0x7594cd898c
	public Void OnSummaryClicked() { }
	// RVA: 0x26c0a28 VA: 0x7594cd8a28
	public Void .ctor() { }
}
```