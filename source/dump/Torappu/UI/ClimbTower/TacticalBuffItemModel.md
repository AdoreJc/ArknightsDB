# TacticalBuffItemModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerTacticalBuffData m_buffData`

- `Boolean m_hasTowerPass`


## Properties

- `ClimbTowerTacticalBuffData buffData`

- `Boolean isBuffLocked`


## Methods

- `ClimbTowerTacticalBuffData get_buffData()`

- `Boolean get_isBuffLocked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class TacticalBuffItemModel : IHotfixable
{
	private ClimbTowerTacticalBuffData m_buffData; // 0x10
	private Boolean m_hasTowerPass; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_buffData; // 0x8
	private static DelegateBridge __Hotfix0_get_isBuffLocked; // 0x10

	public ClimbTowerTacticalBuffData buffData { get; }
	public Boolean isBuffLocked { get; }

	// RVA: 0x2c8c328 VA: 0x75952a4328
	public Void .ctor(ClimbTowerTacticalBuffData buffData, Boolean hasTowerPass) { }
	// RVA: 0x2c8c3dc VA: 0x75952a43dc
	public ClimbTowerTacticalBuffData get_buffData() { }
	// RVA: 0x2c8c444 VA: 0x75952a4444
	public Boolean get_isBuffLocked() { }
}
```