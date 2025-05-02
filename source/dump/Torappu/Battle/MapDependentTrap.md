# MapDependentTrap

**Namespace:** `Torappu.Battle`


## Fields

- `String _defaultSkin`


## Methods

- `Boolean _CheckNeedToLoadSkin()`

- `Boolean _TryLoadSkin()`

- `Void <>xLuaBaseProxy_OnAwake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MapDependentTrap : Trap
{
	private const String SKIN_INSTANCE_NAME; // 0x0
	private String _defaultSkin; // 0x4f8
	private SkinEntry[] _skins; // 0x500
	private static DelegateBridge __Hotfix0_OnAwake; // 0x0
	private static DelegateBridge __Hotfix0__CheckNeedToLoadSkin; // 0x8
	private static DelegateBridge __Hotfix0__TryLoadSkin; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1c23ed4 VA: 0x759423bed4
	protected override Void OnAwake() { }
	// RVA: 0x1c2420c VA: 0x759423c20c
	private Boolean _CheckNeedToLoadSkin() { }
	// RVA: 0x1c23f48 VA: 0x759423bf48
	private Boolean _TryLoadSkin() { }
	// RVA: 0x1c242a4 VA: 0x759423c2a4
	public Void .ctor() { }
	// RVA: 0x1c2441c VA: 0x759423c41c
	private Void <>xLuaBaseProxy_OnAwake() { }
}
```