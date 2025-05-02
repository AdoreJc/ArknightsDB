# FurnitureOutline

**Namespace:** `Torappu`


## Fields

- `Color _outlineColor`

- `Single _fadeTime`

- `MeshRenderer m_meshRenderer`

- `SkinnedMeshRenderer m_skinnedMeshRenderer`

- `Material m_material`

- `Single m_fadeTimer`

- `Boolean m_isFinished`

- `Boolean m_isHighlight`

- `Color m_outlineColor`

- `MaterialPropertyBlock m_propertyBlock`


## Properties

- `MaterialPropertyBlock propertyBlock`

- `Boolean isHighlight`


## Methods

- `MaterialPropertyBlock get_propertyBlock()`

- `Boolean get_isHighlight()`

- `Void set_isHighlight(Boolean)`

- `Void ResetOutLine()`

- `Void _ResetInternal()`

- `Boolean Init(MeshRenderer)`

- `Boolean Init(SkinnedMeshRenderer)`

- `Void LateUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FurnitureOutline : MonoBehaviour, IHotfixable
{
	private const String SHADER_PROPERTY_OUTLINE_COLOR; // 0x0
	private Color _outlineColor; // 0x18
	private Single _fadeTime; // 0x28
	private MeshRenderer m_meshRenderer; // 0x30
	private SkinnedMeshRenderer m_skinnedMeshRenderer; // 0x38
	private Material m_material; // 0x40
	private Single m_fadeTimer; // 0x48
	private Boolean m_isFinished; // 0x4c
	private Boolean m_isHighlight; // 0x4d
	private Color m_outlineColor; // 0x50
	private MaterialPropertyBlock m_propertyBlock; // 0x60
	private static DelegateBridge __Hotfix0_get_propertyBlock; // 0x0
	private static DelegateBridge __Hotfix0_get_isHighlight; // 0x8
	private static DelegateBridge __Hotfix0_set_isHighlight; // 0x10
	private static DelegateBridge __Hotfix0_ResetOutLine; // 0x18
	private static DelegateBridge __Hotfix0__ResetInternal; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix1_Init; // 0x30
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected MaterialPropertyBlock propertyBlock { get; }
	public Boolean isHighlight { get; set; }

	// RVA: 0x2f47190 VA: 0x759555f190
	protected MaterialPropertyBlock get_propertyBlock() { }
	// RVA: 0x2f47240 VA: 0x759555f240
	public Boolean get_isHighlight() { }
	// RVA: 0x2f472a8 VA: 0x759555f2a8
	public Void set_isHighlight(Boolean value) { }
	// RVA: 0x2f47338 VA: 0x759555f338
	public Void ResetOutLine() { }
	// RVA: 0x2f473ac VA: 0x759555f3ac
	private Void _ResetInternal() { }
	// RVA: 0x2f47574 VA: 0x759555f574
	public Boolean Init(MeshRenderer meshRenderer) { }
	// RVA: 0x2f477ac VA: 0x759555f7ac
	public Boolean Init(SkinnedMeshRenderer skinnedMeshRenderer) { }
	// RVA: 0x2f47980 VA: 0x759555f980
	private Void LateUpdate() { }
	// RVA: 0x2f47c78 VA: 0x759555fc78
	public Void .ctor() { }
}
```