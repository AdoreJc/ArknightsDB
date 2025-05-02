# HableCurve

**Namespace:** `UnityEngine.Rendering.PostProcessing`


## Fields

- `Single <whitePoint>k__BackingField`

- `Single <inverseWhitePoint>k__BackingField`

- `Single <x0>k__BackingField`

- `Single <x1>k__BackingField`


## Properties

- `Single whitePoint`

- `Single inverseWhitePoint`


## Methods

- `Single get_whitePoint()`

- `Void set_whitePoint(Single)`

- `Single get_inverseWhitePoint()`

- `Void set_inverseWhitePoint(Single)`

- `Void set_x0(Single)`

- `Void set_x1(Single)`

- `Single Eval(Single)`

- `Void Init(Single, Single, Single, Single, Single, Single)`

- `Void InitSegments(DirectParams)`

- `Void SolveAB(out, out, Single, Single, Single)`

- `Void AsSlopeIntercept(out, out, Single, Single, Single, Single)`

- `Single EvalDerivativeLinearGamma(Single, Single, Single, Single)`


## Dump
```C#
// Dll : Unity.Postprocessing.Runtime.dll
// Namespace : UnityEngine.Rendering.PostProcessing
public class HableCurve
{
	private Single <whitePoint>k__BackingField; // 0x10
	private Single <inverseWhitePoint>k__BackingField; // 0x14
	private Single <x0>k__BackingField; // 0x18
	private Single <x1>k__BackingField; // 0x1c
	private readonly Segment[] m_Segments; // 0x20
	public readonly Uniforms uniforms; // 0x28

	public Single whitePoint { get; set; }
	public Single inverseWhitePoint { get; set; }
	internal Single x0 { get; set; }
	internal Single x1 { get; set; }

	// RVA: 0x6813b70 VA: 0x7598e2bb70
	public Single get_whitePoint() { }
	// RVA: 0x6813b78 VA: 0x7598e2bb78
	private Void set_whitePoint(Single value) { }
	// RVA: 0x6813b80 VA: 0x7598e2bb80
	public Single get_inverseWhitePoint() { }
	// RVA: 0x6813b88 VA: 0x7598e2bb88
	private Void set_inverseWhitePoint(Single value) { }
	// RVA: 0x6813b90 VA: 0x7598e2bb90
	internal Single get_x0() { }
	// RVA: 0x6813b98 VA: 0x7598e2bb98
	private Void set_x0(Single value) { }
	// RVA: 0x6813ba0 VA: 0x7598e2bba0
	internal Single get_x1() { }
	// RVA: 0x6813ba8 VA: 0x7598e2bba8
	private Void set_x1(Single value) { }
	// RVA: 0x6813bb0 VA: 0x7598e2bbb0
	public Void .ctor() { }
	// RVA: 0x6813d44 VA: 0x7598e2bd44
	public Single Eval(Single x) { }
	// RVA: 0x6813e50 VA: 0x7598e2be50
	public Void Init(Single toeStrength, Single toeLength, Single shoulderStrength, Single shoulderLength, Single shoulderAngle, Single gamma) { }
	// RVA: 0x6813fb4 VA: 0x7598e2bfb4
	private Void InitSegments(DirectParams srcParams) { }
	// RVA: 0x68142d4 VA: 0x7598e2c2d4
	private Void SolveAB(out Single lnA, out Single B, Single x0, Single y0, Single m) { }
	// RVA: 0x6814270 VA: 0x7598e2c270
	private Void AsSlopeIntercept(out Single m, out Single b, Single x0, Single x1, Single y0, Single y1) { }
	// RVA: 0x681429c VA: 0x7598e2c29c
	private Single EvalDerivativeLinearGamma(Single m, Single b, Single g, Single x) { }
}
```