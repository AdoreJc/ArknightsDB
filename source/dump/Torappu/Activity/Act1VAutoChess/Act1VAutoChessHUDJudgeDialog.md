# Act1VAutoChessHUDJudgeDialog

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _desc`

- `Text _confirmDesc`

- `Text _cancelDesc`

- `UIRenderTextureImage _blurImage`

- `Button _btnNegative`

- `GameObject _panelCheckBox`

- `Text _checkBoxMsgText`

- `CanvasGroup _checkBox`

- `Boolean m_checkBoxChecked`

- `Boolean m_haveCheckBox`

- `Action m_onCheckBoxConfirm`

- `FadeSwitchTween m_checkBoxFade`


## Methods

- `Void OnCheckboxClick()`

- `Void OnConfirm()`

- `Void OnCancel()`

- `Void _OnCancelImpl()`

- `Void _ConfirmCheckBox()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Boolean <>xLuaBaseProxy_IgnoreTimeScale()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDJudgeDialog : UICompDialog`1
{
	private Text _desc; // 0x48
	private Text _confirmDesc; // 0x50
	private Text _cancelDesc; // 0x58
	private UIRenderTextureImage _blurImage; // 0x60
	private Button _btnNegative; // 0x68
	private GameObject _panelCheckBox; // 0x70
	private Text _checkBoxMsgText; // 0x78
	private CanvasGroup _checkBox; // 0x80
	public static Int32 CANCEL; // 0x0
	public static Int32 CONFIRM; // 0x4
	private Boolean m_checkBoxChecked; // 0x88
	private Boolean m_haveCheckBox; // 0x89
	private Action m_onCheckBoxConfirm; // 0x90
	private FadeSwitchTween m_checkBoxFade; // 0x98
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0_IgnoreTimeScale; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x20
	private static DelegateBridge __Hotfix0_OnCheckboxClick; // 0x28
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x30
	private static DelegateBridge __Hotfix0_OnCancel; // 0x38
	private static DelegateBridge __Hotfix0__OnCancelImpl; // 0x40
	private static DelegateBridge __Hotfix0__ConfirmCheckBox; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x33790a4 VA: 0x75959910a4
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x337911c VA: 0x759599111c
	protected override Boolean IgnoreTimeScale() { }
	// RVA: 0x3379194 VA: 0x7595991194
	protected override Void OnInit() { }
	// RVA: 0x3379318 VA: 0x7595991318
	protected override Void OnRender(Params input) { }
	// RVA: 0x337952c VA: 0x759599152c
	public Void OnCheckboxClick() { }
	// RVA: 0x337963c VA: 0x759599163c
	public Void OnConfirm() { }
	// RVA: 0x33797f0 VA: 0x75959917f0
	public Void OnCancel() { }
	// RVA: 0x3379868 VA: 0x7595991868
	private Void _OnCancelImpl() { }
	// RVA: 0x3379748 VA: 0x7595991748
	private Void _ConfirmCheckBox() { }
	// RVA: 0x337996c VA: 0x759599196c
	public Void .ctor() { }
	// RVA: 0x3379a0c VA: 0x7595991a0c
	private static Void .cctor() { }
	// RVA: 0x3379a5c VA: 0x7595991a5c
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x3379a64 VA: 0x7595991a64
	private Boolean <>xLuaBaseProxy_IgnoreTimeScale() { }
	// RVA: 0x3379a6c VA: 0x7595991a6c
	private Void <>xLuaBaseProxy_OnInit() { }
}
```