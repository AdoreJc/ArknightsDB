# GradientRampDynamic

**Namespace:** `Colorful`


## Fields

- `Gradient Ramp`

- `Single Amount`

- `Texture2D m_RampTexture`


## Methods

- `Void UpdateGradientCache()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class GradientRampDynamic : BaseEffect
{
	public Gradient Ramp; // 0x28
	public Single Amount; // 0x30
	protected Texture2D m_RampTexture; // 0x38


	// RVA: 0x34eb52c VA: 0x7595b0352c
	protected override Void Start() { }
	// RVA: 0x34eb6f4 VA: 0x7595b036f4
	protected virtual Void Reset() { }
	// RVA: 0x34eb554 VA: 0x7595b03554
	public Void UpdateGradientCache() { }
	// RVA: 0x34eb8f8 VA: 0x7595b038f8
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34eba1c VA: 0x7595b03a1c
	protected override String GetShaderName() { }
	// RVA: 0x34eba5c VA: 0x7595b03a5c
	public Void .ctor() { }
}
```