# Path

**Namespace:** `DG.Tweening.Plugins.Core.PathCore`


## Fields

- `Path _incrementalClone`

- `Int32 _incrementalIndex`

- `ABSPathDecoder _decoder`

- `Boolean _changed`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Plugins.Core.PathCore
public class Path
{
	private static CatmullRomDecoder _catmullRomDecoder; // 0x0
	private static LinearDecoder _linearDecoder; // 0x8
	private static CubicBezierDecoder _cubicBezierDecoder; // 0x10
	public Single[] wpLengths; // 0x10
	public Vector3[] wps; // 0x18
	internal PathType type; // 0x20
	internal Int32 subdivisionsXSegment; // 0x24
	internal Int32 subdivisions; // 0x28
	internal ControlPoint[] controlPoints; // 0x30
	internal Single length; // 0x38
	internal Boolean isFinalized; // 0x3c
	internal Single[] timesTable; // 0x40
	internal Single[] lengthsTable; // 0x48
	internal Int32 linearWPIndex; // 0x50
	internal Boolean addedExtraStartWp; // 0x54
	internal Boolean addedExtraEndWp; // 0x55
	internal PathOptions plugOptions; // 0x58
	private Path _incrementalClone; // 0xc8
	private Int32 _incrementalIndex; // 0xd0
	private ABSPathDecoder _decoder; // 0xd8
	private Boolean _changed; // 0xe0
	internal Vector3[] nonLinearDrawWps; // 0xe8
	internal Vector3 targetPosition; // 0xf0
	internal Nullable`1 lookAtPosition; // 0xfc
	internal Color gizmoColor; // 0x10c

	internal Int32 minInputWaypoints { get; }

	// RVA: 0x4188e84 VA: 0x75967a0e84
	internal Int32 get_minInputWaypoints() { }
	// RVA: 0x4194620 VA: 0x75967ac620
	public Void .ctor(PathType type, Vector3[] waypoints, Int32 subdivisionsXSegment, Nullable`1 gizmoColor) { }
	// RVA: 0x4194aac VA: 0x75967acaac
	internal Void .ctor() { }
	// RVA: 0x4188ea4 VA: 0x75967a0ea4
	internal Void FinalizePath(Boolean isClosedPath, AxisConstraint lockPositionAxes, Vector3 currTargetVal) { }
	// RVA: 0x418985c VA: 0x75967a185c
	internal Vector3 GetPoint(Single perc, Boolean convertToConstantPerc) { }
	// RVA: 0x4189748 VA: 0x75967a1748
	internal Single ConvertToConstantPathPerc(Single perc) { }
	// RVA: 0x418a1c0 VA: 0x75967a21c0
	internal Int32 GetWaypointIndexFromPerc(Single perc, Boolean isMovingForward) { }
	// RVA: 0x4194acc VA: 0x75967acacc
	internal static Vector3[] GetDrawPoints(Path p, Int32 drawSubdivisionsXSegment) { }
	// RVA: 0x4194ba8 VA: 0x75967acba8
	internal static Void RefreshNonLinearDrawWps(Path p) { }
	// RVA: 0x418878c VA: 0x75967a078c
	internal Void Destroy() { }
	// RVA: 0x4189230 VA: 0x75967a1230
	internal Path CloneIncremental(Int32 loopIncrement) { }
	// RVA: 0x4194838 VA: 0x75967ac838
	internal Void AssignWaypoints(Vector3[] newWps, Boolean cloneWps) { }
	// RVA: 0x4194930 VA: 0x75967ac930
	internal Void AssignDecoder(PathType pathType) { }
	// RVA: 0x4194cb0 VA: 0x75967accb0
	internal Void Draw() { }
	// RVA: 0x4194cb4 VA: 0x75967accb4
	private static Void Draw(Path p) { }
	// RVA: 0x41950d4 VA: 0x75967ad0d4
	private static Vector3 ConvertToDrawPoint(Vector3 wp, PathOptions plugOptions) { }
}
```