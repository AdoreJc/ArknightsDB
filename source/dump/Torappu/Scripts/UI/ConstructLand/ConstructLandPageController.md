# ConstructLandPageController

**Namespace:** `Torappu.Scripts.UI.ConstructLand`


## Fields

- `ConstructDetailedView _detailedView`

- `ConstructLandConfirmRepairDeco _repairDeco`

- `ConstructLandPage m_page`

- `Boolean m_inited`


## Methods

- `Void Init(ConstructLandPage)`

- `Void _OnSaveBtnClicked(Object)`

- `Void _OnResetBtnClicked(Object)`

- `Void _OnLeavePageBtnClicked(Object)`

- `Void _OnRepairAllBtnClicked()`

- `Void _OnToCraftBtnClicked(Object)`

- `Boolean _NeedSendSaveRequest()`

- `Void _OpenBuildingPage()`

- `Void _DoRepairAll()`

- `Void _DoSaveAndExit()`

- `Void _DoCancelExit()`

- `Void _DoSaveAndOpenBuildPage()`

- `Void _DoSendSaveRequest(Action`1)`

- `Void _OnSaveRespondAndToast(SandboxV2ConstructOperationResponse)`

- `Void _OnSaveRespondAndExit(SandboxV2ConstructOperationResponse)`

- `Void _OnSaveRespondAndOpenBuildPage(SandboxV2ConstructOperationResponse)`

- `Void _DoSave()`

- `Void _OnDetailedToggleClicked(Boolean)`

- `Void OnTipClicked(SandboxV2ConstructTipType)`

- `Void <_OnResetBtnClicked>b__9_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.ConstructLand
public class ConstructLandPageController : DataBinder`1
{
	private ConstructDetailedView _detailedView; // 0x20
	private ConstructLandConfirmRepairDeco _repairDeco; // 0x28
	private ConstructLandPage m_page; // 0x30
	private Boolean m_inited; // 0x38
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnSaveBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnResetBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnLeavePageBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnRepairAllBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnToCraftBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__NeedSendSaveRequest; // 0x40
	private static DelegateBridge __Hotfix0__OpenBuildingPage; // 0x48
	private static DelegateBridge __Hotfix0__DoRepairAll; // 0x50
	private static DelegateBridge __Hotfix0__DoSaveAndExit; // 0x58
	private static DelegateBridge __Hotfix0__DoCancelExit; // 0x60
	private static DelegateBridge __Hotfix0__DoSaveAndOpenBuildPage; // 0x68
	private static DelegateBridge __Hotfix0__DoSendSaveRequest; // 0x70
	private static DelegateBridge __Hotfix0__OnSaveRespondAndToast; // 0x78
	private static DelegateBridge __Hotfix0__OnSaveRespondAndExit; // 0x80
	private static DelegateBridge __Hotfix0__OnSaveRespondAndOpenBuildPage; // 0x88
	private static DelegateBridge __Hotfix0__DoSave; // 0x90
	private static DelegateBridge __Hotfix0__OnDetailedToggleClicked; // 0x98
	private static DelegateBridge __Hotfix0_OnTipClicked; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public EventPool`1 eventPool { get; }

	// RVA: 0x3774664 VA: 0x7595d8c664
	public EventPool`1 get_eventPool() { }
	// RVA: 0x377267c VA: 0x7595d8a67c
	public Void Init(ConstructLandPage page) { }
	// RVA: 0x37746e0 VA: 0x7595d8c6e0
	public override Void OnValueChanged(ConstructLandPageProp property) { }
	// RVA: 0x37747ac VA: 0x7595d8c7ac
	private Void _OnSaveBtnClicked(Object arg) { }
	// RVA: 0x3774c40 VA: 0x7595d8cc40
	private Void _OnResetBtnClicked(Object arg) { }
	// RVA: 0x3774edc VA: 0x7595d8cedc
	private Void _OnLeavePageBtnClicked(Object arg) { }
	// RVA: 0x3775218 VA: 0x7595d8d218
	private Void _OnRepairAllBtnClicked() { }
	// RVA: 0x3775554 VA: 0x7595d8d554
	private Void _OnToCraftBtnClicked(Object arg) { }
	// RVA: 0x3774920 VA: 0x7595d8c920
	private Boolean _NeedSendSaveRequest() { }
	// RVA: 0x3775838 VA: 0x7595d8d838
	private Void _OpenBuildingPage() { }
	// RVA: 0x3775af0 VA: 0x7595d8daf0
	private Void _DoRepairAll() { }
	// RVA: 0x3775bb8 VA: 0x7595d8dbb8
	private Void _DoSaveAndExit() { }
	// RVA: 0x3775c70 VA: 0x7595d8dc70
	private Void _DoCancelExit() { }
	// RVA: 0x3775cf0 VA: 0x7595d8dcf0
	private Void _DoSaveAndOpenBuildPage() { }
	// RVA: 0x3774a3c VA: 0x7595d8ca3c
	private Void _DoSendSaveRequest(Action`1 onProceed) { }
	// RVA: 0x3775da8 VA: 0x7595d8dda8
	private Void _OnSaveRespondAndToast(SandboxV2ConstructOperationResponse response) { }
	// RVA: 0x3775f60 VA: 0x7595d8df60
	private Void _OnSaveRespondAndExit(SandboxV2ConstructOperationResponse response) { }
	// RVA: 0x3775fec VA: 0x7595d8dfec
	private Void _OnSaveRespondAndOpenBuildPage(SandboxV2ConstructOperationResponse response) { }
	// RVA: 0x3775ea0 VA: 0x7595d8dea0
	private Void _DoSave() { }
	// RVA: 0x3776070 VA: 0x7595d8e070
	private Void _OnDetailedToggleClicked(Boolean isOn) { }
	// RVA: 0x37761cc VA: 0x7595d8e1cc
	public Void OnTipClicked(SandboxV2ConstructTipType tips) { }
	// RVA: 0x37762d0 VA: 0x7595d8e2d0
	public Void .ctor() { }
	// RVA: 0x3776360 VA: 0x7595d8e360
	private Void <_OnResetBtnClicked>b__9_0() { }
}
```