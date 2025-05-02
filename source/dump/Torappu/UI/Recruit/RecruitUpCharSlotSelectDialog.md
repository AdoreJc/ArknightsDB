# RecruitUpCharSlotSelectDialog

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `UIRenderTextureImage _blurBg`

- `RecruitUpCharSlotSelectDialogView _dialogView`

- `RectTransform _cancelBtn`

- `Options m_options`

- `RecruitUpCharSlotSelectViewProperty m_property`


## Methods

- `Void _EventOnSelectCharCardClick(Int32)`

- `Void _OpenChooseCharDialog(Int32, RecruitCharSlotCardDetail)`

- `Void _OnChooseCharFinished(Int32, String)`

- `Void _SendChoosePoolUpRequest(Dictionary`2)`

- `Void EventOnDetailBtnClick()`

- `Void EventOnDialogClose()`

- `Void EventOnConfirmBtnClick()`

- `Void <_SendChoosePoolUpRequest>b__11_0(ChoosePoolUpResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitUpCharSlotSelectDialog : UICustomDialog`1
{
	private UIRenderTextureImage _blurBg; // 0x68
	private RecruitUpCharSlotSelectDialogView _dialogView; // 0x70
	private RectTransform _cancelBtn; // 0x78
	private Options m_options; // 0x80
	private RecruitUpCharSlotSelectViewProperty m_property; // 0xb0
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0__EventOnSelectCharCardClick; // 0x10
	private static DelegateBridge __Hotfix0__OpenChooseCharDialog; // 0x18
	private static DelegateBridge __Hotfix0__OnChooseCharFinished; // 0x20
	private static DelegateBridge __Hotfix0__SendChoosePoolUpRequest; // 0x28
	private static DelegateBridge __Hotfix0_EventOnDetailBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnDialogClose; // 0x38
	private static DelegateBridge __Hotfix0_EventOnConfirmBtnClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x26fee08 VA: 0x7594d16e08
	protected override Void OnRender(Options options) { }
	// RVA: 0x26ff3e4 VA: 0x7594d173e4
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x26ff44c VA: 0x7594d1744c
	private Void _EventOnSelectCharCardClick(Int32 index) { }
	// RVA: 0x26ff5e4 VA: 0x7594d175e4
	private Void _OpenChooseCharDialog(Int32 index, RecruitCharSlotCardDetail charSlotCardDetail) { }
	// RVA: 0x26ff87c VA: 0x7594d1787c
	private Void _OnChooseCharFinished(Int32 index, String charId) { }
	// RVA: 0x26ffad8 VA: 0x7594d17ad8
	private Void _SendChoosePoolUpRequest(Dictionary`2 charDict) { }
	// RVA: 0x26ffce0 VA: 0x7594d17ce0
	public Void EventOnDetailBtnClick() { }
	// RVA: 0x26ffe50 VA: 0x7594d17e50
	public Void EventOnDialogClose() { }
	// RVA: 0x26ffed4 VA: 0x7594d17ed4
	public Void EventOnConfirmBtnClick() { }
	// RVA: 0x2700788 VA: 0x7594d18788
	public Void .ctor() { }
	// RVA: 0x27008c0 VA: 0x7594d188c0
	private Void <_SendChoosePoolUpRequest>b__11_0(ChoosePoolUpResponse response) { }
}
```