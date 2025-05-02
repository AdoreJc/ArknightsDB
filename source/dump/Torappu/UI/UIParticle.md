# UIParticle

**Namespace:** `Torappu.UI`


## Fields

- `MeshSharing _meshSharing`

- `Int64 _groupId`

- `Vector3 _scale3D`

- `Camera m_orthoCamera`

- `ParticleVars m_psVars`

- `Boolean <isPaused>k__BackingField`

- `Vector3 <canvasScale>k__BackingField`


## Properties

- `MeshSharing meshSharing`

- `Int64 groupId`

- `Single scale`

- `Vector3 scale3D`

- `Vector3 scale3DForCalc`

- `Boolean isPaused`

- `Vector3 parentScale`

- `Vector3 canvasScale`


## Methods

- `MeshSharing get_meshSharing()`

- `Void set_meshSharing(MeshSharing)`

- `Int64 get_groupId()`

- `Single get_scale()`

- `Void set_scale(Single)`

- `Vector3 get_scale3D()`

- `Void set_scale3D(Vector3)`

- `Vector3 get_scale3DForCalc()`

- `Boolean get_isPaused()`

- `Void set_isPaused(Boolean)`

- `Vector3 get_parentScale()`

- `Vector3 get_canvasScale()`

- `Void set_canvasScale(Vector3)`

- `Void Play()`

- `Void Pause()`

- `Void Resume()`

- `Void Stop()`

- `Void StartEmission()`

- `Void StopEmission()`

- `Void Clear()`

- `Void RefreshParticles()`

- `ParticleVars GetParticleVars()`

- `Void UpdateParticleVars(ParticleVars)`

- `Void RefreshParticles(List`1)`

- `Void _UpdateRendererMaterial()`

- `UIParticleRenderer GetOrCreateRenderer(Int32)`

- `ParticleContext _GetOrCreateContext(ParticleSystem)`

- `Camera _GetBakeCamera()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class UIParticle : MaskableGraphic
{
	private List`1 _particles; // 0xe0
	private MeshSharing _meshSharing; // 0xe8
	private Int64 _groupId; // 0xf0
	private Vector3 _scale3D; // 0xf8
	private readonly List`1 m_renderers; // 0x108
	private Camera m_orthoCamera; // 0x110
	private ParticleVars m_psVars; // 0x118
	private readonly Dictionary`2 m_psContexts; // 0x128
	private Boolean <isPaused>k__BackingField; // 0x130
	private Vector3 <canvasScale>k__BackingField; // 0x134

	public override Boolean raycastTarget { get; set; }
	public MeshSharing meshSharing { get; set; }
	public Int64 groupId { get; }
	internal Boolean useMeshSharing { get; }
	internal Boolean isPrimary { get; }
	internal Boolean canSimulate { get; }
	internal Boolean canRender { get; }
	public Single scale { get; set; }
	public Vector3 scale3D { get; set; }
	public Vector3 scale3DForCalc { get; }
	public List`1 particles { get; }
	public IEnumerable`1 materials { get; }
	public override Material materialForRendering { get; }
	public Boolean isPaused { get; set; }
	public Vector3 parentScale { get; }
	public Vector3 canvasScale { get; set; }

	// RVA: 0x677ff58 VA: 0x7598d97f58
	public override Boolean get_raycastTarget() { }
	// RVA: 0x677ff60 VA: 0x7598d97f60
	public override Void set_raycastTarget(Boolean value) { }
	// RVA: 0x677ff64 VA: 0x7598d97f64
	public MeshSharing get_meshSharing() { }
	// RVA: 0x677ff6c VA: 0x7598d97f6c
	public Void set_meshSharing(MeshSharing value) { }
	// RVA: 0x677ff74 VA: 0x7598d97f74
	public Int64 get_groupId() { }
	// RVA: 0x677ff7c VA: 0x7598d97f7c
	internal Boolean get_useMeshSharing() { }
	// RVA: 0x677ff9c VA: 0x7598d97f9c
	internal Boolean get_isPrimary() { }
	// RVA: 0x677ffb0 VA: 0x7598d97fb0
	internal Boolean get_canSimulate() { }
	// RVA: 0x677ffd4 VA: 0x7598d97fd4
	internal Boolean get_canRender() { }
	// RVA: 0x677fffc VA: 0x7598d97ffc
	public Single get_scale() { }
	// RVA: 0x6780004 VA: 0x7598d98004
	public Void set_scale(Single value) { }
	// RVA: 0x6780010 VA: 0x7598d98010
	public Vector3 get_scale3D() { }
	// RVA: 0x678001c VA: 0x7598d9801c
	public Void set_scale3D(Vector3 value) { }
	// RVA: 0x6780028 VA: 0x7598d98028
	public Vector3 get_scale3DForCalc() { }
	// RVA: 0x6780034 VA: 0x7598d98034
	public List`1 get_particles() { }
	// RVA: 0x678003c VA: 0x7598d9803c
	public IEnumerable`1 get_materials() { }
	// RVA: 0x67800f4 VA: 0x7598d980f4
	public override Material get_materialForRendering() { }
	// RVA: 0x67800fc VA: 0x7598d980fc
	public Boolean get_isPaused() { }
	// RVA: 0x6780104 VA: 0x7598d98104
	private Void set_isPaused(Boolean value) { }
	// RVA: 0x6780110 VA: 0x7598d98110
	public Vector3 get_parentScale() { }
	// RVA: 0x6780154 VA: 0x7598d98154
	public Vector3 get_canvasScale() { }
	// RVA: 0x6780164 VA: 0x7598d98164
	private Void set_canvasScale(Vector3 value) { }
	// RVA: 0x6780174 VA: 0x7598d98174
	protected override Void OnEnable() { }
	// RVA: 0x678087c VA: 0x7598d9887c
	protected override Void OnDisable() { }
	// RVA: 0x6780ad8 VA: 0x7598d98ad8
	public Void Play() { }
	// RVA: 0x6780bd0 VA: 0x7598d98bd0
	public Void Pause() { }
	// RVA: 0x6780ccc VA: 0x7598d98ccc
	public Void Resume() { }
	// RVA: 0x6780cd4 VA: 0x7598d98cd4
	public Void Stop() { }
	// RVA: 0x6780dd0 VA: 0x7598d98dd0
	public Void StartEmission() { }
	// RVA: 0x6780ec0 VA: 0x7598d98ec0
	public Void StopEmission() { }
	// RVA: 0x6780fb0 VA: 0x7598d98fb0
	public Void Clear() { }
	// RVA: 0x67810ac VA: 0x7598d990ac
	public Void RefreshParticles() { }
	// RVA: 0x67810b4 VA: 0x7598d990b4
	public ParticleVars GetParticleVars() { }
	// RVA: 0x67810c4 VA: 0x7598d990c4
	public Void UpdateParticleVars(ParticleVars vars) { }
	// RVA: 0x6780300 VA: 0x7598d98300
	public Void RefreshParticles(List`1 particles) { }
	// RVA: 0x6781be0 VA: 0x7598d99be0
	internal Void UpdateRenderers() { }
	// RVA: 0x6783330 VA: 0x7598d9b330
	protected override Void UpdateMaterial() { }
	// RVA: 0x6783334 VA: 0x7598d9b334
	protected override Void UpdateGeometry() { }
	// RVA: 0x6783338 VA: 0x7598d9b338
	private Void _UpdateRendererMaterial() { }
	// RVA: 0x678167c VA: 0x7598d9967c
	public UIParticleRenderer GetOrCreateRenderer(Int32 index) { }
	// RVA: 0x67813a0 VA: 0x7598d993a0
	private ParticleContext _GetOrCreateContext(ParticleSystem ps) { }
	// RVA: 0x6781d44 VA: 0x7598d99d44
	private Camera _GetBakeCamera() { }
	// RVA: 0x678382c VA: 0x7598d9b82c
	public Void .ctor() { }
}
```