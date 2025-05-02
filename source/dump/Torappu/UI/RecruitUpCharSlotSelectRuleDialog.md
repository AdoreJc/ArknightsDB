# RecruitUpCharSlotSelectRuleDialog

**Namespace:** `Torappu.UI`


## Fields

- `Text _poolTypeText`

- `Text _poolRuleText`

- `UIRenderTextureImage _blurImage`

- `Options m_options`


## Methods

- `Void EventOnDialogClose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class RecruitUpCharSlotSelectRuleDialog : UICustomDialog`1
{
	private Text _poolTypeText; // 0x50
	private Text _poolRuleText; // 0x58
	private UIRenderTextureImage _blurImage; // 0x60
	private Options m_options; // 0x68
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0_IncludeNotificationCamaraForBlur; // 0x10
	private static DelegateBridge __Hotfix0_EventOnDialogClose; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x227ec88 VA: 0x7594896c88
	protected override Void OnRender(Options options) { }
	// RVA: 0x227ee80 VA: 0x7594896e80
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x227eee8 VA: 0x7594896ee8
	protected override Boolean IncludeNotificationCamaraForBlur() { }
	// RVA: 0x227ef50 VA: 0x7594896f50
	public Void EventOnDialogClose() { }
	// RVA: 0x227efd4 VA: 0x7594896fd4
	public Void .ctor() { }
}
```