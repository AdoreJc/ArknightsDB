# ActMultiV3PrepareMainCharPickPanel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `UIAnimationLocation _entryAnim`

- `ActMultiV3PrepareMainCharPickChooseView _chooseView`

- `ActMultiV3PrepareMainCharPickReserveView _reserveView`

- `ActMultiV3PrepareMainCharPickGotAnimView _gotAnimView`

- `ActMultiV3PrepareMainCharPickPanelViewModelProperty m_prop`


## Methods

- `Void _InitIfNot()`

- `Void _HandlePickSucRet(Object)`

- `Void _EventOnSelectChar(Int32)`

- `Void _EvenOnSkip()`

- `Void _EventOnMyTurn()`

- `Void EventOnShowReserveList()`

- `Void EventOnHideReserveList()`

- `Boolean <PlayEntryAnimation>b__10_0()`

- `Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase)`

- `Void <>xLuaBaseProxy_OnVisible(Boolean)`

- `IEnumerator <>xLuaBaseProxy_PlayEntryAnimation()`

- `Void <>xLuaBaseProxy_OnStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainCharPickPanel : ActMultiV3PrepareMainStepPanelBase
{
	private UIAnimationLocation _entryAnim; // 0x38
	private ActMultiV3PrepareMainCharPickChooseView _chooseView; // 0x48
	private ActMultiV3PrepareMainCharPickReserveView _reserveView; // 0x50
	private ActMultiV3PrepareMainCharPickGotAnimView _gotAnimView; // 0x58
	private ActMultiV3PrepareMainCharPickPanelViewModelProperty m_prop; // 0x60
	private static DelegateBridge __Hotfix0_get_step; // 0x0
	private static DelegateBridge __Hotfix0_GetMainViewConfig; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge __Hotfix0_OnVisible; // 0x18
	private static DelegateBridge __Hotfix0_PlayEntryAnimation; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_OnStop; // 0x30
	private static DelegateBridge __Hotfix0__HandlePickSucRet; // 0x38
	private static DelegateBridge __Hotfix0__EventOnSelectChar; // 0x40
	private static DelegateBridge __Hotfix0__EvenOnSkip; // 0x48
	private static DelegateBridge __Hotfix0__EventOnMyTurn; // 0x50
	private static DelegateBridge __Hotfix0_EventOnShowReserveList; // 0x58
	private static DelegateBridge __Hotfix0_EventOnHideReserveList; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override ActMultiV3PrepareStepType step { get; }

	// RVA: 0x3166790 VA: 0x759577e790
	public override ActMultiV3PrepareStepType get_step() { }
	// RVA: 0x31667f8 VA: 0x759577e7f8
	public override ActMultiV3PrepareMainViewConfig GetMainViewConfig() { }
	// RVA: 0x3166864 VA: 0x759577e864
	protected override Void OnUpdate(ActMultiV3StepUpdateCase updateCase) { }
	// RVA: 0x3167168 VA: 0x759577f168
	protected override Void OnVisible(Boolean v) { }
	// RVA: 0x3167298 VA: 0x759577f298
	protected override IEnumerator PlayEntryAnimation() { }
	// RVA: 0x316694c VA: 0x759577e94c
	private Void _InitIfNot() { }
	// RVA: 0x31675e4 VA: 0x759577f5e4
	protected override Void OnStop() { }
	// RVA: 0x31676ec VA: 0x759577f6ec
	private Void _HandlePickSucRet(Object arg) { }
	// RVA: 0x31679c8 VA: 0x759577f9c8
	private Void _EventOnSelectChar(Int32 instId) { }
	// RVA: 0x3167aa4 VA: 0x759577faa4
	private Void _EvenOnSkip() { }
	// RVA: 0x3167b7c VA: 0x759577fb7c
	private Void _EventOnMyTurn() { }
	// RVA: 0x3167bf0 VA: 0x759577fbf0
	public Void EventOnShowReserveList() { }
	// RVA: 0x3167d70 VA: 0x759577fd70
	public Void EventOnHideReserveList() { }
	// RVA: 0x3167e38 VA: 0x759577fe38
	public Void .ctor() { }
	// RVA: 0x3167ea4 VA: 0x759577fea4
	private Boolean <PlayEntryAnimation>b__10_0() { }
	// RVA: 0x3167ed0 VA: 0x759577fed0
	private Void <>xLuaBaseProxy_OnUpdate(ActMultiV3StepUpdateCase P0) { }
	// RVA: 0x3167ed4 VA: 0x759577fed4
	private Void <>xLuaBaseProxy_OnVisible(Boolean P0) { }
	// RVA: 0x3167edc VA: 0x759577fedc
	private IEnumerator <>xLuaBaseProxy_PlayEntryAnimation() { }
	// RVA: 0x3167ee0 VA: 0x759577fee0
	private Void <>xLuaBaseProxy_OnStop() { }
}
```