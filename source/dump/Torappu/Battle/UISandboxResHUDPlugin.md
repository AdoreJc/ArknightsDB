# UISandboxResHUDPlugin

**Namespace:** `Torappu.Battle`


## Fields

- `UIAtlasImage _resIcon`

- `Text _resCount`

- `UIAtlasImage _resBackground`

- `UIAtlasObject _battleAtlas`

- `Boolean m_isValid`


## Methods

- `Void _SetChildrenActive(Boolean)`

- `Void Update()`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UISandboxResHUDPlugin : UnitTalentUIPlugin
{
	private UIAtlasImage _resIcon; // 0x30
	private Text _resCount; // 0x38
	private UIAtlasImage _resBackground; // 0x40
	private UIAtlasObject _battleAtlas; // 0x48
	private Boolean m_isValid; // 0x50
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0__SetChildrenActive; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b89544 VA: 0x75941a1544
	protected override Void DoAttach(Unit owner, UIPluginTalent talent) { }
	// RVA: 0x1b897fc VA: 0x75941a17fc
	private Void _SetChildrenActive(Boolean isActive) { }
	// RVA: 0x1b898cc VA: 0x75941a18cc
	private Void Update() { }
	// RVA: 0x1b89ab4 VA: 0x75941a1ab4
	public Void .ctor() { }
	// RVA: 0x1b89b20 VA: 0x75941a1b20
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
}
```