# UIRTextUpdatePainter

**Namespace:** `UnityEngine.UIElements.UIR.Implementation`


## Fields

- `VisualElement m_CurrentElement`

- `Int32 m_TextEntryIndex`

- `Color32 m_XFormClipPages`

- `Color32 m_IDs`

- `Color32 m_Flags`

- `Color32 m_OpacityColorPages`


## Properties

- `MeshGenerationContext meshGenerationContext`


## Methods

- `MeshGenerationContext get_meshGenerationContext()`

- `Void Begin(VisualElement, UIRenderDevice)`

- `Void End()`

- `Void Dispose()`

- `Void DrawRectangle(RectangleParams)`

- `Void DrawImmediate(Action, Boolean)`

- `Void DrawText(TextParams, ITextHandle, Single)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR.Implementation
internal class UIRTextUpdatePainter : IStylePainter, IDisposable
{
	private VisualElement m_CurrentElement; // 0x10
	private Int32 m_TextEntryIndex; // 0x18
	private NativeArray`1 m_DudVerts; // 0x20
	private NativeArray`1 m_DudIndices; // 0x30
	private NativeSlice`1 m_MeshDataVerts; // 0x40
	private Color32 m_XFormClipPages; // 0x50
	private Color32 m_IDs; // 0x54
	private Color32 m_Flags; // 0x58
	private Color32 m_OpacityColorPages; // 0x5c
	private readonly MeshGenerationContext <meshGenerationContext>k__BackingField; // 0x60

	public MeshGenerationContext meshGenerationContext { get; }

	// RVA: 0x6973ea8 VA: 0x7598f8bea8
	public MeshGenerationContext get_meshGenerationContext() { }
	// RVA: 0x6973eb0 VA: 0x7598f8beb0
	public Void .ctor() { }
	// RVA: 0x696b084 VA: 0x7598f83084
	public Void Begin(VisualElement ve, UIRenderDevice device) { }
	// RVA: 0x696b2d8 VA: 0x7598f832d8
	public Void End() { }
	// RVA: 0x6973f28 VA: 0x7598f8bf28
	public Void Dispose() { }
	// RVA: 0x6973fc4 VA: 0x7598f8bfc4
	public Void DrawRectangle(RectangleParams rectParams) { }
	// RVA: 0x6973fc8 VA: 0x7598f8bfc8
	public Void DrawImmediate(Action callback, Boolean cullingEnabled) { }
	// RVA: 0x6973fcc VA: 0x7598f8bfcc
	public Void DrawText(TextParams textParams, ITextHandle handle, Single pixelsPerPoint) { }
}
```