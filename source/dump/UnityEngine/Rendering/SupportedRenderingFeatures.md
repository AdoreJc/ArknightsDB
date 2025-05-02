# SupportedRenderingFeatures

**Namespace:** `UnityEngine.Rendering`


## Fields

- `ReflectionProbeModes <reflectionProbeModes>k__BackingField`

- `LightmapMixedBakeModes <defaultMixedLightingModes>k__BackingField`

- `LightmapMixedBakeModes <mixedLightingModes>k__BackingField`

- `LightmapBakeType <lightmapBakeTypes>k__BackingField`

- `LightmapsMode <lightmapsModes>k__BackingField`

- `Boolean <enlightenLightmapper>k__BackingField`

- `Boolean <enlighten>k__BackingField`

- `Boolean <lightProbeProxyVolumes>k__BackingField`

- `Boolean <motionVectors>k__BackingField`

- `Boolean <receiveShadows>k__BackingField`

- `Boolean <reflectionProbes>k__BackingField`

- `Boolean <reflectionProbesBlendDistance>k__BackingField`

- `Boolean <rendererPriority>k__BackingField`

- `Boolean <rendersUIOverlay>k__BackingField`

- `Boolean <overridesEnvironmentLighting>k__BackingField`

- `Boolean <overridesFog>k__BackingField`

- `Boolean <overridesRealtimeReflectionProbes>k__BackingField`

- `Boolean <overridesOtherLightingSettings>k__BackingField`

- `Boolean <editableMaterialRenderQueue>k__BackingField`

- `Boolean <overridesLODBias>k__BackingField`

- `Boolean <overridesMaximumLODLevel>k__BackingField`

- `Boolean <rendererProbes>k__BackingField`

- `Boolean <particleSystemInstancing>k__BackingField`

- `Boolean <autoAmbientProbeBaking>k__BackingField`

- `Boolean <autoDefaultReflectionProbeBaking>k__BackingField`

- `Boolean <overridesShadowmask>k__BackingField`

- `String <overrideShadowmaskMessage>k__BackingField`


## Properties

- `LightmapMixedBakeModes defaultMixedLightingModes`

- `LightmapMixedBakeModes mixedLightingModes`

- `LightmapBakeType lightmapBakeTypes`

- `LightmapsMode lightmapsModes`

- `Boolean enlightenLightmapper`

- `Boolean enlighten`

- `Boolean rendersUIOverlay`

- `Boolean autoAmbientProbeBaking`

- `Boolean autoDefaultReflectionProbeBaking`


## Methods

- `LightmapMixedBakeModes get_defaultMixedLightingModes()`

- `LightmapMixedBakeModes get_mixedLightingModes()`

- `LightmapBakeType get_lightmapBakeTypes()`

- `LightmapsMode get_lightmapsModes()`

- `Boolean get_enlightenLightmapper()`

- `Boolean get_enlighten()`

- `Boolean get_rendersUIOverlay()`

- `Boolean get_autoAmbientProbeBaking()`

- `Boolean get_autoDefaultReflectionProbeBaking()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Rendering
public class SupportedRenderingFeatures
{
	private static SupportedRenderingFeatures s_Active; // 0x0
	private ReflectionProbeModes <reflectionProbeModes>k__BackingField; // 0x10
	private LightmapMixedBakeModes <defaultMixedLightingModes>k__BackingField; // 0x14
	private LightmapMixedBakeModes <mixedLightingModes>k__BackingField; // 0x18
	private LightmapBakeType <lightmapBakeTypes>k__BackingField; // 0x1c
	private LightmapsMode <lightmapsModes>k__BackingField; // 0x20
	private Boolean <enlightenLightmapper>k__BackingField; // 0x24
	private Boolean <enlighten>k__BackingField; // 0x25
	private Boolean <lightProbeProxyVolumes>k__BackingField; // 0x26
	private Boolean <motionVectors>k__BackingField; // 0x27
	private Boolean <receiveShadows>k__BackingField; // 0x28
	private Boolean <reflectionProbes>k__BackingField; // 0x29
	private Boolean <reflectionProbesBlendDistance>k__BackingField; // 0x2a
	private Boolean <rendererPriority>k__BackingField; // 0x2b
	private Boolean <rendersUIOverlay>k__BackingField; // 0x2c
	private Boolean <overridesEnvironmentLighting>k__BackingField; // 0x2d
	private Boolean <overridesFog>k__BackingField; // 0x2e
	private Boolean <overridesRealtimeReflectionProbes>k__BackingField; // 0x2f
	private Boolean <overridesOtherLightingSettings>k__BackingField; // 0x30
	private Boolean <editableMaterialRenderQueue>k__BackingField; // 0x31
	private Boolean <overridesLODBias>k__BackingField; // 0x32
	private Boolean <overridesMaximumLODLevel>k__BackingField; // 0x33
	private Boolean <rendererProbes>k__BackingField; // 0x34
	private Boolean <particleSystemInstancing>k__BackingField; // 0x35
	private Boolean <autoAmbientProbeBaking>k__BackingField; // 0x36
	private Boolean <autoDefaultReflectionProbeBaking>k__BackingField; // 0x37
	private Boolean <overridesShadowmask>k__BackingField; // 0x38
	private String <overrideShadowmaskMessage>k__BackingField; // 0x40

	public static SupportedRenderingFeatures active { get; set; }
	public LightmapMixedBakeModes defaultMixedLightingModes { get; }
	public LightmapMixedBakeModes mixedLightingModes { get; }
	public LightmapBakeType lightmapBakeTypes { get; }
	public LightmapsMode lightmapsModes { get; }
	public Boolean enlightenLightmapper { get; }
	public Boolean enlighten { get; }
	public Boolean rendersUIOverlay { get; }
	public Boolean autoAmbientProbeBaking { get; }
	public Boolean autoDefaultReflectionProbeBaking { get; }

	// RVA: 0x68a26f8 VA: 0x7598eba6f8
	public static SupportedRenderingFeatures get_active() { }
	// RVA: 0x68a1b64 VA: 0x7598eb9b64
	public static Void set_active(SupportedRenderingFeatures value) { }
	// RVA: 0x68a27b0 VA: 0x7598eba7b0
	public LightmapMixedBakeModes get_defaultMixedLightingModes() { }
	// RVA: 0x68a27b8 VA: 0x7598eba7b8
	public LightmapMixedBakeModes get_mixedLightingModes() { }
	// RVA: 0x68a27c0 VA: 0x7598eba7c0
	public LightmapBakeType get_lightmapBakeTypes() { }
	// RVA: 0x68a27c8 VA: 0x7598eba7c8
	public LightmapsMode get_lightmapsModes() { }
	// RVA: 0x68a27d0 VA: 0x7598eba7d0
	public Boolean get_enlightenLightmapper() { }
	// RVA: 0x68a27d8 VA: 0x7598eba7d8
	public Boolean get_enlighten() { }
	// RVA: 0x68a27e0 VA: 0x7598eba7e0
	public Boolean get_rendersUIOverlay() { }
	// RVA: 0x68a27e8 VA: 0x7598eba7e8
	public Boolean get_autoAmbientProbeBaking() { }
	// RVA: 0x68a27f0 VA: 0x7598eba7f0
	public Boolean get_autoDefaultReflectionProbeBaking() { }
	// RVA: 0x68a27f8 VA: 0x7598eba7f8
	internal static Void FallbackMixedLightingModeByRef(IntPtr fallbackModePtr) { }
	// RVA: 0x68a292c VA: 0x7598eba92c
	internal static Boolean IsMixedLightingModeSupported(MixedLightingMode mixedMode) { }
	// RVA: 0x68a2998 VA: 0x7598eba998
	internal static Void IsMixedLightingModeSupportedByRef(MixedLightingMode mixedMode, IntPtr isSupportedPtr) { }
	// RVA: 0x68a2aa0 VA: 0x7598ebaaa0
	internal static Boolean IsLightmapBakeTypeSupported(LightmapBakeType bakeType) { }
	// RVA: 0x68a2b0c VA: 0x7598ebab0c
	internal static Void IsLightmapBakeTypeSupportedByRef(LightmapBakeType bakeType, IntPtr isSupportedPtr) { }
	// RVA: 0x68a2bfc VA: 0x7598ebabfc
	internal static Void IsLightmapsModeSupportedByRef(LightmapsMode mode, IntPtr isSupportedPtr) { }
	// RVA: 0x68a2c88 VA: 0x7598ebac88
	internal static Void IsLightmapperSupportedByRef(Int32 lightmapper, IntPtr isSupportedPtr) { }
	// RVA: 0x68a2d0c VA: 0x7598ebad0c
	internal static Void IsUIOverlayRenderedBySRP(IntPtr isSupportedPtr) { }
	// RVA: 0x68a2d84 VA: 0x7598ebad84
	internal static Void IsAutoAmbientProbeBakingSupported(IntPtr isSupportedPtr) { }
	// RVA: 0x68a2dfc VA: 0x7598ebadfc
	internal static Void IsAutoDefaultReflectionProbeBakingSupported(IntPtr isSupportedPtr) { }
	// RVA: 0x68a2e74 VA: 0x7598ebae74
	internal static Void FallbackLightmapperByRef(IntPtr lightmapperPtr) { }
	// RVA: 0x68a1acc VA: 0x7598eb9acc
	public Void .ctor() { }
	// RVA: 0x68a2e90 VA: 0x7598ebae90
	private static Void .cctor() { }
}
```