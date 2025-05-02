# TextureBlitter

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `Material m_BlitMaterial`

- `MaterialPropertyBlock m_Properties`

- `RectInt m_Viewport`

- `RenderTexture m_PrevRT`

- `Boolean <disposed>k__BackingField`


## Properties

- `Boolean disposed`


## Methods

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Void QueueBlit(Texture, RectInt, Vector2Int, Boolean, Color)`

- `Void BlitOneNow(RenderTexture, Texture, RectInt, Vector2Int, Boolean, Color)`

- `Void Commit(RenderTexture)`

- `Void BeginBlit(RenderTexture)`

- `Void DoBlit(IList`1, Int32)`

- `Void EndBlit()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class TextureBlitter : IDisposable
{
	private static readonly Int32[] k_TextureIds; // 0x0
	private static ProfilerMarker s_CommitSampler; // 0x8
	private BlitInfo[] m_SingleBlit; // 0x10
	private Material m_BlitMaterial; // 0x18
	private MaterialPropertyBlock m_Properties; // 0x20
	private RectInt m_Viewport; // 0x28
	private RenderTexture m_PrevRT; // 0x38
	private List`1 m_PendingBlits; // 0x40
	private Boolean <disposed>k__BackingField; // 0x48

	protected Boolean disposed { get; set; }

	// RVA: 0x6957650 VA: 0x7598f6f650
	protected Boolean get_disposed() { }
	// RVA: 0x6957658 VA: 0x7598f6f658
	private Void set_disposed(Boolean value) { }
	// RVA: 0x6957664 VA: 0x7598f6f664
	public Void Dispose() { }
	// RVA: 0x69576d0 VA: 0x7598f6f6d0
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x695775c VA: 0x7598f6f75c
	private static Void .cctor() { }
	// RVA: 0x6957898 VA: 0x7598f6f898
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x6957960 VA: 0x7598f6f960
	public Void QueueBlit(Texture src, RectInt srcRect, Vector2Int dstPos, Boolean addBorder, Color tint) { }
	// RVA: 0x6957b24 VA: 0x7598f6fb24
	public Void BlitOneNow(RenderTexture dst, Texture src, RectInt srcRect, Vector2Int dstPos, Boolean addBorder, Color tint) { }
	// RVA: 0x69584ac VA: 0x7598f704ac
	public Void Commit(RenderTexture dst) { }
	// RVA: 0x6957c80 VA: 0x7598f6fc80
	private Void BeginBlit(RenderTexture dst) { }
	// RVA: 0x6957eb0 VA: 0x7598f6feb0
	private Void DoBlit(IList`1 blitInfos, Int32 startIndex) { }
	// RVA: 0x69583cc VA: 0x7598f703cc
	private Void EndBlit() { }
}
```