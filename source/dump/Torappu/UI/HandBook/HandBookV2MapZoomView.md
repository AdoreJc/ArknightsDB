# HandBookV2MapZoomView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2TeamMapStateBean _stateBean`

- `UITouchZoom _touchZoom`

- `UIWrappedScrollRect _scrollRect`

- `HandBookV2MapView _mapView`

- `Single _fadeInScale`

- `AnimationWrapper _animWrapper`

- `Boolean m_hasInited`


## Methods

- `Void _Init(HandBookV2MapZoomModel)`

- `Void _OnScaleChanged(Single)`

- `Void _OnScaleEnd(Single)`

- `Void _OnScaleStart(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapZoomView : DataBinder`1
{
	private const String ANIM_MAP_ENTER; // 0x0
	private HandBookV2TeamMapStateBean _stateBean; // 0x20
	private UITouchZoom _touchZoom; // 0x28
	private UIWrappedScrollRect _scrollRect; // 0x30
	private HandBookV2MapView _mapView; // 0x38
	private Single _fadeInScale; // 0x40
	private AnimationWrapper _animWrapper; // 0x48
	private Boolean m_hasInited; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0__OnScaleChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnScaleEnd; // 0x18
	private static DelegateBridge __Hotfix0__OnScaleStart; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ed82b0 VA: 0x75954f02b0
	public override Void OnValueChanged(HandBookV2MapZoomProperty property) { }
	// RVA: 0x2ed83d8 VA: 0x75954f03d8
	private Void _Init(HandBookV2MapZoomModel zoomModel) { }
	// RVA: 0x2ed8540 VA: 0x75954f0540
	private Void _OnScaleChanged(Single scale) { }
	// RVA: 0x2ed8620 VA: 0x75954f0620
	private Void _OnScaleEnd(Single scale) { }
	// RVA: 0x2ed8704 VA: 0x75954f0704
	private Void _OnScaleStart(Single scale) { }
	// RVA: 0x2ed87ec VA: 0x75954f07ec
	public Void .ctor() { }
}
```