# TermDescriptionView

**Namespace:** `Torappu.UI`


## Fields

- `CanvasGroup _rootView`

- `RectTransform _btnBack`

- `Transform _tipItemViewContainer`

- `TermDescriptionTipItemView _prefab`

- `Int32 m_focuseIdx`

- `Int32 m_focusePlusIdx`

- `Boolean m_showed`

- `TermDescriptionTipItemView m_flowTermItemView`

- `TermDescriptionTipItemView m_focusTermItemView`

- `TermDescriptionTipItemView m_focusPlusTermItemView`

- `UITermDescViewModel m_flowTermViewModel`

- `UITermDescViewModel m_focusTermViewModel`

- `UITermDescViewModel m_focusPlusTermViewModel`


## Methods

- `Void AddTermDescription(UITermDescDataModel)`

- `Void PopTermDescription()`

- `Void ShowPanel()`

- `Void HidePanel()`

- `Void _UpdateTermFocus()`

- `Void _MoveTermsUp()`

- `Void _MoveTermsDown()`

- `Void _InitFocusViewIfNeeded()`

- `Void _InitFocusPlusViewIfNeeded()`

- `Void _InitBottomFlowViewIfNeeded()`

- `Void _InitUpperFlowViewIfNeeded()`

- `Void _EnsureTermItemView(ref)`

- `Void _EnsureTermParamWrapper(ref)`

- `Void _RenderTopFlowView()`

- `Void _RenderBottomFlowView()`

- `Void _RenderFocusView()`

- `Void _RenderFocusPlusView()`

- `IEnumerator TweenShowPanel()`

- `IEnumerator TweenHidePanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TermDescriptionView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _rootView; // 0x18
	private RectTransform _btnBack; // 0x20
	private Transform _tipItemViewContainer; // 0x28
	private TermDescriptionTipItemView _prefab; // 0x30
	private List`1 m_termList; // 0x38
	private Int32 m_focuseIdx; // 0x40
	private Int32 m_focusePlusIdx; // 0x44
	private const Single FADE_DURATION; // 0x0
	private Boolean m_showed; // 0x48
	private TermDescriptionTipItemView m_flowTermItemView; // 0x50
	private TermDescriptionTipItemView m_focusTermItemView; // 0x58
	private TermDescriptionTipItemView m_focusPlusTermItemView; // 0x60
	private UITermDescViewModel m_flowTermViewModel; // 0x68
	private UITermDescViewModel m_focusTermViewModel; // 0x88
	private UITermDescViewModel m_focusPlusTermViewModel; // 0xa8
	private static DelegateBridge __Hotfix0_AddTermDescription; // 0x0
	private static DelegateBridge __Hotfix0_PopTermDescription; // 0x8
	private static DelegateBridge __Hotfix0_ShowPanel; // 0x10
	private static DelegateBridge __Hotfix0_HidePanel; // 0x18
	private static DelegateBridge __Hotfix0__UpdateTermFocus; // 0x20
	private static DelegateBridge __Hotfix0__MoveTermsUp; // 0x28
	private static DelegateBridge __Hotfix0__MoveTermsDown; // 0x30
	private static DelegateBridge __Hotfix0__InitFocusViewIfNeeded; // 0x38
	private static DelegateBridge __Hotfix0__InitFocusPlusViewIfNeeded; // 0x40
	private static DelegateBridge __Hotfix0__InitBottomFlowViewIfNeeded; // 0x48
	private static DelegateBridge __Hotfix0__InitUpperFlowViewIfNeeded; // 0x50
	private static DelegateBridge __Hotfix0__EnsureTermItemView; // 0x58
	private static DelegateBridge __Hotfix0__EnsureTermParamWrapper; // 0x60
	private static DelegateBridge __Hotfix0__RenderTopFlowView; // 0x68
	private static DelegateBridge __Hotfix0__RenderBottomFlowView; // 0x70
	private static DelegateBridge __Hotfix0__RenderFocusView; // 0x78
	private static DelegateBridge __Hotfix0__RenderFocusPlusView; // 0x80
	private static DelegateBridge __Hotfix0_TweenShowPanel; // 0x88
	private static DelegateBridge __Hotfix0_TweenHidePanel; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x228c3e4 VA: 0x75948a43e4
	public Void AddTermDescription(UITermDescDataModel termParamPair) { }
	// RVA: 0x228db68 VA: 0x75948a5b68
	public Void PopTermDescription() { }
	// RVA: 0x228c2ac VA: 0x75948a42ac
	public Void ShowPanel() { }
	// RVA: 0x228dd7c VA: 0x75948a5d7c
	public Void HidePanel() { }
	// RVA: 0x228da50 VA: 0x75948a5a50
	private Void _UpdateTermFocus() { }
	// RVA: 0x228d870 VA: 0x75948a5870
	private Void _MoveTermsUp() { }
	// RVA: 0x228df5c VA: 0x75948a5f5c
	private Void _MoveTermsDown() { }
	// RVA: 0x228e294 VA: 0x75948a6294
	private Void _InitFocusViewIfNeeded() { }
	// RVA: 0x228e478 VA: 0x75948a6478
	private Void _InitFocusPlusViewIfNeeded() { }
	// RVA: 0x228e660 VA: 0x75948a6660
	private Void _InitBottomFlowViewIfNeeded() { }
	// RVA: 0x228e770 VA: 0x75948a6770
	private Void _InitUpperFlowViewIfNeeded() { }
	// RVA: 0x228e880 VA: 0x75948a6880
	private Void _EnsureTermItemView(ref TermDescriptionTipItemView itemView) { }
	// RVA: 0x228e9fc VA: 0x75948a69fc
	private Void _EnsureTermParamWrapper(ref UITermDescViewModel viewModel) { }
	// RVA: 0x228d910 VA: 0x75948a5910
	private Void _RenderTopFlowView() { }
	// RVA: 0x228dffc VA: 0x75948a5ffc
	private Void _RenderBottomFlowView() { }
	// RVA: 0x228e348 VA: 0x75948a6348
	private Void _RenderFocusView() { }
	// RVA: 0x228e530 VA: 0x75948a6530
	private Void _RenderFocusPlusView() { }
	// RVA: 0x228e13c VA: 0x75948a613c
	private IEnumerator TweenShowPanel() { }
	// RVA: 0x228e1e8 VA: 0x75948a61e8
	private IEnumerator TweenHidePanel() { }
	// RVA: 0x228eab8 VA: 0x75948a6ab8
	public Void .ctor() { }
}
```