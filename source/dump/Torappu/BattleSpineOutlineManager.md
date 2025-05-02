# BattleSpineOutlineManager

**Namespace:** `Torappu`


## Fields

- `Boolean m_isEnabled`

- `Shader m_outlineShader`


## Properties

- `Boolean isEnable`


## Methods

- `Boolean get_isEnable()`

- `Void Init()`

- `Void ResetMeshByAnimator(UnitAnimator, Boolean)`

- `Void DrawOutline(UnitAnimator)`

- `Void DisableOutlineByAnimator(UnitAnimator)`

- `BattleOutlineConfig _GetOutlineConfig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BattleSpineOutlineManager : IHotfixable
{
	public static readonly String OUTLINE_SHADER_NAME; // 0x0
	public static readonly Single OFFSET_Z; // 0x8
	public static readonly BattleOutlineConfig DEFAULT_CONFIG; // 0xc
	private Dictionary`2 m_options; // 0x10
	private Boolean m_isEnabled; // 0x18
	private Shader m_outlineShader; // 0x20
	private static DelegateBridge __Hotfix0_get_isEnable; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_ResetMeshByAnimator; // 0x38
	private static DelegateBridge __Hotfix0_DrawOutline; // 0x40
	private static DelegateBridge __Hotfix0_DisableOutlineByAnimator; // 0x48
	private static DelegateBridge __Hotfix0__GetOutlineConfig; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean isEnable { get; }

	// RVA: 0x2f42350 VA: 0x759555a350
	public Boolean get_isEnable() { }
	// RVA: 0x2f423c8 VA: 0x759555a3c8
	public Void Init() { }
	// RVA: 0x2f42508 VA: 0x759555a508
	public Void ResetMeshByAnimator(UnitAnimator animator, Boolean isEnabled) { }
	// RVA: 0x2f42888 VA: 0x759555a888
	public Void DrawOutline(UnitAnimator animator) { }
	// RVA: 0x2f42968 VA: 0x759555a968
	public Void DisableOutlineByAnimator(UnitAnimator animator) { }
	// RVA: 0x2f42740 VA: 0x759555a740
	private BattleOutlineConfig _GetOutlineConfig() { }
	// RVA: 0x2f42a98 VA: 0x759555aa98
	public Void .ctor() { }
	// RVA: 0x2f42b6c VA: 0x759555ab6c
	private static Void .cctor() { }
}
```