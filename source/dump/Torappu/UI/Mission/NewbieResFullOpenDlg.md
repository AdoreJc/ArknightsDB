# NewbieResFullOpenDlg

**Namespace:** `Torappu.UI.Mission`


## Fields

- `RectTransform _backRt`

- `NewbieResFullOpenView _view`

- `UIRenderTextureImage _blurBkg`

- `NewbieResFullOpenProp m_prop`


## Methods

- `Void _EventOnClose()`

- `Void EventOnCloseClick()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class NewbieResFullOpenDlg : UICompDialog`1
{
	private RectTransform _backRt; // 0x48
	private NewbieResFullOpenView _view; // 0x50
	private UIRenderTextureImage _blurBkg; // 0x58
	private NewbieResFullOpenProp m_prop; // 0x60
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__EventOnClose; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCloseClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x273476c VA: 0x7594d4c76c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x27347d4 VA: 0x7594d4c7d4
	protected override Void OnInit() { }
	// RVA: 0x27348fc VA: 0x7594d4c8fc
	protected override Void OnRender(Input input) { }
	// RVA: 0x2734b44 VA: 0x7594d4cb44
	private Void _EventOnClose() { }
	// RVA: 0x2734c18 VA: 0x7594d4cc18
	public Void EventOnCloseClick() { }
	// RVA: 0x2734c80 VA: 0x7594d4cc80
	public Void .ctor() { }
	// RVA: 0x2734db8 VA: 0x7594d4cdb8
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2734dc0 VA: 0x7594d4cdc0
	private Void <>xLuaBaseProxy_OnInit() { }
}
```