# Renderer

**Namespace:** `UnityEngine`


## Properties

- `Boolean castShadows`

- `Boolean motionVectors`

- `Boolean useLightProbes`

- `Bounds bounds`

- `Bounds localBounds`

- `Boolean enabled`

- `Boolean isVisible`

- `ShadowCastingMode shadowCastingMode`

- `Boolean receiveShadows`

- `Boolean forceRenderingOff`

- `Boolean staticShadowCaster`

- `MotionVectorGenerationMode motionVectorGenerationMode`

- `LightProbeUsage lightProbeUsage`

- `ReflectionProbeUsage reflectionProbeUsage`

- `UInt32 renderingLayerMask`

- `Int32 rendererPriority`

- `RayTracingMode rayTracingMode`

- `String sortingLayerName`

- `Int32 sortingLayerID`

- `Int32 sortingOrder`

- `Boolean allowOcclusionWhenDynamic`

- `Boolean isPartOfStaticBatch`

- `Matrix4x4 worldToLocalMatrix`

- `Matrix4x4 localToWorldMatrix`

- `GameObject lightProbeProxyVolumeOverride`

- `Transform probeAnchor`

- `Int32 lightmapIndex`

- `Int32 realtimeLightmapIndex`

- `Vector4 lightmapScaleOffset`

- `Vector4 realtimeLightmapScaleOffset`

- `Material material`

- `Material sharedMaterial`


## Methods

- `Boolean get_castShadows()`

- `Void set_castShadows(Boolean)`

- `Boolean get_motionVectors()`

- `Void set_motionVectors(Boolean)`

- `Boolean get_useLightProbes()`

- `Void set_useLightProbes(Boolean)`

- `Bounds get_bounds()`

- `Void set_bounds(Bounds)`

- `Bounds get_localBounds()`

- `Void set_localBounds(Bounds)`

- `Void ResetBounds()`

- `Void ResetLocalBounds()`

- `Void SetStaticLightmapST(Vector4)`

- `Material GetMaterial()`

- `Material GetSharedMaterial()`

- `Void SetMaterial(Material)`

- `Void CopyMaterialArray([Out])`

- `Void CopySharedMaterialArray([Out])`

- `Void SetMaterialArray(Material[])`

- `Boolean HasPropertyBlock()`

- `Void SetPropertyBlock(MaterialPropertyBlock)`

- `Void SetPropertyBlock(MaterialPropertyBlock, Int32)`

- `Void GetPropertyBlock(MaterialPropertyBlock)`

- `Void GetPropertyBlock(MaterialPropertyBlock, Int32)`

- `Void GetClosestReflectionProbesInternal(Object)`

- `Boolean get_enabled()`

- `Void set_enabled(Boolean)`

- `Boolean get_isVisible()`

- `ShadowCastingMode get_shadowCastingMode()`

- `Void set_shadowCastingMode(ShadowCastingMode)`

- `Boolean get_receiveShadows()`

- `Void set_receiveShadows(Boolean)`

- `Boolean get_forceRenderingOff()`

- `Void set_forceRenderingOff(Boolean)`

- `Boolean GetIsStaticShadowCaster()`

- `Void SetIsStaticShadowCaster(Boolean)`

- `Boolean get_staticShadowCaster()`

- `Void set_staticShadowCaster(Boolean)`

- `MotionVectorGenerationMode get_motionVectorGenerationMode()`

- `Void set_motionVectorGenerationMode(MotionVectorGenerationMode)`

- `LightProbeUsage get_lightProbeUsage()`

- `Void set_lightProbeUsage(LightProbeUsage)`

- `ReflectionProbeUsage get_reflectionProbeUsage()`

- `Void set_reflectionProbeUsage(ReflectionProbeUsage)`

- `UInt32 get_renderingLayerMask()`

- `Void set_renderingLayerMask(UInt32)`

- `Int32 get_rendererPriority()`

- `Void set_rendererPriority(Int32)`

- `RayTracingMode get_rayTracingMode()`

- `Void set_rayTracingMode(RayTracingMode)`

- `String get_sortingLayerName()`

- `Void set_sortingLayerName(String)`

- `Int32 get_sortingLayerID()`

- `Void set_sortingLayerID(Int32)`

- `Int32 get_sortingOrder()`

- `Void set_sortingOrder(Int32)`

- `Boolean get_allowOcclusionWhenDynamic()`

- `Void set_allowOcclusionWhenDynamic(Boolean)`

- `Boolean get_isPartOfStaticBatch()`

- `Matrix4x4 get_worldToLocalMatrix()`

- `Matrix4x4 get_localToWorldMatrix()`

- `GameObject get_lightProbeProxyVolumeOverride()`

- `Void set_lightProbeProxyVolumeOverride(GameObject)`

- `Transform get_probeAnchor()`

- `Void set_probeAnchor(Transform)`

- `Int32 GetLightmapIndex(LightmapType)`

- `Void SetLightmapIndex(Int32, LightmapType)`

- `Vector4 GetLightmapST(LightmapType)`

- `Void SetLightmapST(Vector4, LightmapType)`

- `Int32 get_lightmapIndex()`

- `Void set_lightmapIndex(Int32)`

- `Int32 get_realtimeLightmapIndex()`

- `Void set_realtimeLightmapIndex(Int32)`

- `Vector4 get_lightmapScaleOffset()`

- `Void set_lightmapScaleOffset(Vector4)`

- `Vector4 get_realtimeLightmapScaleOffset()`

- `Void set_realtimeLightmapScaleOffset(Vector4)`

- `Int32 GetMaterialCount()`

- `Void set_materials(Material[])`

- `Material get_material()`

- `Void set_material(Material)`

- `Material get_sharedMaterial()`

- `Void set_sharedMaterial(Material)`

- `Void set_sharedMaterials(Material[])`

- `Void GetMaterials(List`1)`

- `Void GetSharedMaterials(List`1)`

- `Void GetClosestReflectionProbes(List`1)`

- `Void get_bounds_Injected(out)`

- `Void set_bounds_Injected(ref)`

- `Void get_localBounds_Injected(out)`

- `Void set_localBounds_Injected(ref)`

- `Void SetStaticLightmapST_Injected(ref)`

- `Void get_worldToLocalMatrix_Injected(out)`

- `Void get_localToWorldMatrix_Injected(out)`

- `Void GetLightmapST_Injected(LightmapType, out)`

- `Void SetLightmapST_Injected(ref, LightmapType)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Renderer : Component
{

	public Boolean castShadows { get; set; }
	public Boolean motionVectors { get; set; }
	public Boolean useLightProbes { get; set; }
	public Bounds bounds { get; set; }
	public Bounds localBounds { get; set; }
	public Boolean enabled { get; set; }
	public Boolean isVisible { get; }
	public ShadowCastingMode shadowCastingMode { get; set; }
	public Boolean receiveShadows { get; set; }
	public Boolean forceRenderingOff { get; set; }
	public Boolean staticShadowCaster { get; set; }
	public MotionVectorGenerationMode motionVectorGenerationMode { get; set; }
	public LightProbeUsage lightProbeUsage { get; set; }
	public ReflectionProbeUsage reflectionProbeUsage { get; set; }
	public UInt32 renderingLayerMask { get; set; }
	public Int32 rendererPriority { get; set; }
	public RayTracingMode rayTracingMode { get; set; }
	public String sortingLayerName { get; set; }
	public Int32 sortingLayerID { get; set; }
	public Int32 sortingOrder { get; set; }
	internal Int32 sortingGroupID { get; set; }
	internal Int32 sortingGroupOrder { get; set; }
	public Boolean allowOcclusionWhenDynamic { get; set; }
	internal Transform staticBatchRootTransform { get; set; }
	internal Int32 staticBatchIndex { get; }
	public Boolean isPartOfStaticBatch { get; }
	public Matrix4x4 worldToLocalMatrix { get; }
	public Matrix4x4 localToWorldMatrix { get; }
	public GameObject lightProbeProxyVolumeOverride { get; set; }
	public Transform probeAnchor { get; set; }
	public Int32 lightmapIndex { get; set; }
	public Int32 realtimeLightmapIndex { get; set; }
	public Vector4 lightmapScaleOffset { get; set; }
	public Vector4 realtimeLightmapScaleOffset { get; set; }
	public Material[] materials { get; set; }
	public Material material { get; set; }
	public Material sharedMaterial { get; set; }
	public Material[] sharedMaterials { get; set; }

	// RVA: 0x68624f4 VA: 0x7598e7a4f4
	public Boolean get_castShadows() { }
	// RVA: 0x6862578 VA: 0x7598e7a578
	public Void set_castShadows(Boolean value) { }
	// RVA: 0x6862608 VA: 0x7598e7a608
	public Boolean get_motionVectors() { }
	// RVA: 0x686268c VA: 0x7598e7a68c
	public Void set_motionVectors(Boolean value) { }
	// RVA: 0x686271c VA: 0x7598e7a71c
	public Boolean get_useLightProbes() { }
	// RVA: 0x68627a0 VA: 0x7598e7a7a0
	public Void set_useLightProbes(Boolean value) { }
	// RVA: 0x6862830 VA: 0x7598e7a830
	public Bounds get_bounds() { }
	// RVA: 0x68628dc VA: 0x7598e7a8dc
	public Void set_bounds(Bounds value) { }
	// RVA: 0x6862964 VA: 0x7598e7a964
	public Bounds get_localBounds() { }
	// RVA: 0x6862a10 VA: 0x7598e7aa10
	public Void set_localBounds(Bounds value) { }
	// RVA: 0x6862a98 VA: 0x7598e7aa98
	public Void ResetBounds() { }
	// RVA: 0x6862ad4 VA: 0x7598e7aad4
	public Void ResetLocalBounds() { }
	// RVA: 0x6862b10 VA: 0x7598e7ab10
	private Void SetStaticLightmapST(Vector4 st) { }
	// RVA: 0x6862ba8 VA: 0x7598e7aba8
	private Material GetMaterial() { }
	// RVA: 0x6862be4 VA: 0x7598e7abe4
	private Material GetSharedMaterial() { }
	// RVA: 0x6862c20 VA: 0x7598e7ac20
	private Void SetMaterial(Material m) { }
	// RVA: 0x6862c64 VA: 0x7598e7ac64
	private Material[] GetMaterialArray() { }
	// RVA: 0x6862ca0 VA: 0x7598e7aca0
	private Void CopyMaterialArray([Out] Material[] m) { }
	// RVA: 0x6862ce4 VA: 0x7598e7ace4
	private Void CopySharedMaterialArray([Out] Material[] m) { }
	// RVA: 0x6862d28 VA: 0x7598e7ad28
	private Void SetMaterialArray(Material[] m) { }
	// RVA: 0x6862d6c VA: 0x7598e7ad6c
	internal Void Internal_SetPropertyBlock(MaterialPropertyBlock properties) { }
	// RVA: 0x6862db0 VA: 0x7598e7adb0
	internal Void Internal_GetPropertyBlock(MaterialPropertyBlock dest) { }
	// RVA: 0x6862df4 VA: 0x7598e7adf4
	internal Void Internal_SetPropertyBlockMaterialIndex(MaterialPropertyBlock properties, Int32 materialIndex) { }
	// RVA: 0x6862e48 VA: 0x7598e7ae48
	internal Void Internal_GetPropertyBlockMaterialIndex(MaterialPropertyBlock dest, Int32 materialIndex) { }
	// RVA: 0x6862e9c VA: 0x7598e7ae9c
	public Boolean HasPropertyBlock() { }
	// RVA: 0x6862ed8 VA: 0x7598e7aed8
	public Void SetPropertyBlock(MaterialPropertyBlock properties) { }
	// RVA: 0x6862f1c VA: 0x7598e7af1c
	public Void SetPropertyBlock(MaterialPropertyBlock properties, Int32 materialIndex) { }
	// RVA: 0x6862f70 VA: 0x7598e7af70
	public Void GetPropertyBlock(MaterialPropertyBlock properties) { }
	// RVA: 0x6862fb4 VA: 0x7598e7afb4
	public Void GetPropertyBlock(MaterialPropertyBlock properties, Int32 materialIndex) { }
	// RVA: 0x6863008 VA: 0x7598e7b008
	private Void GetClosestReflectionProbesInternal(Object result) { }
	// RVA: 0x686304c VA: 0x7598e7b04c
	public Boolean get_enabled() { }
	// RVA: 0x6863088 VA: 0x7598e7b088
	public Void set_enabled(Boolean value) { }
	// RVA: 0x68630cc VA: 0x7598e7b0cc
	public Boolean get_isVisible() { }
	// RVA: 0x686253c VA: 0x7598e7a53c
	public ShadowCastingMode get_shadowCastingMode() { }
	// RVA: 0x68625c4 VA: 0x7598e7a5c4
	public Void set_shadowCastingMode(ShadowCastingMode value) { }
	// RVA: 0x6863108 VA: 0x7598e7b108
	public Boolean get_receiveShadows() { }
	// RVA: 0x6863144 VA: 0x7598e7b144
	public Void set_receiveShadows(Boolean value) { }
	// RVA: 0x6863188 VA: 0x7598e7b188
	public Boolean get_forceRenderingOff() { }
	// RVA: 0x68631c4 VA: 0x7598e7b1c4
	public Void set_forceRenderingOff(Boolean value) { }
	// RVA: 0x6863208 VA: 0x7598e7b208
	private Boolean GetIsStaticShadowCaster() { }
	// RVA: 0x6863244 VA: 0x7598e7b244
	private Void SetIsStaticShadowCaster(Boolean value) { }
	// RVA: 0x6863288 VA: 0x7598e7b288
	public Boolean get_staticShadowCaster() { }
	// RVA: 0x68632c4 VA: 0x7598e7b2c4
	public Void set_staticShadowCaster(Boolean value) { }
	// RVA: 0x6862650 VA: 0x7598e7a650
	public MotionVectorGenerationMode get_motionVectorGenerationMode() { }
	// RVA: 0x68626d8 VA: 0x7598e7a6d8
	public Void set_motionVectorGenerationMode(MotionVectorGenerationMode value) { }
	// RVA: 0x6862764 VA: 0x7598e7a764
	public LightProbeUsage get_lightProbeUsage() { }
	// RVA: 0x68627ec VA: 0x7598e7a7ec
	public Void set_lightProbeUsage(LightProbeUsage value) { }
	// RVA: 0x6863308 VA: 0x7598e7b308
	public ReflectionProbeUsage get_reflectionProbeUsage() { }
	// RVA: 0x6863344 VA: 0x7598e7b344
	public Void set_reflectionProbeUsage(ReflectionProbeUsage value) { }
	// RVA: 0x6863388 VA: 0x7598e7b388
	public UInt32 get_renderingLayerMask() { }
	// RVA: 0x68633c4 VA: 0x7598e7b3c4
	public Void set_renderingLayerMask(UInt32 value) { }
	// RVA: 0x6863408 VA: 0x7598e7b408
	public Int32 get_rendererPriority() { }
	// RVA: 0x6863444 VA: 0x7598e7b444
	public Void set_rendererPriority(Int32 value) { }
	// RVA: 0x6863488 VA: 0x7598e7b488
	public RayTracingMode get_rayTracingMode() { }
	// RVA: 0x68634c4 VA: 0x7598e7b4c4
	public Void set_rayTracingMode(RayTracingMode value) { }
	// RVA: 0x6863508 VA: 0x7598e7b508
	public String get_sortingLayerName() { }
	// RVA: 0x6863544 VA: 0x7598e7b544
	public Void set_sortingLayerName(String value) { }
	// RVA: 0x6863588 VA: 0x7598e7b588
	public Int32 get_sortingLayerID() { }
	// RVA: 0x68635c4 VA: 0x7598e7b5c4
	public Void set_sortingLayerID(Int32 value) { }
	// RVA: 0x6863608 VA: 0x7598e7b608
	public Int32 get_sortingOrder() { }
	// RVA: 0x6863644 VA: 0x7598e7b644
	public Void set_sortingOrder(Int32 value) { }
	// RVA: 0x6863688 VA: 0x7598e7b688
	internal Int32 get_sortingGroupID() { }
	// RVA: 0x68636c4 VA: 0x7598e7b6c4
	internal Void set_sortingGroupID(Int32 value) { }
	// RVA: 0x6863708 VA: 0x7598e7b708
	internal Int32 get_sortingGroupOrder() { }
	// RVA: 0x6863744 VA: 0x7598e7b744
	internal Void set_sortingGroupOrder(Int32 value) { }
	// RVA: 0x6863788 VA: 0x7598e7b788
	public Boolean get_allowOcclusionWhenDynamic() { }
	// RVA: 0x68637c4 VA: 0x7598e7b7c4
	public Void set_allowOcclusionWhenDynamic(Boolean value) { }
	// RVA: 0x6863808 VA: 0x7598e7b808
	internal Transform get_staticBatchRootTransform() { }
	// RVA: 0x6863844 VA: 0x7598e7b844
	internal Void set_staticBatchRootTransform(Transform value) { }
	// RVA: 0x6863888 VA: 0x7598e7b888
	internal Int32 get_staticBatchIndex() { }
	// RVA: 0x68638c4 VA: 0x7598e7b8c4
	internal Void SetStaticBatchInfo(Int32 firstSubMesh, Int32 subMeshCount) { }
	// RVA: 0x6863918 VA: 0x7598e7b918
	public Boolean get_isPartOfStaticBatch() { }
	// RVA: 0x6863954 VA: 0x7598e7b954
	public Matrix4x4 get_worldToLocalMatrix() { }
	// RVA: 0x6863a04 VA: 0x7598e7ba04
	public Matrix4x4 get_localToWorldMatrix() { }
	// RVA: 0x6863ab4 VA: 0x7598e7bab4
	public GameObject get_lightProbeProxyVolumeOverride() { }
	// RVA: 0x6863af0 VA: 0x7598e7baf0
	public Void set_lightProbeProxyVolumeOverride(GameObject value) { }
	// RVA: 0x6863b34 VA: 0x7598e7bb34
	public Transform get_probeAnchor() { }
	// RVA: 0x6863b70 VA: 0x7598e7bb70
	public Void set_probeAnchor(Transform value) { }
	// RVA: 0x6863bb4 VA: 0x7598e7bbb4
	private Int32 GetLightmapIndex(LightmapType lt) { }
	// RVA: 0x6863bf8 VA: 0x7598e7bbf8
	private Void SetLightmapIndex(Int32 index, LightmapType lt) { }
	// RVA: 0x6863c4c VA: 0x7598e7bc4c
	private Vector4 GetLightmapST(LightmapType lt) { }
	// RVA: 0x6863d00 VA: 0x7598e7bd00
	private Void SetLightmapST(Vector4 st, LightmapType lt) { }
	// RVA: 0x6863db0 VA: 0x7598e7bdb0
	public Int32 get_lightmapIndex() { }
	// RVA: 0x6863df0 VA: 0x7598e7bdf0
	public Void set_lightmapIndex(Int32 value) { }
	// RVA: 0x6863e38 VA: 0x7598e7be38
	public Int32 get_realtimeLightmapIndex() { }
	// RVA: 0x6863e78 VA: 0x7598e7be78
	public Void set_realtimeLightmapIndex(Int32 value) { }
	// RVA: 0x6863ec0 VA: 0x7598e7bec0
	public Vector4 get_lightmapScaleOffset() { }
	// RVA: 0x6863ec8 VA: 0x7598e7bec8
	public Void set_lightmapScaleOffset(Vector4 value) { }
	// RVA: 0x6863ecc VA: 0x7598e7becc
	public Vector4 get_realtimeLightmapScaleOffset() { }
	// RVA: 0x6863ed4 VA: 0x7598e7bed4
	public Void set_realtimeLightmapScaleOffset(Vector4 value) { }
	// RVA: 0x6863edc VA: 0x7598e7bedc
	private Int32 GetMaterialCount() { }
	// RVA: 0x6863f18 VA: 0x7598e7bf18
	private Material[] GetSharedMaterialArray() { }
	// RVA: 0x6863f54 VA: 0x7598e7bf54
	public Material[] get_materials() { }
	// RVA: 0x6863f90 VA: 0x7598e7bf90
	public Void set_materials(Material[] value) { }
	// RVA: 0x6863fd4 VA: 0x7598e7bfd4
	public Material get_material() { }
	// RVA: 0x6864010 VA: 0x7598e7c010
	public Void set_material(Material value) { }
	// RVA: 0x6864054 VA: 0x7598e7c054
	public Material get_sharedMaterial() { }
	// RVA: 0x6864090 VA: 0x7598e7c090
	public Void set_sharedMaterial(Material value) { }
	// RVA: 0x68640d4 VA: 0x7598e7c0d4
	public Material[] get_sharedMaterials() { }
	// RVA: 0x6864110 VA: 0x7598e7c110
	public Void set_sharedMaterials(Material[] value) { }
	// RVA: 0x6864154 VA: 0x7598e7c154
	public Void GetMaterials(List`1 m) { }
	// RVA: 0x6864288 VA: 0x7598e7c288
	public Void GetSharedMaterials(List`1 m) { }
	// RVA: 0x68643bc VA: 0x7598e7c3bc
	public Void GetClosestReflectionProbes(List`1 result) { }
	// RVA: 0x6864400 VA: 0x7598e7c400
	public Void .ctor() { }
	// RVA: 0x6862898 VA: 0x7598e7a898
	private Void get_bounds_Injected(out Bounds ret) { }
	// RVA: 0x6862920 VA: 0x7598e7a920
	private Void set_bounds_Injected(ref Bounds value) { }
	// RVA: 0x68629cc VA: 0x7598e7a9cc
	private Void get_localBounds_Injected(out Bounds ret) { }
	// RVA: 0x6862a54 VA: 0x7598e7aa54
	private Void set_localBounds_Injected(ref Bounds value) { }
	// RVA: 0x6862b64 VA: 0x7598e7ab64
	private Void SetStaticLightmapST_Injected(ref Vector4 st) { }
	// RVA: 0x68639c0 VA: 0x7598e7b9c0
	private Void get_worldToLocalMatrix_Injected(out Matrix4x4 ret) { }
	// RVA: 0x6863a70 VA: 0x7598e7ba70
	private Void get_localToWorldMatrix_Injected(out Matrix4x4 ret) { }
	// RVA: 0x6863cac VA: 0x7598e7bcac
	private Void GetLightmapST_Injected(LightmapType lt, out Vector4 ret) { }
	// RVA: 0x6863d5c VA: 0x7598e7bd5c
	private Void SetLightmapST_Injected(ref Vector4 st, LightmapType lt) { }
}
```