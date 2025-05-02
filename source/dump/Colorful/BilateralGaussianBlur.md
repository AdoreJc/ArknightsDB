# BilateralGaussianBlur

**Namespace:** `Colorful`


## Fields

- `Int32 Passes`

- `Single Threshold`

- `Single Amount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class BilateralGaussianBlur : BaseEffect
{
	public Int32 Passes; // 0x28
	public Single Threshold; // 0x2c
	public Single Amount; // 0x30


	// RVA: 0x34e7a28 VA: 0x7595affa28
	protected override Void Start() { }
	// RVA: 0x34e7a9c VA: 0x7595affa9c
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e7cb4 VA: 0x7595affcb4
	protected virtual Void OnePassBlur(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e7e6c VA: 0x7595affe6c
	protected virtual Void MultiPassBlur(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34e819c VA: 0x7595b0019c
	protected override String GetShaderName() { }
	// RVA: 0x34e81dc VA: 0x7595b001dc
	public Void .ctor() { }
}
```