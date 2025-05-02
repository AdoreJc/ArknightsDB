# SoftMaskable

**Namespace:** `SoftMasking`


## Fields

- `ISoftMask _mask`

- `ISoftMask _cachedMask`

- `Graphic _graphic`

- `Material _replacement`

- `Boolean _affectedByMask`

- `Boolean _destroyed`

- `Boolean <shaderIsNotSupported>k__BackingField`


## Properties

- `Boolean shaderIsNotSupported`

- `Boolean isMaskingEnabled`

- `ISoftMask mask`

- `Graphic graphic`

- `Material replacement`


## Methods

- `Boolean get_shaderIsNotSupported()`

- `Void set_shaderIsNotSupported(Boolean)`

- `Boolean get_isMaskingEnabled()`

- `ISoftMask get_mask()`

- `Void set_mask(ISoftMask)`

- `Material GetModifiedMaterial(Material)`

- `Void Invalidate()`

- `Void MaskMightChanged()`

- `Void OnTransformChildrenChanged()`

- `Void RequestChildTransformUpdate()`

- `Graphic get_graphic()`

- `Material get_replacement()`

- `Void set_replacement(Material)`

- `Boolean FindMaskOrDie()`

- `Void SetShaderNotSupported(Material)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : SoftMasking
public class SoftMaskable : UIBehaviour, IMaterialModifier
{
	private ISoftMask _mask; // 0x18
	private ISoftMask _cachedMask; // 0x20
	private Graphic _graphic; // 0x28
	private Material _replacement; // 0x30
	private Boolean _affectedByMask; // 0x38
	private Boolean _destroyed; // 0x39
	private Boolean <shaderIsNotSupported>k__BackingField; // 0x3a

	public Boolean shaderIsNotSupported { get; set; }
	public Boolean isMaskingEnabled { get; }
	public ISoftMask mask { get; set; }
	private Graphic graphic { get; }
	private Material replacement { get; set; }

	// RVA: 0x2c1ded0 VA: 0x7595235ed0
	public Boolean get_shaderIsNotSupported() { }
	// RVA: 0x2c1ded8 VA: 0x7595235ed8
	private Void set_shaderIsNotSupported(Boolean value) { }
	// RVA: 0x2c1dee4 VA: 0x7595235ee4
	public Boolean get_isMaskingEnabled() { }
	// RVA: 0x2c1e008 VA: 0x7595236008
	public ISoftMask get_mask() { }
	// RVA: 0x2c1e010 VA: 0x7595236010
	private Void set_mask(ISoftMask value) { }
	// RVA: 0x2c1e254 VA: 0x7595236254
	public Material GetModifiedMaterial(Material baseMaterial) { }
	// RVA: 0x2c1dde4 VA: 0x7595235de4
	public Void Invalidate() { }
	// RVA: 0x2c1deac VA: 0x7595235eac
	public Void MaskMightChanged() { }
	// RVA: 0x2c1e6fc VA: 0x75952366fc
	protected override Void Awake() { }
	// RVA: 0x2c1e720 VA: 0x7595236720
	protected override Void OnEnable() { }
	// RVA: 0x2c1e810 VA: 0x7595236810
	protected override Void OnDisable() { }
	// RVA: 0x2c1e830 VA: 0x7595236830
	protected override Void OnDestroy() { }
	// RVA: 0x2c1e860 VA: 0x7595236860
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x2c1e87c VA: 0x759523687c
	protected override Void OnCanvasHierarchyChanged() { }
	// RVA: 0x2c1e898 VA: 0x7595236898
	private Void OnTransformChildrenChanged() { }
	// RVA: 0x2c1e750 VA: 0x7595236750
	private Void RequestChildTransformUpdate() { }
	// RVA: 0x2c1e584 VA: 0x7595236584
	private Graphic get_graphic() { }
	// RVA: 0x2c1e89c VA: 0x759523689c
	private Material get_replacement() { }
	// RVA: 0x2c1e118 VA: 0x7595236118
	private Void set_replacement(Material value) { }
	// RVA: 0x2c1e634 VA: 0x7595236634
	private Boolean FindMaskOrDie() { }
	// RVA: 0x2c1e8a4 VA: 0x75952368a4
	private static ISoftMask NearestMask(Transform transform, out Boolean processedByThisMask, Boolean enabledOnly) { }
	// RVA: 0x2c1e988 VA: 0x7595236988
	private static ISoftMask GetISoftMask(Transform current, Boolean shouldBeEnabled) { }
	// RVA: 0x2c1eac4 VA: 0x7595236ac4
	private static Boolean IsOverridingSortingCanvas(Transform transform) { }
	// RVA: 0x2c1e428 VA: 0x7595236428
	private Void SetShaderNotSupported(Material material) { }
	// RVA: 0x2c1eb74 VA: 0x7595236b74
	public Void .ctor() { }
}
```