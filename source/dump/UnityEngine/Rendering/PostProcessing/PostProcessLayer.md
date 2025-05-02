# PostProcessLayer

**Namespace:** `UnityEngine.Rendering.PostProcessing`


## Fields

- `Transform volumeTrigger`

- `LayerMask volumeLayer`

- `Boolean stopNaNPropagation`

- `Boolean finalBlitToCameraTarget`

- `Antialiasing antialiasingMode`

- `TemporalAntialiasing temporalAntialiasing`

- `SubpixelMorphologicalAntialiasing subpixelMorphologicalAntialiasing`

- `FastApproximateAntialiasing fastApproximateAntialiasing`

- `Fog fog`

- `Dithering dithering`

- `PostProcessDebugLayer debugLayer`

- `PostProcessResources m_Resources`

- `PostProcessResources m_OldResources`

- `Boolean m_ShowToolkit`

- `Boolean m_ShowCustomSorter`

- `Boolean breakBeforeColorGrading`

- `DepthTextureMode <cameraDepthFlags>k__BackingField`

- `Boolean <haveBundlesBeenInited>k__BackingField`

- `PropertySheetFactory m_PropertySheetFactory`

- `CommandBuffer m_LegacyCmdBufferBeforeReflections`

- `CommandBuffer m_LegacyCmdBufferBeforeLighting`

- `CommandBuffer m_LegacyCmdBufferOpaque`

- `CommandBuffer m_LegacyCmdBuffer`

- `Camera m_Camera`

- `PostProcessRenderContext m_CurrentContext`

- `LogHistogram m_LogHistogram`

- `Boolean m_SettingsUpdateNeeded`

- `Boolean m_IsRenderingInSceneView`

- `TargetPool m_TargetPool`

- `Boolean m_NaNKilled`


## Properties

- `DepthTextureMode cameraDepthFlags`

- `Boolean haveBundlesBeenInited`


## Methods

- `Void set_sortedBundles(Dictionary`2)`

- `DepthTextureMode get_cameraDepthFlags()`

- `Void set_cameraDepthFlags(DepthTextureMode)`

- `Boolean get_haveBundlesBeenInited()`

- `Void set_haveBundlesBeenInited(Boolean)`

- `Void OnEnable()`

- `Void InitLegacy()`

- `Boolean DynamicResolutionAllowsFinalBlitToCameraTarget()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`

- `Void Init(PostProcessResources)`

- `Void InitBundles()`

- `Void UpdateBundleSortList(List`1, PostProcessEvent)`

- `Void OnDisable()`

- `Void Reset()`

- `Void OnPreCull()`

- `Void OnPreRender()`

- `Void UpdateSrcDstForOpaqueOnly(ref, ref, PostProcessRenderContext, RenderTargetIdentifier, Int32)`

- `Void BuildCommandBuffers()`

- `Void OnPostRender()`

- `PostProcessBundle GetBundle()`

- `PostProcessBundle GetBundle(Type)`

- `T GetSettings()`

- `Void BakeMSVOMap(CommandBuffer, Camera, RenderTargetIdentifier, Nullable`1, Boolean, Boolean)`

- `Void SetLegacyCameraFlags(PostProcessRenderContext)`

- `Void ResetHistory()`

- `Boolean HasOpaqueOnlyEffects(PostProcessRenderContext)`

- `Boolean HasActiveEffects(PostProcessEvent, PostProcessRenderContext)`

- `Void SetupContext(PostProcessRenderContext)`

- `Void UpdateVolumeSystem(Camera, CommandBuffer)`

- `Void RenderOpaqueOnly(PostProcessRenderContext)`

- `Void Render(PostProcessRenderContext)`

- `Int32 RenderInjectionPoint(PostProcessEvent, PostProcessRenderContext, String, Int32)`

- `Void RenderList(List`1, PostProcessRenderContext, String)`

- `Void ApplyFlip(PostProcessRenderContext, MaterialPropertyBlock)`

- `Void ApplyDefaultFlip(MaterialPropertyBlock)`

- `Int32 RenderBuiltins(PostProcessRenderContext, Boolean, Int32, Int32)`

- `Void RenderFinalPass(PostProcessRenderContext, Int32, Int32)`

- `Int32 RenderEffect(PostProcessRenderContext, Boolean)`

- `Boolean ShouldGenerateLogHistogram(PostProcessRenderContext)`


## Dump
```C#
// Dll : Unity.Postprocessing.Runtime.dll
// Namespace : UnityEngine.Rendering.PostProcessing
public class PostProcessLayer : MonoBehaviour
{
	public Transform volumeTrigger; // 0x18
	public LayerMask volumeLayer; // 0x20
	public Boolean stopNaNPropagation; // 0x24
	public Boolean finalBlitToCameraTarget; // 0x25
	public Antialiasing antialiasingMode; // 0x28
	public TemporalAntialiasing temporalAntialiasing; // 0x30
	public SubpixelMorphologicalAntialiasing subpixelMorphologicalAntialiasing; // 0x38
	public FastApproximateAntialiasing fastApproximateAntialiasing; // 0x40
	public Fog fog; // 0x48
	private Dithering dithering; // 0x50
	public PostProcessDebugLayer debugLayer; // 0x58
	private PostProcessResources m_Resources; // 0x60
	private PostProcessResources m_OldResources; // 0x68
	private Boolean m_ShowToolkit; // 0x70
	private Boolean m_ShowCustomSorter; // 0x71
	public Boolean breakBeforeColorGrading; // 0x72
	private List`1 m_BeforeTransparentBundles; // 0x78
	private List`1 m_BeforeStackBundles; // 0x80
	private List`1 m_AfterStackBundles; // 0x88
	private Dictionary`2 <sortedBundles>k__BackingField; // 0x90
	private DepthTextureMode <cameraDepthFlags>k__BackingField; // 0x98
	private Boolean <haveBundlesBeenInited>k__BackingField; // 0x9c
	private Dictionary`2 m_Bundles; // 0xa0
	private PropertySheetFactory m_PropertySheetFactory; // 0xa8
	private CommandBuffer m_LegacyCmdBufferBeforeReflections; // 0xb0
	private CommandBuffer m_LegacyCmdBufferBeforeLighting; // 0xb8
	private CommandBuffer m_LegacyCmdBufferOpaque; // 0xc0
	private CommandBuffer m_LegacyCmdBuffer; // 0xc8
	private Camera m_Camera; // 0xd0
	private PostProcessRenderContext m_CurrentContext; // 0xd8
	private LogHistogram m_LogHistogram; // 0xe0
	private Boolean m_SettingsUpdateNeeded; // 0xe8
	private Boolean m_IsRenderingInSceneView; // 0xe9
	private TargetPool m_TargetPool; // 0xf0
	private Boolean m_NaNKilled; // 0xf8
	private readonly List`1 m_ActiveEffects; // 0x100
	private readonly List`1 m_Targets; // 0x108

	public virtual Boolean hgDither { get; }
	public virtual Boolean hgVignette { get; }
	public virtual Boolean hgBloom { get; }
	public Dictionary`2 sortedBundles { get; set; }
	public DepthTextureMode cameraDepthFlags { get; set; }
	public Boolean haveBundlesBeenInited { get; set; }

	// RVA: 0x6808038 VA: 0x7598e20038
	public virtual Boolean get_hgDither() { }
	// RVA: 0x6808040 VA: 0x7598e20040
	public virtual Boolean get_hgVignette() { }
	// RVA: 0x68080ac VA: 0x7598e200ac
	public virtual Boolean get_hgBloom() { }
	// RVA: 0x6808154 VA: 0x7598e20154
	public Dictionary`2 get_sortedBundles() { }
	// RVA: 0x680815c VA: 0x7598e2015c
	private Void set_sortedBundles(Dictionary`2 value) { }
	// RVA: 0x6808164 VA: 0x7598e20164
	public DepthTextureMode get_cameraDepthFlags() { }
	// RVA: 0x680816c VA: 0x7598e2016c
	private Void set_cameraDepthFlags(DepthTextureMode value) { }
	// RVA: 0x6808174 VA: 0x7598e20174
	public Boolean get_haveBundlesBeenInited() { }
	// RVA: 0x680817c VA: 0x7598e2017c
	private Void set_haveBundlesBeenInited(Boolean value) { }
	// RVA: 0x6808188 VA: 0x7598e20188
	private Void OnEnable() { }
	// RVA: 0x6808984 VA: 0x7598e20984
	private Void InitLegacy() { }
	// RVA: 0x6808bd8 VA: 0x7598e20bd8
	private Boolean DynamicResolutionAllowsFinalBlitToCameraTarget() { }
	// RVA: 0x6808c38 VA: 0x7598e20c38
	private Void OnRenderImage(RenderTexture src, RenderTexture dst) { }
	// RVA: 0x68082d0 VA: 0x7598e202d0
	public Void Init(PostProcessResources resources) { }
	// RVA: 0x6808478 VA: 0x7598e20478
	public Void InitBundles() { }
	// RVA: 0x6808d70 VA: 0x7598e20d70
	private Void UpdateBundleSortList(List`1 sortedList, PostProcessEvent evt) { }
	// RVA: 0x6809504 VA: 0x7598e21504
	private Void OnDisable() { }
	// RVA: 0x6809950 VA: 0x7598e21950
	private Void Reset() { }
	// RVA: 0x6809974 VA: 0x7598e21974
	private Void OnPreCull() { }
	// RVA: 0x680a6f0 VA: 0x7598e226f0
	private Void OnPreRender() { }
	// RVA: 0x680a774 VA: 0x7598e22774
	private static Boolean RequiresInitialBlit(Camera camera, PostProcessRenderContext context) { }
	// RVA: 0x680a77c VA: 0x7598e2277c
	private Void UpdateSrcDstForOpaqueOnly(ref Int32 src, ref Int32 dst, PostProcessRenderContext context, RenderTargetIdentifier cameraTarget, Int32 opaqueOnlyEffectsRemaining) { }
	// RVA: 0x6809c04 VA: 0x7598e21c04
	private Void BuildCommandBuffers() { }
	// RVA: 0x680bd48 VA: 0x7598e23d48
	private Void OnPostRender() { }
	// RVA: 0x VA: 0x0
	public PostProcessBundle GetBundle() { }
	// RVA: 0x680beb4 VA: 0x7598e23eb4
	public PostProcessBundle GetBundle(Type settingsType) { }
	// RVA: 0x VA: 0x0
	public T GetSettings() { }
	// RVA: 0x680bf0c VA: 0x7598e23f0c
	public Void BakeMSVOMap(CommandBuffer cmd, Camera camera, RenderTargetIdentifier destination, Nullable`1 depthMap, Boolean invert, Boolean isMSAA) { }
	// RVA: 0x680c018 VA: 0x7598e24018
	internal Void OverrideSettings(List`1 baseSettings, Single interpFactor) { }
	// RVA: 0x680c2b0 VA: 0x7598e242b0
	private Void SetLegacyCameraFlags(PostProcessRenderContext context) { }
	// RVA: 0x680c528 VA: 0x7598e24528
	public Void ResetHistory() { }
	// RVA: 0x680b054 VA: 0x7598e23054
	public Boolean HasOpaqueOnlyEffects(PostProcessRenderContext context) { }
	// RVA: 0x680c6a0 VA: 0x7598e246a0
	public Boolean HasActiveEffects(PostProcessEvent evt, PostProcessRenderContext context) { }
	// RVA: 0x680add0 VA: 0x7598e22dd0
	private Void SetupContext(PostProcessRenderContext context) { }
	// RVA: 0x680af54 VA: 0x7598e22f54
	public Void UpdateVolumeSystem(Camera cam, CommandBuffer cmd) { }
	// RVA: 0x680b29c VA: 0x7598e2329c
	public Void RenderOpaqueOnly(PostProcessRenderContext context) { }
	// RVA: 0x680b384 VA: 0x7598e23384
	public Void Render(PostProcessRenderContext context) { }
	// RVA: 0x680db74 VA: 0x7598e25b74
	private Int32 RenderInjectionPoint(PostProcessEvent evt, PostProcessRenderContext context, String marker, Int32 releaseTargetAfterUse) { }
	// RVA: 0x680cf4c VA: 0x7598e24f4c
	private Void RenderList(List`1 list, PostProcessRenderContext context, String marker) { }
	// RVA: 0x680ec74 VA: 0x7598e26c74
	private Void ApplyFlip(PostProcessRenderContext context, MaterialPropertyBlock properties) { }
	// RVA: 0x680ed18 VA: 0x7598e26d18
	private Void ApplyDefaultFlip(MaterialPropertyBlock properties) { }
	// RVA: 0x680dd00 VA: 0x7598e25d00
	private Int32 RenderBuiltins(PostProcessRenderContext context, Boolean isFinalPass, Int32 releaseTargetAfterUse, Int32 eye) { }
	// RVA: 0x680e510 VA: 0x7598e26510
	private Void RenderFinalPass(PostProcessRenderContext context, Int32 releaseTargetAfterUse, Int32 eye) { }
	// RVA: 0x VA: 0x0
	private Int32 RenderEffect(PostProcessRenderContext context, Boolean useTempTarget) { }
	// RVA: 0x680ef34 VA: 0x7598e26f34
	private Boolean ShouldGenerateLogHistogram(PostProcessRenderContext context) { }
	// RVA: 0x680f734 VA: 0x7598e27734
	public Void .ctor() { }
}
```