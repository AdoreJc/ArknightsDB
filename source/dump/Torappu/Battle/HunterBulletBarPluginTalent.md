# HunterBulletBarPluginTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Character m_characterOwner`

- `Ability m_traitAbility`


## Properties

- `Character characterOwner`

- `Ability traitAbiliy`

- `Boolean needDisplay`

- `Int32 currentCnt`

- `Int32 maxCnt`


## Methods

- `Character get_characterOwner()`

- `Ability get_traitAbiliy()`

- `Boolean get_needDisplay()`

- `Int32 get_currentCnt()`

- `Int32 get_maxCnt()`

- `Void _OnHudCreated(Object)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class HunterBulletBarPluginTalent : UIPluginTalent
{
	private Character m_characterOwner; // 0x60
	private Ability m_traitAbility; // 0x68
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_get_characterOwner; // 0x8
	private static DelegateBridge __Hotfix0_get_traitAbiliy; // 0x10
	private static DelegateBridge __Hotfix0_get_needDisplay; // 0x18
	private static DelegateBridge __Hotfix0_get_currentCnt; // 0x20
	private static DelegateBridge __Hotfix0_get_maxCnt; // 0x28
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x30
	private static DelegateBridge __Hotfix0_DoAttach; // 0x38
	private static DelegateBridge __Hotfix0_DoDetach; // 0x40
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override PluginType type { get; }
	private Character characterOwner { get; }
	private Ability traitAbiliy { get; }
	public Boolean needDisplay { get; }
	public Int32 currentCnt { get; }
	public Int32 maxCnt { get; }

	// RVA: 0x1b853b0 VA: 0x759419d3b0
	public override PluginType get_type() { }
	// RVA: 0x1b85414 VA: 0x759419d414
	private Character get_characterOwner() { }
	// RVA: 0x1b85558 VA: 0x759419d558
	private Ability get_traitAbiliy() { }
	// RVA: 0x1b85678 VA: 0x759419d678
	public Boolean get_needDisplay() { }
	// RVA: 0x1b85898 VA: 0x759419d898
	public Int32 get_currentCnt() { }
	// RVA: 0x1b859fc VA: 0x759419d9fc
	public Int32 get_maxCnt() { }
	// RVA: 0x1b85b60 VA: 0x759419db60
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b85c7c VA: 0x759419dc7c
	protected override Void DoAttach() { }
	// RVA: 0x1b85e80 VA: 0x759419de80
	protected override Void DoDetach() { }
	// RVA: 0x1b85f84 VA: 0x759419df84
	private Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b86020 VA: 0x759419e020
	public Void .ctor() { }
	// RVA: 0x1b860fc VA: 0x759419e0fc
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b86100 VA: 0x759419e100
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```