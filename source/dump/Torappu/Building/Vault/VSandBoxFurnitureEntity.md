# VSandBoxFurnitureEntity

**Namespace:** `Torappu.Building.Vault`


## Fields

- `String _topicId`

- `String m_triggerName`


## Methods

- `String <>xLuaBaseProxy_get_interactAnimation()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VSandBoxFurnitureEntity : VFurnitureEntity
{
	public const String ON_NONE_SEASON; // 0x0
	public const String ON_DRY_SEASON; // 0x0
	public const String ON_RAINY_SEASON; // 0x0
	private String _topicId; // 0xb8
	private String m_triggerName; // 0xc0
	private static DelegateBridge __Hotfix0_get_interactAnimation; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override String interactAnimation { get; }

	// RVA: 0x3d08c70 VA: 0x7596320c70
	protected override String get_interactAnimation() { }
	// RVA: 0x3d08cd8 VA: 0x7596320cd8
	public override Void OnInit() { }
	// RVA: 0x3d08e58 VA: 0x7596320e58
	public override Void OnExit() { }
	// RVA: 0x3d08f34 VA: 0x7596320f34
	public Void .ctor() { }
	// RVA: 0x3d08fa0 VA: 0x7596320fa0
	private String <>xLuaBaseProxy_get_interactAnimation() { }
	// RVA: 0x3d08fa4 VA: 0x7596320fa4
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3d08fa8 VA: 0x7596320fa8
	private Void <>xLuaBaseProxy_OnExit() { }
}
```