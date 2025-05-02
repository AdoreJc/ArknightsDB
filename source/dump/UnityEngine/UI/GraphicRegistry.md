# GraphicRegistry

**Namespace:** `UnityEngine.UI`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class GraphicRegistry
{
	private static GraphicRegistry s_Instance; // 0x0
	private readonly Dictionary`2 m_Graphics; // 0x10
	private readonly Dictionary`2 m_RaycastableGraphics; // 0x18
	private static readonly List`1 s_EmptyList; // 0x8

	public static GraphicRegistry instance { get; }

	// RVA: 0x69230f4 VA: 0x7598f3b0f4
	protected Void .ctor() { }
	// RVA: 0x69232b4 VA: 0x7598f3b2b4
	public static GraphicRegistry get_instance() { }
	// RVA: 0x691eddc VA: 0x7598f36ddc
	public static Void RegisterGraphicForCanvas(Canvas c, Graphic graphic) { }
	// RVA: 0x691e1b4 VA: 0x7598f361b4
	public static Void RegisterRaycastGraphicForCanvas(Canvas c, Graphic graphic) { }
	// RVA: 0x691e9e0 VA: 0x7598f369e0
	public static Void UnregisterGraphicForCanvas(Canvas c, Graphic graphic) { }
	// RVA: 0x691e038 VA: 0x7598f36038
	public static Void UnregisterRaycastGraphicForCanvas(Canvas c, Graphic graphic) { }
	// RVA: 0x691f718 VA: 0x7598f37718
	public static Void DisableGraphicForCanvas(Canvas c, Graphic graphic) { }
	// RVA: 0x692336c VA: 0x7598f3b36c
	public static Void DisableRaycastGraphicForCanvas(Canvas c, Graphic graphic) { }
	// RVA: 0x69234ec VA: 0x7598f3b4ec
	public static IList`1 GetGraphicsForCanvas(Canvas canvas) { }
	// RVA: 0x692288c VA: 0x7598f3a88c
	public static IList`1 GetRaycastableGraphicsForCanvas(Canvas canvas) { }
	// RVA: 0x69235a8 VA: 0x7598f3b5a8
	private static Void .cctor() { }
}
```