# ActMultiV3PrepareMainStepView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3PrepareStepType m_fromStep`

- `Coroutine m_switchItr`


## Methods

- `Void _CleanSwitchCoroutine()`

- `IEnumerator _DoSwitchStepPanel(ActMultiV3PrepareMainStepPanelBase, ActMultiV3PrepareMainStepPanelBase, ActMultiV3PrepareMainViewModel)`

- `Void _DoUpdatePanel(ActMultiV3PrepareMainStepPanelBase, ActMultiV3PrepareMainViewModel, ActMultiV3StepUpdateCase)`

- `Void InitIfNot(ActMultiV3PrepareMainState)`

- `ActMultiV3PrepareMainViewConfig GetMainViewConfig(ActMultiV3PrepareMainViewModelProperty)`

- `Void DoBackAction()`

- `Void UpdatePing(Int32)`

- `Void Stop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainStepView : ActMultiV3PrepareMainViewBase, IPingListener
{
	private ActMultiV3PrepareMainStepPanelBase[] _stepPrefabs; // 0x20
	private List`1 m_stepPanels; // 0x28
	private ActMultiV3PrepareStepType m_fromStep; // 0x30
	private Coroutine m_switchItr; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__CleanSwitchCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__DoSwitchStepPanel; // 0x10
	private static DelegateBridge __Hotfix0__DoUpdatePanel; // 0x18
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_GetMainViewConfig; // 0x28
	private static DelegateBridge __Hotfix0_DoBackAction; // 0x30
	private static DelegateBridge __Hotfix0_UpdatePing; // 0x38
	private static DelegateBridge __Hotfix0_Stop; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3165094 VA: 0x759577d094
	public override Void OnValueChanged(ActMultiV3PrepareMainViewModelProperty property) { }
	// RVA: 0x3165368 VA: 0x759577d368
	private Void _CleanSwitchCoroutine() { }
	// RVA: 0x31653fc VA: 0x759577d3fc
	private IEnumerator _DoSwitchStepPanel(ActMultiV3PrepareMainStepPanelBase from, ActMultiV3PrepareMainStepPanelBase to, ActMultiV3PrepareMainViewModel model) { }
	// RVA: 0x3165508 VA: 0x759577d508
	private Void _DoUpdatePanel(ActMultiV3PrepareMainStepPanelBase panel, ActMultiV3PrepareMainViewModel model, ActMultiV3StepUpdateCase updateCase) { }
	// RVA: 0x31586f8 VA: 0x75957706f8
	public Void InitIfNot(ActMultiV3PrepareMainState hostState) { }
	// RVA: 0x31592ec VA: 0x75957712ec
	public ActMultiV3PrepareMainViewConfig GetMainViewConfig(ActMultiV3PrepareMainViewModelProperty prop) { }
	// RVA: 0x315ac34 VA: 0x7595772c34
	public Void DoBackAction() { }
	// RVA: 0x31656f0 VA: 0x759577d6f0
	public Void UpdatePing(Int32 ping) { }
	// RVA: 0x3158368 VA: 0x7595770368
	public Void Stop() { }
	// RVA: 0x316585c VA: 0x759577d85c
	public Void .ctor() { }
}
```