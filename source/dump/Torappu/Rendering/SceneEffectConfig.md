# SceneEffectConfig

**Namespace:** `Torappu.Rendering`


## Fields

- `SceneEffectProfile _effectProfile`

- `Vector4 m_heightFogParam`

- `Vector4 m_heightFogNoiseST`

- `Vector4 m_colorgradingParam`

- `Vector4 m_dirFogParam`

- `Vector4 m_dirFogParam2`

- `SceneDirectionalFog m_dirFogConfig`

- `SceneEffectProfile m_profile`


## Properties

- `SceneEffectProfile effectProfile`

- `SceneEffectProfile profile`

- `Boolean graphicsGradingEnabled`

- `Boolean shadowTintEnabled`

- `Boolean HeightFogEnabled`

- `Boolean DirFogEnabled`

- `Boolean ColorGradingEnabled`


## Methods

- `SceneEffectProfile get_effectProfile()`

- `Void set_effectProfile(SceneEffectProfile)`

- `SceneEffectProfile get_profile()`

- `Boolean get_graphicsGradingEnabled()`

- `Boolean get_shadowTintEnabled()`

- `Boolean get_HeightFogEnabled()`

- `Boolean get_DirFogEnabled()`

- `Boolean get_ColorGradingEnabled()`

- `Void Init()`

- `Void Awake()`

- `Void OnEnable()`

- `Void Update()`

- `Void OnDisable()`

- `Void EnableShadowTint()`

- `Void DisableShadowTint()`

- `Void EnableHeightFog()`

- `Void DisableHeightFog()`

- `Void EnableDirFog()`

- `Void DisableDirFog()`

- `Void EnableColorGrading()`

- `Void DisableColorGrading()`

- `Void DisableGraphicsGrading()`

- `Void UpdateShadowTint()`

- `Void UpdateHeightFog()`

- `Void UpdateDirFog()`

- `Void UpdateColorGrading()`

- `Void Refresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class SceneEffectConfig : MonoBehaviour
{
	private SceneEffectProfile _effectProfile; // 0x18
	private Vector4 m_heightFogParam; // 0x20
	private Vector4 m_heightFogNoiseST; // 0x30
	private Vector4 m_colorgradingParam; // 0x40
	private Vector4 m_dirFogParam; // 0x50
	private Vector4 m_dirFogParam2; // 0x60
	private SceneDirectionalFog m_dirFogConfig; // 0x70
	private SceneEffectProfile m_profile; // 0x78

	public SceneEffectProfile effectProfile { get; set; }
	private SceneEffectProfile profile { get; }
	private Boolean graphicsGradingEnabled { get; }
	private Boolean shadowTintEnabled { get; }
	private Boolean HeightFogEnabled { get; }
	private Boolean DirFogEnabled { get; }
	private Boolean ColorGradingEnabled { get; }

	// RVA: 0x3f04530 VA: 0x759651c530
	public SceneEffectProfile get_effectProfile() { }
	// RVA: 0x3f04538 VA: 0x759651c538
	public Void set_effectProfile(SceneEffectProfile value) { }
	// RVA: 0x3f04540 VA: 0x759651c540
	private SceneEffectProfile get_profile() { }
	// RVA: 0x3f0470c VA: 0x759651c70c
	private Boolean get_graphicsGradingEnabled() { }
	// RVA: 0x3f047a4 VA: 0x759651c7a4
	private Boolean get_shadowTintEnabled() { }
	// RVA: 0x3f0483c VA: 0x759651c83c
	private Boolean get_HeightFogEnabled() { }
	// RVA: 0x3f048d4 VA: 0x759651c8d4
	private Boolean get_DirFogEnabled() { }
	// RVA: 0x3f04994 VA: 0x759651c994
	private Boolean get_ColorGradingEnabled() { }
	// RVA: 0x3f04a64 VA: 0x759651ca64
	private Void Init() { }
	// RVA: 0x3f04b28 VA: 0x759651cb28
	private Void Awake() { }
	// RVA: 0x3f04b2c VA: 0x759651cb2c
	private Void OnEnable() { }
	// RVA: 0x3f04bb0 VA: 0x759651cbb0
	private Void Update() { }
	// RVA: 0x3f04bb4 VA: 0x759651cbb4
	private Void OnDisable() { }
	// RVA: 0x3f04cc4 VA: 0x759651ccc4
	private Void EnableShadowTint() { }
	// RVA: 0x3f04c50 VA: 0x759651cc50
	private Void DisableShadowTint() { }
	// RVA: 0x3f04d74 VA: 0x759651cd74
	private Void EnableHeightFog() { }
	// RVA: 0x3f04c0c VA: 0x759651cc0c
	private Void DisableHeightFog() { }
	// RVA: 0x3f04fa8 VA: 0x759651cfa8
	private Void EnableDirFog() { }
	// RVA: 0x3f0526c VA: 0x759651d26c
	private Void DisableDirFog() { }
	// RVA: 0x3f052c4 VA: 0x759651d2c4
	private Void EnableColorGrading() { }
	// RVA: 0x3f04bc8 VA: 0x759651cbc8
	private Void DisableColorGrading() { }
	// RVA: 0x3f053e4 VA: 0x759651d3e4
	private Void DisableGraphicsGrading() { }
	// RVA: 0x3f04d14 VA: 0x759651cd14
	private Void UpdateShadowTint() { }
	// RVA: 0x3f04dc4 VA: 0x759651cdc4
	private Void UpdateHeightFog() { }
	// RVA: 0x3f04ff8 VA: 0x759651cff8
	private Void UpdateDirFog() { }
	// RVA: 0x3f05314 VA: 0x759651d314
	private Void UpdateColorGrading() { }
	// RVA: 0x3f045fc VA: 0x759651c5fc
	public Void Refresh() { }
	// RVA: 0x3f05428 VA: 0x759651d428
	public Void .ctor() { }
}
```