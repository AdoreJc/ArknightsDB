# DeepSeaRPTechTreeView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `GameObject _objSavePart`

- `CanvasGroup _canvasSavedPart`

- `UIAnimationLocation _enterAnim`

- `DeepSeaRPTechTreeViewModel m_viewModel`

- `Boolean m_inited`

- `FadeSwitchTween m_tweenSaved`

- `Action <onSaveClicked>k__BackingField`


## Properties

- `Action onSaveClicked`


## Methods

- `Void set_onTechSetClicked(Action`1)`

- `Void set_onTechUnSetClicked(Action`1)`

- `Void set_onTechActiveClicked(Action`1)`

- `Void set_onTechNodeToggleClicked(Action`1)`

- `Action get_onSaveClicked()`

- `Void set_onSaveClicked(Action)`

- `Void PlayEnterAnim()`

- `Void _InitIfNot()`

- `Void _EventOnActiveClick(String)`

- `Void _EventOnSetClick(String)`

- `Void _EventOnUnsetClick(String)`

- `Void _EventOnNodeToggleClick(String)`

- `Void EventOnSaveClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTechTreeView : DataBinder`1
{
	private List`1 _nodeList; // 0x20
	private GameObject _objSavePart; // 0x28
	private CanvasGroup _canvasSavedPart; // 0x30
	private UIAnimationLocation _enterAnim; // 0x38
	private DeepSeaRPTechTreeViewModel m_viewModel; // 0x48
	private Boolean m_inited; // 0x50
	private FadeSwitchTween m_tweenSaved; // 0x58
	private const Single DUR_SAVED_FADE_OUT; // 0x0
	private Action`1 <onTechSetClicked>k__BackingField; // 0x60
	private Action`1 <onTechUnSetClicked>k__BackingField; // 0x68
	private Action`1 <onTechActiveClicked>k__BackingField; // 0x70
	private Action`1 <onTechNodeToggleClicked>k__BackingField; // 0x78
	private Action <onSaveClicked>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_onTechSetClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onTechSetClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onTechUnSetClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onTechUnSetClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onTechActiveClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onTechActiveClicked; // 0x28
	private static DelegateBridge __Hotfix0_get_onTechNodeToggleClicked; // 0x30
	private static DelegateBridge __Hotfix0_set_onTechNodeToggleClicked; // 0x38
	private static DelegateBridge __Hotfix0_get_onSaveClicked; // 0x40
	private static DelegateBridge __Hotfix0_set_onSaveClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x60
	private static DelegateBridge __Hotfix0__EventOnActiveClick; // 0x68
	private static DelegateBridge __Hotfix0__EventOnSetClick; // 0x70
	private static DelegateBridge __Hotfix0__EventOnUnsetClick; // 0x78
	private static DelegateBridge __Hotfix0__EventOnNodeToggleClick; // 0x80
	private static DelegateBridge __Hotfix0_EventOnSaveClick; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	private Action`1 onTechSetClicked { get; set; }
	private Action`1 onTechUnSetClicked { get; set; }
	private Action`1 onTechActiveClicked { get; set; }
	private Action`1 onTechNodeToggleClicked { get; set; }
	private Action onSaveClicked { get; set; }

	// RVA: 0x29e4d7c VA: 0x7594ffcd7c
	private Action`1 get_onTechSetClicked() { }
	// RVA: 0x29e2a24 VA: 0x7594ffaa24
	public Void set_onTechSetClicked(Action`1 value) { }
	// RVA: 0x29e4de4 VA: 0x7594ffcde4
	private Action`1 get_onTechUnSetClicked() { }
	// RVA: 0x29e2aa8 VA: 0x7594ffaaa8
	public Void set_onTechUnSetClicked(Action`1 value) { }
	// RVA: 0x29e4e4c VA: 0x7594ffce4c
	private Action`1 get_onTechActiveClicked() { }
	// RVA: 0x29e29a0 VA: 0x7594ffa9a0
	public Void set_onTechActiveClicked(Action`1 value) { }
	// RVA: 0x29e4eb4 VA: 0x7594ffceb4
	private Action`1 get_onTechNodeToggleClicked() { }
	// RVA: 0x29e2b2c VA: 0x7594ffab2c
	public Void set_onTechNodeToggleClicked(Action`1 value) { }
	// RVA: 0x29e4f1c VA: 0x7594ffcf1c
	private Action get_onSaveClicked() { }
	// RVA: 0x29e291c VA: 0x7594ffa91c
	public Void set_onSaveClicked(Action value) { }
	// RVA: 0x29e4f84 VA: 0x7594ffcf84
	public override Void OnValueChanged(DeepSeaRPTechTreeViewProperty property) { }
	// RVA: 0x29e21f8 VA: 0x7594ffa1f8
	public Void PlayEnterAnim() { }
	// RVA: 0x29e532c VA: 0x7594ffd32c
	private Void _InitIfNot() { }
	// RVA: 0x29e5410 VA: 0x7594ffd410
	private Void _EventOnActiveClick(String techId) { }
	// RVA: 0x29e54c8 VA: 0x7594ffd4c8
	private Void _EventOnSetClick(String techId) { }
	// RVA: 0x29e5580 VA: 0x7594ffd580
	private Void _EventOnUnsetClick(String techId) { }
	// RVA: 0x29e5638 VA: 0x7594ffd638
	private Void _EventOnNodeToggleClick(String techId) { }
	// RVA: 0x29e56f0 VA: 0x7594ffd6f0
	public Void EventOnSaveClick() { }
	// RVA: 0x29e578c VA: 0x7594ffd78c
	public Void .ctor() { }
}
```