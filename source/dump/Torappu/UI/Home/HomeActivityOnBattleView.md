# HomeActivityOnBattleView

**Namespace:** `Torappu.UI.Home`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `ActivityOnBattleViewModel m_viewModel`

- `Adapter m_contentAdapter`


## Methods

- `Void set_onJumpToActivityClicked(Action`1)`

- `Void set_onJumpToCrisisV2Clicked(Action`1)`

- `Void set_onJumpToRoguelikeClicked(Action`1)`

- `Void set_onJumpToMainlineClicked(Action`1)`

- `Void set_onJumpToSandboxPermClicked(Action`1)`

- `Void _InitIfNot()`

- `Void _OnActivityClicked(String)`

- `Void _OnCrisisSeasonClicked(String)`

- `Void _OnRoguelikeClicked(String)`

- `Void _OnCrisisV2Clicked(String)`

- `Void _OnMainlineClicked(String)`

- `Void _OnSandboxPermClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeActivityOnBattleView : DataBinder`1
{
	private SimpleLayoutContent _content; // 0x20
	private Boolean m_isInited; // 0x28
	private ActivityOnBattleViewModel m_viewModel; // 0x30
	private Adapter m_contentAdapter; // 0x38
	private Action`1 <onJumpToActivityClicked>k__BackingField; // 0x40
	private Action`1 <onJumpToCrisisV2Clicked>k__BackingField; // 0x48
	private Action`1 <onJumpToRoguelikeClicked>k__BackingField; // 0x50
	private Action`1 <onJumpToMainlineClicked>k__BackingField; // 0x58
	private Action`1 <onJumpToSandboxPermClicked>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onJumpToActivityClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onJumpToActivityClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onJumpToCrisisV2Clicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onJumpToCrisisV2Clicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onJumpToRoguelikeClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onJumpToRoguelikeClicked; // 0x28
	private static DelegateBridge __Hotfix0_get_onJumpToMainlineClicked; // 0x30
	private static DelegateBridge __Hotfix0_set_onJumpToMainlineClicked; // 0x38
	private static DelegateBridge __Hotfix0_get_onJumpToSandboxPermClicked; // 0x40
	private static DelegateBridge __Hotfix0_set_onJumpToSandboxPermClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__OnActivityClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnCrisisSeasonClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnRoguelikeClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnCrisisV2Clicked; // 0x78
	private static DelegateBridge __Hotfix0__OnMainlineClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnSandboxPermClicked; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	private Action`1 onJumpToActivityClicked { get; set; }
	private Action`1 onJumpToCrisisV2Clicked { get; set; }
	private Action`1 onJumpToRoguelikeClicked { get; set; }
	private Action`1 onJumpToMainlineClicked { get; set; }
	private Action`1 onJumpToSandboxPermClicked { get; set; }

	// RVA: 0x2831e84 VA: 0x7594e49e84
	private Action`1 get_onJumpToActivityClicked() { }
	// RVA: 0x2831eec VA: 0x7594e49eec
	public Void set_onJumpToActivityClicked(Action`1 value) { }
	// RVA: 0x2831f70 VA: 0x7594e49f70
	private Action`1 get_onJumpToCrisisV2Clicked() { }
	// RVA: 0x2831fd8 VA: 0x7594e49fd8
	public Void set_onJumpToCrisisV2Clicked(Action`1 value) { }
	// RVA: 0x283205c VA: 0x7594e4a05c
	private Action`1 get_onJumpToRoguelikeClicked() { }
	// RVA: 0x28320c4 VA: 0x7594e4a0c4
	public Void set_onJumpToRoguelikeClicked(Action`1 value) { }
	// RVA: 0x2832148 VA: 0x7594e4a148
	private Action`1 get_onJumpToMainlineClicked() { }
	// RVA: 0x28321b0 VA: 0x7594e4a1b0
	public Void set_onJumpToMainlineClicked(Action`1 value) { }
	// RVA: 0x2832234 VA: 0x7594e4a234
	private Action`1 get_onJumpToSandboxPermClicked() { }
	// RVA: 0x283229c VA: 0x7594e4a29c
	public Void set_onJumpToSandboxPermClicked(Action`1 value) { }
	// RVA: 0x2832320 VA: 0x7594e4a320
	public override Void OnValueChanged(ActivityOnBattleViewProperty property) { }
	// RVA: 0x28323ec VA: 0x7594e4a3ec
	private Void _InitIfNot() { }
	// RVA: 0x2832550 VA: 0x7594e4a550
	private Void _OnActivityClicked(String activityId) { }
	// RVA: 0x2832618 VA: 0x7594e4a618
	private Void _OnCrisisSeasonClicked(String seasonId) { }
	// RVA: 0x28326e0 VA: 0x7594e4a6e0
	private Void _OnRoguelikeClicked(String topicId) { }
	// RVA: 0x28327a8 VA: 0x7594e4a7a8
	private Void _OnCrisisV2Clicked(String topicId) { }
	// RVA: 0x2832870 VA: 0x7594e4a870
	private Void _OnMainlineClicked(String topicId) { }
	// RVA: 0x2832938 VA: 0x7594e4a938
	private Void _OnSandboxPermClicked(String topicId) { }
	// RVA: 0x2832a00 VA: 0x7594e4aa00
	public Void .ctor() { }
}
```