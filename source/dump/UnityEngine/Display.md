# Display

**Namespace:** `UnityEngine`


## Properties

- `Int32 renderingWidth`

- `Int32 renderingHeight`

- `Int32 systemWidth`

- `Int32 systemHeight`

- `RenderBuffer colorBuffer`


## Methods

- `Int32 get_renderingWidth()`

- `Int32 get_renderingHeight()`

- `Int32 get_systemWidth()`

- `Int32 get_systemHeight()`

- `RenderBuffer get_colorBuffer()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Display
{
	internal IntPtr nativeDisplay; // 0x10
	public static Display[] displays; // 0x0
	private static Display _mainDisplay; // 0x8
	private static Int32 m_ActiveEditorGameViewTarget; // 0x10
	private static DisplaysUpdatedDelegate onDisplaysUpdated; // 0x18

	public Int32 renderingWidth { get; }
	public Int32 renderingHeight { get; }
	public Int32 systemWidth { get; }
	public Int32 systemHeight { get; }
	public RenderBuffer colorBuffer { get; }
	public static Display main { get; }

	// RVA: 0x685cfb8 VA: 0x7598e74fb8
	internal Void .ctor() { }
	// RVA: 0x685cff4 VA: 0x7598e74ff4
	internal Void .ctor(IntPtr nativeDisplay) { }
	// RVA: 0x685d01c VA: 0x7598e7501c
	public Int32 get_renderingWidth() { }
	// RVA: 0x685d104 VA: 0x7598e75104
	public Int32 get_renderingHeight() { }
	// RVA: 0x685d198 VA: 0x7598e75198
	public Int32 get_systemWidth() { }
	// RVA: 0x685d280 VA: 0x7598e75280
	public Int32 get_systemHeight() { }
	// RVA: 0x685d314 VA: 0x7598e75314
	public RenderBuffer get_colorBuffer() { }
	// RVA: 0x685d400 VA: 0x7598e75400
	public static Vector3 RelativeMouseAt(Vector3 inputMouseCoordinates) { }
	// RVA: 0x685d52c VA: 0x7598e7552c
	public static Display get_main() { }
	// RVA: 0x685d584 VA: 0x7598e75584
	private static Void RecreateDisplayList(IntPtr[] nativeDisplay) { }
	// RVA: 0x685d718 VA: 0x7598e75718
	private static Void FireDisplaysUpdated() { }
	// RVA: 0x685d22c VA: 0x7598e7522c
	private static Void GetSystemExtImpl(IntPtr nativeDisplay, out Int32 w, out Int32 h) { }
	// RVA: 0x685d0b0 VA: 0x7598e750b0
	private static Void GetRenderingExtImpl(IntPtr nativeDisplay, out Int32 w, out Int32 h) { }
	// RVA: 0x685d3ac VA: 0x7598e753ac
	private static Void GetRenderingBuffersImpl(IntPtr nativeDisplay, out RenderBuffer color, out RenderBuffer depth) { }
	// RVA: 0x685d4d0 VA: 0x7598e754d0
	private static Int32 RelativeMouseAtImpl(Int32 x, Int32 y, out Int32 rx, out Int32 ry) { }
	// RVA: 0x685d7ac VA: 0x7598e757ac
	private static Void .cctor() { }
}
```