# FxSpineHighlight

**Namespace:** `Torappu.Fx`


## Fields

- `Color _highlightColor`

- `Color _highlightTintColor`

- `Texture2D _highlightTex`

- `Single _highlightAmount`

- `Shader _replaceShader`

- `Shader m_originShader`

- `Shader m_replaceShader`

- `Color m_originHihglightColor`

- `Color m_originHihglightTintColor`

- `Texture2D m_originHighlightTex`

- `Single m_originHighlightAmount`

- `Color m_highlightColor`

- `Color m_highlightTintColor`

- `Texture2D m_highlightTex`

- `Single m_highlightAmount`

- `Boolean m_initialized`


## Properties

- `Boolean m_isDirty`


## Methods

- `Boolean get_m_isDirty()`

- `Void _InitParams()`

- `Void _ResetParams()`

- `Void _SetParams()`

- `Void Awake()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxSpineHighlight : MonoBehaviour, IHotfixable
{
	private const String DEFAULT_SPINE_HIGHLIGHT_SHADER_NAME; // 0x0
	private Color _highlightColor; // 0x18
	private Color _highlightTintColor; // 0x28
	private Texture2D _highlightTex; // 0x38
	private Single _highlightAmount; // 0x40
	private Shader _replaceShader; // 0x48
	private Shader m_originShader; // 0x50
	private Shader m_replaceShader; // 0x58
	private Material[] m_spineMaterials; // 0x60
	private Color m_originHihglightColor; // 0x68
	private Color m_originHihglightTintColor; // 0x78
	private Texture2D m_originHighlightTex; // 0x88
	private Single m_originHighlightAmount; // 0x90
	private Color m_highlightColor; // 0x94
	private Color m_highlightTintColor; // 0xa4
	private Texture2D m_highlightTex; // 0xb8
	private Single m_highlightAmount; // 0xc0
	private Boolean m_initialized; // 0xc4
	private static DelegateBridge __Hotfix0_get_m_isDirty; // 0x0
	private static DelegateBridge __Hotfix0__InitParams; // 0x8
	private static DelegateBridge __Hotfix0__ResetParams; // 0x10
	private static DelegateBridge __Hotfix0__SetParams; // 0x18
	private static DelegateBridge __Hotfix0_Awake; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0_OnDisable; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean m_isDirty { get; }

	// RVA: 0x3efe3ac VA: 0x75965163ac
	private Boolean get_m_isDirty() { }
	// RVA: 0x3efe4d8 VA: 0x75965164d8
	private Void _InitParams() { }
	// RVA: 0x3efe55c VA: 0x759651655c
	private Void _ResetParams() { }
	// RVA: 0x3efe774 VA: 0x7596516774
	private Void _SetParams() { }
	// RVA: 0x3efea44 VA: 0x7596516a44
	private Void Awake() { }
	// RVA: 0x3efec8c VA: 0x7596516c8c
	private Void OnEnable() { }
	// RVA: 0x3efed08 VA: 0x7596516d08
	private Void OnDisable() { }
	// RVA: 0x3efed84 VA: 0x7596516d84
	private Void Update() { }
	// RVA: 0x3efee0c VA: 0x7596516e0c
	public Void .ctor() { }
}
```