# RenderChainCommand

**Namespace:** `UnityEngine.UIElements.UIR`


## Methods

- `Void Blit(Texture, RenderTexture, Single)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class RenderChainCommand : LinkedPoolItem`1
{
	internal VisualElement owner; // 0x18
	internal RenderChainCommand prev; // 0x20
	internal RenderChainCommand next; // 0x28
	internal Boolean closing; // 0x30
	internal CommandType type; // 0x34
	internal State state; // 0x38
	internal MeshHandle mesh; // 0x58
	internal Int32 indexOffset; // 0x60
	internal Int32 indexCount; // 0x64
	internal Action callback; // 0x68
	private static readonly Int32 k_ID_MainTex; // 0x0
	private static ProfilerMarker s_ImmediateOverheadMarker; // 0x8


	// RVA: 0x69654d0 VA: 0x7598f7d4d0
	internal Void Reset() { }
	// RVA: 0x69633f4 VA: 0x7598f7b3f4
	internal Void ExecuteNonDrawMesh(DrawParams drawParams, Single pixelsPerPoint, ref Exception immediateException) { }
	// RVA: 0x6965af8 VA: 0x7598f7daf8
	private Void Blit(Texture source, RenderTexture destination, Single depth) { }
	// RVA: 0x6965940 VA: 0x7598f7d940
	private static Rect CombineScissorRects(Rect r0, Rect r1) { }
	// RVA: 0x696553c VA: 0x7598f7d53c
	private static RectInt RectPointsToPixelsAndFlipYAxis(Rect rect, Single pixelsPerPoint) { }
	// RVA: 0x6965c68 VA: 0x7598f7dc68
	public Void .ctor() { }
	// RVA: 0x6965cb0 VA: 0x7598f7dcb0
	private static Void .cctor() { }
}
```