# HandBookV2TeamMapStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapRenderProperty _mapProperty`

- `HandBookV2MapZoomProperty _zoomProperty`

- `TrackPointViewProperty _missionTrackPointProperty`

- `HandBookV2MapFocusProperty _focusProperty`

- `HandBookV2ForceMapData m_forceMapData`


## Properties

- `HandBookV2MapZoomProperty zoomProperty`


## Methods

- `HandBookV2MapZoomProperty get_zoomProperty()`

- `Void RefreshFocusPos(String)`

- `Void InitData(UIPage)`

- `Void Refresh()`

- `Void _RefreshForceViewModel(HandBookV2MapRenderViewModel)`

- `Void _InitForceLineViewModel(HandBookV2MapRenderViewModel)`

- `Void _InitPointLineViewModel(HandBookV2MapRenderViewModel)`

- `Vector2 _GetPointPos(HandBookV2MapRenderViewModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2TeamMapStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private const Single DEFAULT_ZOOM_VAL; // 0x0
	private HandBookV2MapRenderProperty _mapProperty; // 0x18
	private HandBookV2MapZoomProperty _zoomProperty; // 0x20
	private TrackPointViewProperty _missionTrackPointProperty; // 0x28
	private HandBookV2MapFocusProperty _focusProperty; // 0x30
	private HandBookV2ForceMapData m_forceMapData; // 0x38
	private static DelegateBridge __Hotfix0_get_zoomProperty; // 0x0
	private static DelegateBridge __Hotfix0_RefreshFocusPos; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge __Hotfix0_Refresh; // 0x18
	private static DelegateBridge __Hotfix0__RefreshForceViewModel; // 0x20
	private static DelegateBridge __Hotfix0__InitForceLineViewModel; // 0x28
	private static DelegateBridge __Hotfix0__InitPointLineViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GetPointPos; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public HandBookV2MapZoomProperty zoomProperty { get; }

	// RVA: 0x2edefa0 VA: 0x75954f6fa0
	public HandBookV2MapZoomProperty get_zoomProperty() { }
	// RVA: 0x2edf008 VA: 0x75954f7008
	public Void RefreshFocusPos(String forceId) { }
	// RVA: 0x2edf140 VA: 0x75954f7140
	public Void InitData(UIPage page) { }
	// RVA: 0x2ee0844 VA: 0x75954f8844
	public Void Refresh() { }
	// RVA: 0x2edf788 VA: 0x75954f7788
	private Void _RefreshForceViewModel(HandBookV2MapRenderViewModel viewModel) { }
	// RVA: 0x2ee036c VA: 0x75954f836c
	private Void _InitForceLineViewModel(HandBookV2MapRenderViewModel viewModel) { }
	// RVA: 0x2ee05a4 VA: 0x75954f85a4
	private Void _InitPointLineViewModel(HandBookV2MapRenderViewModel viewModel) { }
	// RVA: 0x2ee08d0 VA: 0x75954f88d0
	private Vector2 _GetPointPos(HandBookV2MapRenderViewModel viewModel, Int32 pointIndex) { }
	// RVA: 0x2ee0a64 VA: 0x75954f8a64
	public Void .ctor() { }
}
```