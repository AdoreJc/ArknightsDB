# SpecifyUnitModeEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Int32 _unitModeIndex`

- `Boolean _pauseOnOtherMode`

- `Unit m_unit`


## Methods

- `Void Update()`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SpecifyUnitModeEffect : Behaviour
{
	private Int32 _unitModeIndex; // 0x20
	private Boolean _pauseOnOtherMode; // 0x24
	private Unit m_unit; // 0x28
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x200d7f0 VA: 0x75946257f0
	public override Void OnPlay() { }
	// RVA: 0x200d9fc VA: 0x75946259fc
	private Void Update() { }
	// RVA: 0x200db34 VA: 0x7594625b34
	public Void .ctor() { }
	// RVA: 0x200dbac VA: 0x7594625bac
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```