# UIChooseCharDialog

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `UIRenderTextureImage _blurBg`

- `Transform _viewContainer`

- `Options m_options`

- `UIChooseCharDialogViewModel m_viewModel`

- `CommonSingleChooseCharGroupView m_groupView`

- `CommonChooseCharRowComp m_rowComp`

- `GroupViewBuilder m_viewBuilder`


## Methods

- `Void _RenderGroupView()`

- `Void _GeneRowViews(RowParam, ref)`

- `CommonChooseCharRowComp _LoadRowComp()`

- `Void _OnItemClick(String)`

- `Void EventOnDismissClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIChooseCharDialog : UICustomDialog`1
{
	private const Int32 ROW_COUNT; // 0x0
	private UIRenderTextureImage _blurBg; // 0x60
	private Transform _viewContainer; // 0x68
	private Options m_options; // 0x70
	private UIChooseCharDialogViewModel m_viewModel; // 0x98
	private CommonSingleChooseCharGroupView m_groupView; // 0xa0
	private CommonChooseCharRowComp m_rowComp; // 0xa8
	private GroupViewBuilder m_viewBuilder; // 0xb0
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0_IncludeNotificationCamaraForBlur; // 0x10
	private static DelegateBridge __Hotfix0__RenderGroupView; // 0x18
	private static DelegateBridge __Hotfix0__GenerateVirtualViews; // 0x20
	private static DelegateBridge __Hotfix0__GeneRowViews; // 0x28
	private static DelegateBridge __Hotfix0__LoadRowComp; // 0x30
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnDismissClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2c3f7a4 VA: 0x75952577a4
	protected override Void OnRender(Options options) { }
	// RVA: 0x2c3fe44 VA: 0x7595257e44
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2c3feac VA: 0x7595257eac
	protected override Boolean IncludeNotificationCamaraForBlur() { }
	// RVA: 0x2c3fc80 VA: 0x7595257c80
	private Void _RenderGroupView() { }
	// RVA: 0x2c3ff98 VA: 0x7595257f98
	private List`1 _GenerateVirtualViews() { }
	// RVA: 0x2c401dc VA: 0x75952581dc
	private Void _GeneRowViews(RowParam rowParam, ref List`1 virtualViews) { }
	// RVA: 0x2c40690 VA: 0x7595258690
	private CommonChooseCharRowComp _LoadRowComp() { }
	// RVA: 0x2c40768 VA: 0x7595258768
	private Void _OnItemClick(String charId) { }
	// RVA: 0x2c40820 VA: 0x7595258820
	public Void EventOnDismissClick() { }
	// RVA: 0x2c408a4 VA: 0x75952588a4
	public Void .ctor() { }
}
```