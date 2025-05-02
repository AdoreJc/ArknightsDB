# CatmullRomDecoder

**Namespace:** `DG.Tweening.Plugins.Core.PathCore`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins.Core.PathCore
internal class CatmullRomDecoder : ABSPathDecoder
{
	private static readonly ControlPoint[] _PartialControlPs; // 0x0
	private static readonly Vector3[] _PartialWps; // 0x8

	internal override Int32 minInputWaypoints { get; }

	// RVA: 0x419362c VA: 0x75967ab62c
	internal override Int32 get_minInputWaypoints() { }
	// RVA: 0x4193634 VA: 0x75967ab634
	internal override Void FinalizePath(Path p, Vector3[] wps, Boolean isClosedPath) { }
	// RVA: 0x4193ebc VA: 0x75967abebc
	internal override Vector3 GetPoint(Single perc, Vector3[] wps, Path p, ControlPoint[] controlPoints) { }
	// RVA: 0x41938b0 VA: 0x75967ab8b0
	internal Void SetTimeToLengthTables(Path p, Int32 subdivisions) { }
	// RVA: 0x4193ac0 VA: 0x75967abac0
	internal Void SetWaypointsLengths(Path p, Int32 subdivisions) { }
	// RVA: 0x4194130 VA: 0x75967ac130
	public Void .ctor() { }
	// RVA: 0x4194138 VA: 0x75967ac138
	private static Void .cctor() { }
}
```