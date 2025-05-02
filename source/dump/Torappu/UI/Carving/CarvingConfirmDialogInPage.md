# CarvingConfirmDialogInPage

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIAnimationLocation _enterAnim`

- `UIRenderTextureImage _blurBg`

- `RectTransform _backRt`

- `Text _descText`

- `Text _cancelText`

- `Text _confirmText`

- `TwoStateToggle _confirmBgToggle`

- `Boolean m_isInited`

- `Tween m_enterAnim`


## Methods

- `Void OnCancelBtnClicked()`

- `Void OnConfirmBtnClicked()`

- `Void _InitIfNot()`

- `Void _Render(Option)`

- `Void _OnBackPressed()`

- `Void _GenerateEnterAnim()`

- `Void <>xLuaBaseProxy_OnDestroySubClass()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingConfirmDialogInPage : UICompDialog`1
{
	private UIAnimationLocation _enterAnim; // 0x48
	private UIRenderTextureImage _blurBg; // 0x58
	private RectTransform _backRt; // 0x60
	private Text _descText; // 0x68
	private Text _cancelText; // 0x70
	private Text _confirmText; // 0x78
	private TwoStateToggle _confirmBgToggle; // 0x80
	private Boolean m_isInited; // 0x88
	private Tween m_enterAnim; // 0x90
	private static DelegateBridge __Hotfix0_OnCancelBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0_OnConfirmBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroySubClass; // 0x18
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__Render; // 0x30
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0x38
	private static DelegateBridge __Hotfix0__GenerateEnterAnim; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2d8f574 VA: 0x75953a7574
	public Void OnCancelBtnClicked() { }
	// RVA: 0x2d8f66c VA: 0x75953a766c
	public Void OnConfirmBtnClicked() { }
	// RVA: 0x2d8f764 VA: 0x75953a7764
	protected override Void OnRender(Option options) { }
	// RVA: 0x2d8fa8c VA: 0x75953a7a8c
	protected override Void OnDestroySubClass() { }
	// RVA: 0x2d8fb28 VA: 0x75953a7b28
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2d8f894 VA: 0x75953a7894
	private Void _InitIfNot() { }
	// RVA: 0x2d8f998 VA: 0x75953a7998
	private Void _Render(Option options) { }
	// RVA: 0x2d8fce8 VA: 0x75953a7ce8
	private Void _OnBackPressed() { }
	// RVA: 0x2d8fb90 VA: 0x75953a7b90
	private Void _GenerateEnterAnim() { }
	// RVA: 0x2d8fd64 VA: 0x75953a7d64
	public Void .ctor() { }
	// RVA: 0x2d8fdf4 VA: 0x75953a7df4
	private Void <>xLuaBaseProxy_OnDestroySubClass() { }
	// RVA: 0x2d8fdfc VA: 0x75953a7dfc
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```