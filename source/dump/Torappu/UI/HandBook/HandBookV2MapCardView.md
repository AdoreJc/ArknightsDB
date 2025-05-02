# HandBookV2MapCardView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `GameObject _havePart`

- `GameObject _dontHavePart`

- `Image _charHeadIcon`

- `Text _nameText`

- `Text _numberShow`

- `GameObject _selected`

- `GameObject _haveMoreLineLeft`

- `GameObject _haveMoreLineRight`

- `UICommonTrackPoint _updatedTrackPoint`

- `Single _initPos`

- `Single _selectedPos`

- `CanvasGroup _updateFlagCanvasGroup`

- `UIHandBookCardEvent clickEvent`

- `TrackPointViewProperty m_updatedTrackPointProperty`

- `HandBookV2GroupCharViewModel m_viewModel`

- `Tween m_cacheTween`


## Methods

- `HandBookV2GroupCharViewModel GetViewModel()`

- `Void UpdateTrackPoint()`

- `Void RenderView(HandBookV2GroupCharViewModel)`

- `Void RefreshView(HandBookV2GroupCharViewModel)`

- `Void ClearMoreLine()`

- `Void ApplyMoreLine()`

- `Void OnClick()`

- `Void SetSelect(Boolean)`

- `Void OnHide()`

- `Single <SetSelect>b__24_0()`

- `Void <SetSelect>b__24_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapCardView : MonoBehaviour, IHotfixable
{
	private GameObject _havePart; // 0x18
	private GameObject _dontHavePart; // 0x20
	private Image _charHeadIcon; // 0x28
	private Text _nameText; // 0x30
	private Text _numberShow; // 0x38
	private GameObject _selected; // 0x40
	private GameObject _haveMoreLineLeft; // 0x48
	private GameObject _haveMoreLineRight; // 0x50
	private UICommonTrackPoint _updatedTrackPoint; // 0x58
	private Single _initPos; // 0x60
	private Single _selectedPos; // 0x64
	private CanvasGroup _updateFlagCanvasGroup; // 0x68
	public UIHandBookCardEvent clickEvent; // 0x70
	private const Single DURATION_PARAM; // 0x0
	private TrackPointViewProperty m_updatedTrackPointProperty; // 0x78
	private HandBookV2GroupCharViewModel m_viewModel; // 0x80
	private Tween m_cacheTween; // 0x88
	private static DelegateBridge __Hotfix0_GetViewModel; // 0x0
	private static DelegateBridge __Hotfix0_UpdateTrackPoint; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_RefreshView; // 0x18
	private static DelegateBridge __Hotfix0_ClearMoreLine; // 0x20
	private static DelegateBridge __Hotfix0_ApplyMoreLine; // 0x28
	private static DelegateBridge __Hotfix0_OnClick; // 0x30
	private static DelegateBridge __Hotfix0_SetSelect; // 0x38
	private static DelegateBridge __Hotfix0_OnHide; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2ec9ae4 VA: 0x75954e1ae4
	public HandBookV2GroupCharViewModel GetViewModel() { }
	// RVA: 0x2ed0d1c VA: 0x75954e8d1c
	public Void UpdateTrackPoint() { }
	// RVA: 0x2ecb664 VA: 0x75954e3664
	public Void RenderView(HandBookV2GroupCharViewModel viewModel) { }
	// RVA: 0x2ecbe64 VA: 0x75954e3e64
	public Void RefreshView(HandBookV2GroupCharViewModel viewModel) { }
	// RVA: 0x2ecca3c VA: 0x75954e4a3c
	public Void ClearMoreLine() { }
	// RVA: 0x2ecd150 VA: 0x75954e5150
	public Void ApplyMoreLine() { }
	// RVA: 0x2ed0dd8 VA: 0x75954e8dd8
	public Void OnClick() { }
	// RVA: 0x2eccb64 VA: 0x75954e4b64
	public Void SetSelect(Boolean isSelect) { }
	// RVA: 0x2eccabc VA: 0x75954e4abc
	public Void OnHide() { }
	// RVA: 0x2ed0e7c VA: 0x75954e8e7c
	public Void .ctor() { }
	// RVA: 0x2ed0f34 VA: 0x75954e8f34
	private Single <SetSelect>b__24_0() { }
	// RVA: 0x2ed0f50 VA: 0x75954e8f50
	private Void <SetSelect>b__24_1(Single val) { }
}
```