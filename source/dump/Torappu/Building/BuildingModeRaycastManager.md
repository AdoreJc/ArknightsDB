# BuildingModeRaycastManager

**Namespace:** `Torappu.Building`


## Methods

- `Void Block(RaycastBlockKey)`

- `Void BlockAll(RaycastBlockKey)`

- `Void Unblock(RaycastBlockKey)`

- `Void BlockRaycast(IBuildingMode, Boolean)`

- `BlockContext _SecureContext(RaycastBlockKey)`

- `Mode _GetMode(IBuildingMode)`

- `Void _UpdateBlockStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingModeRaycastManager
{
	private ListDict`2 m_blockInfos; // 0x10


	// RVA: 0x3796e20 VA: 0x7595daee20
	public Void Block(RaycastBlockKey key) { }
	// RVA: 0x3797124 VA: 0x7595daf124
	public Void BlockAll(RaycastBlockKey key) { }
	// RVA: 0x3797164 VA: 0x7595daf164
	public Void Unblock(RaycastBlockKey key) { }
	// RVA: 0x3797198 VA: 0x7595daf198
	public Void BlockRaycast(IBuildingMode buildingMode, Boolean isBlock) { }
	// RVA: 0x3796ec0 VA: 0x7595daeec0
	private BlockContext _SecureContext(RaycastBlockKey key) { }
	// RVA: 0x3796f90 VA: 0x7595daef90
	private Mode _GetMode(IBuildingMode buildingMode) { }
	// RVA: 0x3797014 VA: 0x7595daf014
	private Void _UpdateBlockStatus() { }
	// RVA: 0x37972b0 VA: 0x7595daf2b0
	public Void .ctor() { }
}
```