# GuideMissionRewardPreviewDlg

**Namespace:** `Torappu.UI.Mission`


## Fields

- `RectTransform _backRt`

- `UIRenderTextureImage _blurBkg`

- `GuideMissionRewardPreview _view`

- `GuideMissionRewardPreviewProp m_prop`


## Methods

- `Void _EventOnClose()`

- `Void EventOnCloseClick()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class GuideMissionRewardPreviewDlg : UICompDialog`1
{
	private RectTransform _backRt; // 0x48
	private UIRenderTextureImage _blurBkg; // 0x50
	private GuideMissionRewardPreview _view; // 0x58
	private GuideMissionRewardPreviewProp m_prop; // 0x60
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__EventOnClose; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCloseClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2733434 VA: 0x7594d4b434
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x273349c VA: 0x7594d4b49c
	protected override Void OnInit() { }
	// RVA: 0x27335c4 VA: 0x7594d4b5c4
	protected override Void OnRender(Input input) { }
	// RVA: 0x273398c VA: 0x7594d4b98c
	private Void _EventOnClose() { }
	// RVA: 0x2733a60 VA: 0x7594d4ba60
	public Void EventOnCloseClick() { }
	// RVA: 0x2733ac8 VA: 0x7594d4bac8
	public Void .ctor() { }
	// RVA: 0x2733c00 VA: 0x7594d4bc00
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2733c08 VA: 0x7594d4bc08
	private Void <>xLuaBaseProxy_OnInit() { }
}
```