# ActMultiV3StageListRewardDialog

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Image _imgItemIcon`

- `Image _imgItemIconSmall`

- `Image _imgSeasonIcon`

- `UIRenderTextureImage _blurBg`

- `Boolean m_inited`

- `ViewModel m_viewModel`

- `UICompDialogFinder m_dialogFinder`


## Methods

- `Void _InitIfNot()`

- `Void _Render()`

- `Void EventOnBackBtnClicked()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListRewardDialog : UICompDialog`1
{
	private Image _imgItemIcon; // 0x48
	private Image _imgItemIconSmall; // 0x50
	private Image _imgSeasonIcon; // 0x58
	private DiffItem[] _diffItems; // 0x60
	private UIRenderTextureImage _blurBg; // 0x68
	private Boolean m_inited; // 0x70
	private ViewModel m_viewModel; // 0x78
	private UICompDialogFinder m_dialogFinder; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x314befc VA: 0x7595763efc
	private Void _InitIfNot() { }
	// RVA: 0x314c078 VA: 0x7595764078
	protected override Void OnRender(Options input) { }
	// RVA: 0x314c620 VA: 0x7595764620
	private Void _Render() { }
	// RVA: 0x314cc08 VA: 0x7595764c08
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x314cc70 VA: 0x7595764c70
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x314cd44 VA: 0x7595764d44
	public Void .ctor() { }
	// RVA: 0x314cdd4 VA: 0x7595764dd4
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```