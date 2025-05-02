# UIBattleSandboxConstructUIHudPlugin

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `SimpleLayoutContent _iconLayout`

- `Sprite _defaultSprite`

- `Boolean m_binded`

- `Adapter m_adapter`

- `Character m_characterOwner`


## Methods

- `Void Update()`

- `Void OnValueChanged(ConstructLandPageProp)`

- `Void <>xLuaBaseProxy_DoAttach(Unit)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxConstructUIHudPlugin : HudPlugin, IConstructSceneView
{
	private SimpleLayoutContent _iconLayout; // 0x28
	private List`1 _iconPair; // 0x30
	private Sprite _defaultSprite; // 0x38
	private Boolean m_binded; // 0x40
	private Adapter m_adapter; // 0x48
	private Character m_characterOwner; // 0x50
	private ListDict`2 m_upgradeCache; // 0x58
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_DoDetach; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20c0cb0 VA: 0x75946d8cb0
	protected override Void DoAttach(Unit owner) { }
	// RVA: 0x20c0fc4 VA: 0x75946d8fc4
	private Void Update() { }
	// RVA: 0x20c10b4 VA: 0x75946d90b4
	protected override Void DoDetach() { }
	// RVA: 0x20c1140 VA: 0x75946d9140
	public Void OnValueChanged(ConstructLandPageProp property) { }
	// RVA: 0x20c1424 VA: 0x75946d9424
	public Void .ctor() { }
	// RVA: 0x20c14e8 VA: 0x75946d94e8
	private Void <>xLuaBaseProxy_DoAttach(Unit P0) { }
	// RVA: 0x20c14f0 VA: 0x75946d94f0
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```