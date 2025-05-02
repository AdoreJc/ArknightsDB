# CubicBezierDecoder

**Namespace:** `DG.Tweening.Plugins.Core.PathCore`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins.Core.PathCore
internal class CubicBezierDecoder : ABSPathDecoder
{
	private static readonly ControlPoint[] _PartialControlPs; // 0x0
	private static readonly Vector3[] _PartialWps; // 0x8

	internal override Int32 minInputWaypoints { get; }

	// RVA: 0x4192720 VA: 0x75967aa720
	internal override Int32 get_minInputWaypoints() { }
	// RVA: 0x4192728 VA: 0x75967aa728
	internal override Void FinalizePath(Path p, Vector3[] wps, Boolean isClosedPath) { }
	// RVA: 0x41931a0 VA: 0x75967ab1a0
	internal override Vector3 GetPoint(Single perc, Vector3[] wps, Path p, ControlPoint[] controlPoints) { }
	// RVA: 0x4192c4c VA: 0x75967aac4c
	internal Void SetTimeToLengthTables(Path p, Int32 subdivisions) { }
	// RVA: 0x4192e5c VA: 0x75967aae5c
	internal Void SetWaypointsLengths(Path p, Int32 subdivisions) { }
	// RVA: 0x4193328 VA: 0x75967ab328
	public Void .ctor() { }
	// RVA: 0x4193338 VA: 0x75967ab338
	private static Void .cctor() { }
}
```