# ActMultiV3StageListInfoDialog

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _backPressRt`

- `SimpleLayoutContent _layoutModeItems`

- `UIRenderTextureImage _blurBg`

- `Boolean m_hasInited`

- `ViewModel m_viewModel`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void EventOnBackBtnClicked()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListInfoDialog : UICompDialog`1
{
	private RectTransform _backPressRt; // 0x48
	private SimpleLayoutContent _layoutModeItems; // 0x50
	private UIRenderTextureImage _blurBg; // 0x58
	private Boolean m_hasInited; // 0x60
	private ViewModel m_viewModel; // 0x68
	private Adapter m_adapter; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x314a20c VA: 0x759576220c
	private Void _InitIfNot() { }
	// RVA: 0x314a400 VA: 0x7595762400
	protected override Void OnRender(Options input) { }
	// RVA: 0x314a8a0 VA: 0x75957628a0
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x314a908 VA: 0x7595762908
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x314a9dc VA: 0x75957629dc
	public Void .ctor() { }
	// RVA: 0x314aa6c VA: 0x7595762a6c
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```