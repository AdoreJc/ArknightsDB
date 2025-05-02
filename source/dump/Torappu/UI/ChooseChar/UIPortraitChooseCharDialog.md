# UIPortraitChooseCharDialog

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `UIRenderTextureImage _imgBlur`

- `UIPortraitChooseCharGroupView _charGroupView`

- `UIPortraitChooseCharButtonView _buttonView`

- `RectTransform _backRt`

- `UIPortraitChooseCharProperty m_property`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnCancelClicked()`

- `Void _EventOnConfirmClicked()`

- `Void _EventOnCharCardClicked(String)`

- `Void _EventOnCharCardDetailClicked(String)`

- `Void _EventOnClearAllSelectClicked()`

- `Void _OnCloseDialog(Boolean)`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIPortraitChooseCharDialog : UICompDialog`1, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_CONFIRM_BTN_CLICKED; // 0x0
	public const Int32 ON_CANCEL_BTN_CLICKED; // 0x0
	public const Int32 ON_CHAR_CARD_CLICKED; // 0x0
	public const Int32 ON_CHAR_CARD_DETAIL_CLICKED; // 0x0
	public const Int32 ON_CLEAR_ALL_SELECT_CLICKED; // 0x0
	private UIRenderTextureImage _imgBlur; // 0x48
	private UIPortraitChooseCharGroupView _charGroupView; // 0x50
	private UIPortraitChooseCharButtonView _buttonView; // 0x58
	private RectTransform _backRt; // 0x60
	private UIPortraitChooseCharProperty m_property; // 0x68
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__EventOnCancelClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnConfirmClicked; // 0x28
	private static DelegateBridge __Hotfix0__EventOnCharCardClicked; // 0x30
	private static DelegateBridge __Hotfix0__EventOnCharCardDetailClicked; // 0x38
	private static DelegateBridge __Hotfix0__EventOnClearAllSelectClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnCloseDialog; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2c3e4a4 VA: 0x75952564a4
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2c3e50c VA: 0x759525650c
	protected override Void OnInit() { }
	// RVA: 0x2c3e664 VA: 0x7595256664
	protected override Void OnRender(Options input) { }
	// RVA: 0x2c3e8b0 VA: 0x75952568b0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2c3eab4 VA: 0x7595256ab4
	private Void _EventOnCancelClicked() { }
	// RVA: 0x2c3ea14 VA: 0x7595256a14
	private Void _EventOnConfirmClicked() { }
	// RVA: 0x2c3eb20 VA: 0x7595256b20
	private Void _EventOnCharCardClicked(String charId) { }
	// RVA: 0x2c3ecc4 VA: 0x7595256cc4
	private Void _EventOnCharCardDetailClicked(String charId) { }
	// RVA: 0x2c3edd0 VA: 0x7595256dd0
	private Void _EventOnClearAllSelectClicked() { }
	// RVA: 0x2c3eeb8 VA: 0x7595256eb8
	private Void _OnCloseDialog(Boolean isSubmit) { }
	// RVA: 0x2c3f040 VA: 0x7595257040
	public Void .ctor() { }
	// RVA: 0x2c3f1b4 VA: 0x75952571b4
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2c3f1bc VA: 0x75952571bc
	private Void <>xLuaBaseProxy_OnInit() { }
}
```