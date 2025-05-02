# SandboxV2DungeonCameraSlider

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean m_isSliding`

- `Int32 m_lock`


## Properties

- `Boolean isSliding`

- `Single zoomValue`

- `Single maxZoomValue`


## Methods

- `Boolean get_isSliding()`

- `Single get_zoomValue()`

- `Void set_zoomValue(Single)`

- `Void set_maxZoomValue(Single)`

- `Single _SliderValueToZoomValue(Single)`

- `Single _ZoomValueToSliderValue(Single)`

- `Void SetLock(LockSource, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCameraSlider : Slider
{
	private Boolean m_isSliding; // 0x15a
	private Int32 m_lock; // 0x15c

	public Boolean isSliding { get; }
	public Single zoomValue { get; set; }
	public Single maxZoomValue { set; }

	// RVA: 0x2515cc0 VA: 0x7594b2dcc0
	public Boolean get_isSliding() { }
	// RVA: 0x2515cd8 VA: 0x7594b2dcd8
	public Single get_zoomValue() { }
	// RVA: 0x2516950 VA: 0x7594b2e950
	public Void set_zoomValue(Single value) { }
	// RVA: 0x25167d0 VA: 0x7594b2e7d0
	public Void set_maxZoomValue(Single value) { }
	// RVA: 0x2519200 VA: 0x7594b31200
	private Single _SliderValueToZoomValue(Single sliderValue) { }
	// RVA: 0x2519208 VA: 0x7594b31208
	private Single _ZoomValueToSliderValue(Single zoomValue) { }
	// RVA: 0x2519210 VA: 0x7594b31210
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x251924c VA: 0x7594b3124c
	public override Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x2516fd4 VA: 0x7594b2efd4
	public Void SetLock(LockSource lockSource, Boolean isLock) { }
	// RVA: 0x2519284 VA: 0x7594b31284
	public Void .ctor() { }
}
```