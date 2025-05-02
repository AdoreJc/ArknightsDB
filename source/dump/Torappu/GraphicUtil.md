# GraphicUtil

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class GraphicUtil : IHotfixable, ILuaCallCSharp
{
	public const String MAT_UI_ANIM_KEYWORD; // 0x0
	private static readonly Vector3[] s_corners; // 0x0
	private static __XLua_Gen_Delegate62 __Hotfix0_Blur; // 0x8
	private static __XLua_Gen_Delegate63 __Hotfix0_ShotBlurredCamera; // 0x10
	private static __XLua_Gen_Delegate64 __Hotfix0_AdjustSizeToMaxSize; // 0x18
	private static __XLua_Gen_Delegate65 __Hotfix1_ShotBlurredCamera; // 0x20
	private static __XLua_Gen_Delegate66 __Hotfix0_CreateCameraRT; // 0x28
	private static __XLua_Gen_Delegate67 __Hotfix0_CalcBlurSize; // 0x30
	private static __XLua_Gen_Delegate68 __Hotfix0_CalcBoundOfRectTransform; // 0x38
	private static __XLua_Gen_Delegate69 __Hotfix0_CalcWorldCenter; // 0x40
	private static __XLua_Gen_Delegate70 __Hotfix0_ConvertAnchoredPosToOtherRectTrans; // 0x48
	private static __XLua_Gen_Delegate71 __Hotfix0_StartFromLeftBottom; // 0x50
	private static __XLua_Gen_Delegate72 __Hotfix0_CalcWorldBoundOfRectTransform; // 0x58
	private static __XLua_Gen_Delegate73 __Hotfix0_CaptureTextureThumbFromCamera; // 0x60
	private static __XLua_Gen_Delegate74 __Hotfix0_CaptureSpriteThumbFromCamera; // 0x68
	private static __XLua_Gen_Delegate75 __Hotfix0_Encapsulate2DBounds; // 0x70
	private static __XLua_Gen_Delegate1 __Hotfix0_ClearRTSprite; // 0x78
	private static __XLua_Gen_Delegate76 __Hotfix0_WorldToRectLocalPoint; // 0x80
	private static __XLua_Gen_Delegate71 __Hotfix0_ConvertScreenToCanvasLogic; // 0x88
	private static __XLua_Gen_Delegate77 __Hotfix0_GetRTDescFromBase; // 0x90
	private static __XLua_Gen_Delegate78 __Hotfix0_Scale2DByMaxValue; // 0x98
	private static __XLua_Gen_Delegate6 __Hotfix0_UICalcInheritAlpha; // 0xa0
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x676e5f4 VA: 0x7598d865f4
	public static Void Blur(RenderTexture source, RenderTexture destination, Int32 downsample, Int32 blurSize, Int32 blurIterations, Material blurMaterial) { }
	// RVA: 0x676e918 VA: 0x7598d86918
	public static Sprite ShotBlurredCamera(Camera camera, Shader blurShader) { }
	// RVA: 0x676f024 VA: 0x7598d87024
	public static Void AdjustSizeToMaxSize(Int32 maxWidth, Int32 maxHeight, ref Int32 basicWidth, ref Int32 basicHeight) { }
	// RVA: 0x676ea84 VA: 0x7598d86a84
	public static Sprite ShotBlurredCamera(List`1 cameras, Shader blurShader, Int32 overrideWidth, Int32 overrideHeight) { }
	// RVA: 0x676f86c VA: 0x7598d8786c
	public static RenderTexture CreateCameraRT(Camera camera, RenderTextureFormat textureFormat, Int32 overrideWidth, Int32 overrideHeight, Int32 depthBuffer) { }
	// RVA: 0x676f680 VA: 0x7598d87680
	public static Int32 CalcBlurSize(Int32 width, Int32 height) { }
	// RVA: 0x676f9dc VA: 0x7598d879dc
	public static Bounds CalcBoundOfRectTransform(RectTransform transform, RectTransform local) { }
	// RVA: 0x676fca8 VA: 0x7598d87ca8
	public static Vector3 CalcWorldCenter(RectTransform transform) { }
	// RVA: 0x676fdd8 VA: 0x7598d87dd8
	public static Vector2 ConvertAnchoredPosToOtherRectTrans(Vector2 anchoredPos, RectTransform fromTrans, RectTransform toTrans) { }
	// RVA: 0x676ffc4 VA: 0x7598d87fc4
	public static Vector2 StartFromLeftBottom(Vector2 position, RectTransform local) { }
	// RVA: 0x6770114 VA: 0x7598d88114
	public static Bounds CalcWorldBoundOfRectTransform(RectTransform transform) { }
	// RVA: 0x677035c VA: 0x7598d8835c
	public static Texture2D CaptureTextureThumbFromCamera(Camera camera, Int32 width, Int32 height) { }
	// RVA: 0x6770554 VA: 0x7598d88554
	public static Sprite CaptureSpriteThumbFromCamera(Camera camera, Int32 width, Int32 height) { }
	// RVA: 0x6770654 VA: 0x7598d88654
	public static Bounds Encapsulate2DBounds(Bounds target, Bounds container) { }
	// RVA: 0x6770858 VA: 0x7598d88858
	public static Void ClearRTSprite(Sprite sprite) { }
	// RVA: 0x67709a0 VA: 0x7598d889a0
	public static Vector2 WorldToRectLocalPoint(Camera camera, Vector3 point, RectTransform rectTrans) { }
	// RVA: 0x6770ab4 VA: 0x7598d88ab4
	public static Vector2 ConvertScreenToCanvasLogic(Vector2 valInScreen, CanvasScaler scaler) { }
	// RVA: 0x6770c78 VA: 0x7598d88c78
	public static RenderTextureDescriptor GetRTDescFromBase(RenderTextureDescriptor baseDesc, Int32 width, Int32 height) { }
	// RVA: 0x676f36c VA: 0x7598d8736c
	public static Vector2Int Scale2DByMaxValue(Vector2Int size, Vector2Int max) { }
	// RVA: 0x6770e50 VA: 0x7598d88e50
	public static Single UICalcInheritAlpha(Graphic graphic) { }
	// RVA: 0x6771068 VA: 0x7598d89068
	public Void .ctor() { }
	// RVA: 0x67710f0 VA: 0x7598d890f0
	private static Void .cctor() { }
}
```