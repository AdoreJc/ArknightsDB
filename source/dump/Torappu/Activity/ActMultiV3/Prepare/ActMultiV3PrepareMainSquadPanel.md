# ActMultiV3PrepareMainSquadPanel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `UIAnimationLocation _entryAnim`

- `ActMultiV3PrepareMainSquadPanelMainView _mainView`

- `ActMultiV3PrepareMainSquadPanelSysAllocView _sysAllocView`

- `Transform _procViewContainer`

- `ActMultiV3PrepareMainSquadPanelViewModelProperty m_prop`


## Methods

- `Void _InitIfNot()`

- `ActMultiV3PrepareMainViewConfig _GetMainViewConfigByProc(ActMultiV3PrepareMainSquadProc)`

- `Void _HandleSetCharSuc(Object)`

- `Void _HandleSaveSquadSuc(Object)`

- `Void SetCharInSquad(Int32, Boolean)`

- `Void CheckReserveVisible()`

- `Void SetReady(Boolean)`

- `Void ToNextProc()`

- `Void JumpToEndProc()`

- `Void SaveSquad()`

- `Void _SaveSquadImpl(Boolean)`

- `Void SetCharSkill(Int32, String)`

- `Void SetCharEquip(Int32, String)`

- `Void SwitchShowSkill()`

- `Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase)`

- `Void <>xLuaBaseProxy_OnVisible(Boolean)`

- `Void <>xLuaBaseProxy_OnEmergency()`

- `IEnumerator <>xLuaBaseProxy_PlayEntryAnimation()`

- `Boolean <>xLuaBaseProxy_DoBackAction()`

- `Void <>xLuaBaseProxy_OnStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSquadPanel : ActMultiV3PrepareMainStepPanelBase, IActMultiV3PrepareMainSquadPanelProcEvent
{
	private UIAnimationLocation _entryAnim; // 0x38
	private ActMultiV3PrepareMainSquadPanelMainView _mainView; // 0x48
	private ActMultiV3PrepareMainSquadPanelSysAllocView _sysAllocView; // 0x50
	private ActMultiV3PrepareMainSquadPanelProcViewBase[] _procViewPrefab; // 0x58
	private Transform _procViewContainer; // 0x60
	private ActMultiV3PrepareMainSquadPanelViewModelProperty m_prop; // 0x68
	private List`1 m_procViews; // 0x70
	private static DelegateBridge __Hotfix0_GetMainViewConfig; // 0x0
	private static DelegateBridge __Hotfix0_get_step; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge __Hotfix0_OnVisible; // 0x18
	private static DelegateBridge __Hotfix0_OnEmergency; // 0x20
	private static DelegateBridge __Hotfix0_PlayEntryAnimation; // 0x28
	private static DelegateBridge __Hotfix0_DoBackAction; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_OnStop; // 0x40
	private static DelegateBridge __Hotfix0__GetMainViewConfigByProc; // 0x48
	private static DelegateBridge __Hotfix0__HandleSetCharSuc; // 0x50
	private static DelegateBridge __Hotfix0__HandleSaveSquadSuc; // 0x58
	private static DelegateBridge __Hotfix0_SetCharInSquad; // 0x60
	private static DelegateBridge __Hotfix0_CheckReserveVisible; // 0x68
	private static DelegateBridge __Hotfix0_SetReady; // 0x70
	private static DelegateBridge __Hotfix0_ToNextProc; // 0x78
	private static DelegateBridge __Hotfix0_JumpToEndProc; // 0x80
	private static DelegateBridge __Hotfix0_SaveSquad; // 0x88
	private static DelegateBridge __Hotfix0__SaveSquadImpl; // 0x90
	private static DelegateBridge __Hotfix0_SetCharSkill; // 0x98
	private static DelegateBridge __Hotfix0_SetCharEquip; // 0xa0
	private static DelegateBridge __Hotfix0_SwitchShowSkill; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public override ActMultiV3PrepareStepType step { get; }

	// RVA: 0x316dc6c VA: 0x7595785c6c
	public override ActMultiV3PrepareMainViewConfig GetMainViewConfig() { }
	// RVA: 0x316de14 VA: 0x7595785e14
	public override ActMultiV3PrepareStepType get_step() { }
	// RVA: 0x316de7c VA: 0x7595785e7c
	protected override Void OnUpdate(ActMultiV3StepUpdateCase updateCase) { }
	// RVA: 0x316efc0 VA: 0x7595786fc0
	protected override Void OnVisible(Boolean v) { }
	// RVA: 0x316f250 VA: 0x7595787250
	protected override Void OnEmergency() { }
	// RVA: 0x316f440 VA: 0x7595787440
	protected override IEnumerator PlayEntryAnimation() { }
	// RVA: 0x316f514 VA: 0x7595787514
	public override Boolean DoBackAction() { }
	// RVA: 0x316df64 VA: 0x7595785f64
	private Void _InitIfNot() { }
	// RVA: 0x316fa3c VA: 0x7595787a3c
	protected override Void OnStop() { }
	// RVA: 0x316dd14 VA: 0x7595785d14
	private ActMultiV3PrepareMainViewConfig _GetMainViewConfigByProc(ActMultiV3PrepareMainSquadProc proc) { }
	// RVA: 0x316fbbc VA: 0x7595787bbc
	private Void _HandleSetCharSuc(Object arg) { }
	// RVA: 0x316ffc4 VA: 0x7595787fc4
	private Void _HandleSaveSquadSuc(Object arg) { }
	// RVA: 0x3170188 VA: 0x7595788188
	public Void SetCharInSquad(Int32 instId, Boolean inSquad) { }
	// RVA: 0x31703d0 VA: 0x75957883d0
	public Void CheckReserveVisible() { }
	// RVA: 0x31704f0 VA: 0x75957884f0
	public Void SetReady(Boolean isReady) { }
	// RVA: 0x31705d0 VA: 0x75957885d0
	public Void ToNextProc() { }
	// RVA: 0x31706ac VA: 0x75957886ac
	public Void JumpToEndProc() { }
	// RVA: 0x31707f4 VA: 0x75957887f4
	public Void SaveSquad() { }
	// RVA: 0x316f318 VA: 0x7595787318
	private Void _SaveSquadImpl(Boolean isEmergency) { }
	// RVA: 0x31708e4 VA: 0x75957888e4
	public Void SetCharSkill(Int32 instId, String skillId) { }
	// RVA: 0x3170a74 VA: 0x7595788a74
	public Void SetCharEquip(Int32 instId, String equipId) { }
	// RVA: 0x3170c04 VA: 0x7595788c04
	public Void SwitchShowSkill() { }
	// RVA: 0x3170d28 VA: 0x7595788d28
	public Void .ctor() { }
	// RVA: 0x3170d98 VA: 0x7595788d98
	private Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase P0) { }
	// RVA: 0x3170da0 VA: 0x7595788da0
	private Void <>xLuaBaseProxy_OnVisible(Boolean P0) { }
	// RVA: 0x3170dac VA: 0x7595788dac
	private Void <>xLuaBaseProxy_OnEmergency() { }
	// RVA: 0x3170db4 VA: 0x7595788db4
	private IEnumerator <>xLuaBaseProxy_PlayEntryAnimation() { }
	// RVA: 0x3170dbc VA: 0x7595788dbc
	private Boolean <>xLuaBaseProxy_DoBackAction() { }
	// RVA: 0x3170dc4 VA: 0x7595788dc4
	private Void <>xLuaBaseProxy_OnStop() { }
}
```