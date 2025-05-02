# Convolution3x3

**Namespace:** `Colorful`


## Fields

- `Vector3 KernelTop`

- `Vector3 KernelMiddle`

- `Vector3 KernelBottom`

- `Single Divisor`

- `Single Amount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Convolution3x3 : BaseEffect
{
	public Vector3 KernelTop; // 0x28
	public Vector3 KernelMiddle; // 0x34
	public Vector3 KernelBottom; // 0x40
	public Single Divisor; // 0x4c
	public Single Amount; // 0x50


	// RVA: 0x34e9458 VA: 0x7595b01458
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e969c VA: 0x7595b0169c
	protected override String GetShaderName() { }
	// RVA: 0x34e96dc VA: 0x7595b016dc
	public Void .ctor() { }
}
```