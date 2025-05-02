# VFloorPlane

**Namespace:** `Torappu.Building.Vault`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VFloorPlane : VGridPlane
{
	public ObstacleRect[] _obstacleRects; // 0x50


	// RVA: 0x385628c VA: 0x7595e6e28c
	public override Bounds GetLocalBounds3D(Single thickness) { }
	// RVA: 0x385634c VA: 0x7595e6e34c
	public override Bounds GetLocalBounds3D(GridPosition gridPos, Single thickness) { }
	// RVA: 0x3856474 VA: 0x7595e6e474
	protected override Vector2 LocalPosToGridPos(Vector3 localPos) { }
	// RVA: 0x38564f4 VA: 0x7595e6e4f4
	protected override Vector3 GridPosToLocalPos(Vector2 gridPos) { }
	// RVA: 0x3856548 VA: 0x7595e6e548
	protected override GridMap CreateGridMap(Options options) { }
	// RVA: 0x3856740 VA: 0x7595e6e740
	protected override Void ResetLocation(Single altitute, Rect area) { }
	// RVA: 0x38567d8 VA: 0x7595e6e7d8
	public Void .ctor() { }
}
```