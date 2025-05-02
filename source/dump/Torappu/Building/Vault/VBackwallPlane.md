# VBackwallPlane

**Namespace:** `Torappu.Building.Vault`


## Methods

- `Boolean _ShouldEnabled()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VBackwallPlane : VGridPlane
{
	private ObstacleRect[] _obstacleRects; // 0x50


	// RVA: 0x3855b8c VA: 0x7595e6db8c
	public override Bounds GetLocalBounds3D(Single thickness) { }
	// RVA: 0x3855c4c VA: 0x7595e6dc4c
	public override Bounds GetLocalBounds3D(GridPosition gridPos, Single thickness) { }
	// RVA: 0x3855d74 VA: 0x7595e6dd74
	protected override Vector2 LocalPosToGridPos(Vector3 localPos) { }
	// RVA: 0x3855df4 VA: 0x7595e6ddf4
	protected override Vector3 GridPosToLocalPos(Vector2 gridPos) { }
	// RVA: 0x3855e38 VA: 0x7595e6de38
	protected override GridMap CreateGridMap(Options options) { }
	// RVA: 0x38561c4 VA: 0x7595e6e1c4
	protected override Void ResetLocation(Single depth, Rect area) { }
	// RVA: 0x385625c VA: 0x7595e6e25c
	protected override Void OnInit() { }
	// RVA: 0x3856090 VA: 0x7595e6e090
	private Boolean _ShouldEnabled() { }
	// RVA: 0x385627c VA: 0x7595e6e27c
	public Void .ctor() { }
}
```