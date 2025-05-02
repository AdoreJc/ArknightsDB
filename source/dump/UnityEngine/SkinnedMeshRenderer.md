# SkinnedMeshRenderer

**Namespace:** `UnityEngine`


## Properties

- `SkinQuality quality`

- `Boolean updateWhenOffscreen`

- `Boolean forceMatrixRecalculationPerRender`

- `Transform rootBone`

- `Mesh sharedMesh`

- `Boolean skinnedMotionVectors`

- `Target vertexBufferTarget`


## Methods

- `SkinQuality get_quality()`

- `Void set_quality(SkinQuality)`

- `Boolean get_updateWhenOffscreen()`

- `Void set_updateWhenOffscreen(Boolean)`

- `Boolean get_forceMatrixRecalculationPerRender()`

- `Void set_forceMatrixRecalculationPerRender(Boolean)`

- `Transform get_rootBone()`

- `Void set_rootBone(Transform)`

- `Void set_bones(Transform[])`

- `Mesh get_sharedMesh()`

- `Void set_sharedMesh(Mesh)`

- `Boolean get_skinnedMotionVectors()`

- `Void set_skinnedMotionVectors(Boolean)`

- `Single GetBlendShapeWeight(Int32)`

- `Void SetBlendShapeWeight(Int32, Single)`

- `Void BakeMesh(Mesh)`

- `Void BakeMesh(Mesh, Boolean)`

- `GraphicsBuffer GetVertexBuffer()`

- `GraphicsBuffer GetPreviousVertexBuffer()`

- `GraphicsBuffer GetVertexBufferImpl()`

- `GraphicsBuffer GetPreviousVertexBufferImpl()`

- `Target get_vertexBufferTarget()`

- `Void set_vertexBufferTarget(Target)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class SkinnedMeshRenderer : Renderer
{

	public SkinQuality quality { get; set; }
	public Boolean updateWhenOffscreen { get; set; }
	public Boolean forceMatrixRecalculationPerRender { get; set; }
	public Transform rootBone { get; set; }
	public Transform[] bones { get; set; }
	public Mesh sharedMesh { get; set; }
	public Boolean skinnedMotionVectors { get; set; }
	public Target vertexBufferTarget { get; set; }

	// RVA: 0x6868614 VA: 0x7598e80614
	public SkinQuality get_quality() { }
	// RVA: 0x6868650 VA: 0x7598e80650
	public Void set_quality(SkinQuality value) { }
	// RVA: 0x6868694 VA: 0x7598e80694
	public Boolean get_updateWhenOffscreen() { }
	// RVA: 0x68686d0 VA: 0x7598e806d0
	public Void set_updateWhenOffscreen(Boolean value) { }
	// RVA: 0x6868714 VA: 0x7598e80714
	public Boolean get_forceMatrixRecalculationPerRender() { }
	// RVA: 0x6868750 VA: 0x7598e80750
	public Void set_forceMatrixRecalculationPerRender(Boolean value) { }
	// RVA: 0x6868794 VA: 0x7598e80794
	public Transform get_rootBone() { }
	// RVA: 0x68687d0 VA: 0x7598e807d0
	public Void set_rootBone(Transform value) { }
	// RVA: 0x6868814 VA: 0x7598e80814
	public Transform[] get_bones() { }
	// RVA: 0x6868850 VA: 0x7598e80850
	public Void set_bones(Transform[] value) { }
	// RVA: 0x6868894 VA: 0x7598e80894
	public Mesh get_sharedMesh() { }
	// RVA: 0x68688d0 VA: 0x7598e808d0
	public Void set_sharedMesh(Mesh value) { }
	// RVA: 0x6868914 VA: 0x7598e80914
	public Boolean get_skinnedMotionVectors() { }
	// RVA: 0x6868950 VA: 0x7598e80950
	public Void set_skinnedMotionVectors(Boolean value) { }
	// RVA: 0x6868994 VA: 0x7598e80994
	public Single GetBlendShapeWeight(Int32 index) { }
	// RVA: 0x68689d8 VA: 0x7598e809d8
	public Void SetBlendShapeWeight(Int32 index, Single value) { }
	// RVA: 0x6868a2c VA: 0x7598e80a2c
	public Void BakeMesh(Mesh mesh) { }
	// RVA: 0x6868a74 VA: 0x7598e80a74
	public Void BakeMesh(Mesh mesh, Boolean useScale) { }
	// RVA: 0x6868ac8 VA: 0x7598e80ac8
	public GraphicsBuffer GetVertexBuffer() { }
	// RVA: 0x6868bc8 VA: 0x7598e80bc8
	public GraphicsBuffer GetPreviousVertexBuffer() { }
	// RVA: 0x6868b8c VA: 0x7598e80b8c
	private GraphicsBuffer GetVertexBufferImpl() { }
	// RVA: 0x6868c8c VA: 0x7598e80c8c
	private GraphicsBuffer GetPreviousVertexBufferImpl() { }
	// RVA: 0x6868cc8 VA: 0x7598e80cc8
	public Target get_vertexBufferTarget() { }
	// RVA: 0x6868d04 VA: 0x7598e80d04
	public Void set_vertexBufferTarget(Target value) { }
	// RVA: 0x6868d48 VA: 0x7598e80d48
	public Void .ctor() { }
}
```