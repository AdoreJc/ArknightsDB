# UIParticleRenderer

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_delay`

- `Int32 m_index`

- `Boolean m_isTrail`

- `Bounds m_lastBounds`

- `UIParticle m_parent`

- `ParticleSystem m_particleSystem`

- `Single m_prevCanvasScale`

- `Vector3 m_prevPsPos`

- `Vector3 m_prevScale`

- `Vector2Int m_prevScreenSize`

- `Boolean m_prewarm`

- `ParticleSystemRenderer m_renderer`

- `ParticleContext m_psContext`

- `Boolean m_isParticleDriver`


## Properties

- `Rect rootCanvasRect`


## Methods

- `Rect get_rootCanvasRect()`

- `Void Reset(Int32)`

- `Void Set(UIParticle, ParticleContext, Boolean, Boolean)`

- `Void NotifyTextureSheetAnimationFrameOverTimeChanged()`

- `Void UpdateMesh(Camera)`

- `Vector3 GetWorldScale()`

- `Matrix4x4 GetWorldMatrix(Vector3, Vector3)`

- `Void _Simulate(Vector3, Boolean)`

- `BakeInput _CreateBakeInput(Camera)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class UIParticleRenderer : MaskableGraphic
{
	private static readonly List`1 s_components; // 0x0
	private static readonly CombineInstance[] s_combineInstances; // 0x8
	private static readonly List`1 s_renderers; // 0x10
	private static readonly List`1 s_colors; // 0x18
	private static readonly Vector3[] s_corners; // 0x20
	private static Boolean s_globalDisableCulling; // 0x28
	private Boolean m_delay; // 0xe0
	private Int32 m_index; // 0xe4
	private Boolean m_isTrail; // 0xe8
	private Bounds m_lastBounds; // 0xec
	private UIParticle m_parent; // 0x108
	private ParticleSystem m_particleSystem; // 0x110
	private Single m_prevCanvasScale; // 0x118
	private Vector3 m_prevPsPos; // 0x11c
	private Vector3 m_prevScale; // 0x128
	private Vector2Int m_prevScreenSize; // 0x134
	private Boolean m_prewarm; // 0x13c
	private ParticleSystemRenderer m_renderer; // 0x140
	private ParticleContext m_psContext; // 0x148
	private Boolean m_isParticleDriver; // 0x150

	public override Texture mainTexture { get; }
	public override Boolean raycastTarget { get; }
	private Rect rootCanvasRect { get; }

	// RVA: 0x6784b1c VA: 0x7598d9cb1c
	public override Texture get_mainTexture() { }
	// RVA: 0x6784b38 VA: 0x7598d9cb38
	public override Boolean get_raycastTarget() { }
	// RVA: 0x6784b40 VA: 0x7598d9cb40
	private Rect get_rootCanvasRect() { }
	// RVA: 0x6781250 VA: 0x7598d99250
	public Void Reset(Int32 index) { }
	// RVA: 0x6783424 VA: 0x7598d9b424
	public static UIParticleRenderer AddRenderer(UIParticle parent, Int32 index) { }
	// RVA: 0x6785028 VA: 0x7598d9d028
	public override Material GetModifiedMaterial(Material baseMaterial) { }
	// RVA: 0x6781838 VA: 0x7598d99838
	public Void Set(UIParticle parent, ParticleContext psContext, Boolean isTrail, Boolean isDriver) { }
	// RVA: 0x6785114 VA: 0x7598d9d114
	public Void NotifyTextureSheetAnimationFrameOverTimeChanged() { }
	// RVA: 0x67823d0 VA: 0x7598d9a3d0
	public Void UpdateMesh(Camera bakeCamera) { }
	// RVA: 0x6785740 VA: 0x7598d9d740
	protected override Void UpdateGeometry() { }
	// RVA: 0x6785744 VA: 0x7598d9d744
	public override Void Cull(Rect clipRect, Boolean validRect) { }
	// RVA: 0x6785030 VA: 0x7598d9d030
	private Vector3 GetWorldScale() { }
	// RVA: 0x6785920 VA: 0x7598d9d920
	private Matrix4x4 GetWorldMatrix(Vector3 psPos, Vector3 scale) { }
	// RVA: 0x6785178 VA: 0x7598d9d178
	private Void _Simulate(Vector3 scale, Boolean paused) { }
	// RVA: 0x6785444 VA: 0x7598d9d444
	private BakeInput _CreateBakeInput(Camera bakeCamera) { }
	// RVA: 0x6785b74 VA: 0x7598d9db74
	public Void .ctor() { }
	// RVA: 0x6785b7c VA: 0x7598d9db7c
	private static Void .cctor() { }
}
```