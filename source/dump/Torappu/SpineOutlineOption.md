# SpineOutlineOption

**Namespace:** `Torappu`


## Fields

- `UnitAnimator m_animator`

- `Material m_currentMaterial`

- `Renderer m_currentRender`

- `MeshFilter m_currentMeshFilter`

- `Transform m_currentTransform`

- `BattleOutlineConfig m_config`

- `Shader m_outlineShader`

- `Boolean m_isEnabled`

- `Boolean <isEnabled>k__BackingField`


## Properties

- `Boolean isEnabled`


## Methods

- `Boolean get_isEnabled()`

- `Void set_isEnabled(Boolean)`

- `Void UpdateOutlineOption(UnitAnimator, Boolean)`

- `Void DoLateUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SpineOutlineOption : IHotfixable
{
	private UnitAnimator m_animator; // 0x10
	private Dictionary`2 m_materials; // 0x18
	private Material m_currentMaterial; // 0x20
	private Renderer m_currentRender; // 0x28
	private MeshFilter m_currentMeshFilter; // 0x30
	private Transform m_currentTransform; // 0x38
	private BattleOutlineConfig m_config; // 0x40
	private Shader m_outlineShader; // 0x58
	private Boolean m_isEnabled; // 0x60
	private Boolean <isEnabled>k__BackingField; // 0x61
	private static DelegateBridge __Hotfix0_get_isEnabled; // 0x0
	private static DelegateBridge __Hotfix0_set_isEnabled; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_UpdateOutlineOption; // 0x18
	private static DelegateBridge __Hotfix0_DoLateUpdate; // 0x20

	public Boolean isEnabled { get; set; }

	// RVA: 0x2f418d4 VA: 0x75955598d4
	public Boolean get_isEnabled() { }
	// RVA: 0x2f4193c VA: 0x759555993c
	public Void set_isEnabled(Boolean value) { }
	// RVA: 0x2f419bc VA: 0x75955599bc
	public Void .ctor(UnitAnimator unitAnimator, BattleOutlineConfig config, Shader outlineShader) { }
	// RVA: 0x2f41ae8 VA: 0x7595559ae8
	public Void UpdateOutlineOption(UnitAnimator animator, Boolean force) { }
	// RVA: 0x2f41ea8 VA: 0x7595559ea8
	public Void DoLateUpdate() { }
}
```