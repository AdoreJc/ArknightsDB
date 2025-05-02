# SmartSaturation

**Namespace:** `Colorful`


## Fields

- `Single Boost`

- `AnimationCurve Curve`

- `Texture2D _CurveTexture`


## Properties

- `Texture2D m_CurveTexture`


## Methods

- `Texture2D get_m_CurveTexture()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class SmartSaturation : BaseEffect
{
	public Single Boost; // 0x28
	public AnimationCurve Curve; // 0x30
	private Texture2D _CurveTexture; // 0x38

	protected Texture2D m_CurveTexture { get; }

	// RVA: 0x34f0998 VA: 0x7595b08998
	protected Texture2D get_m_CurveTexture() { }
	// RVA: 0x34f0a14 VA: 0x7595b08a14
	protected virtual Void Reset() { }
	// RVA: 0x34f0b5c VA: 0x7595b08b5c
	protected virtual Void OnEnable() { }
	// RVA: 0x34f0b74 VA: 0x7595b08b74
	protected override Void OnDisable() { }
	// RVA: 0x34f0c10 VA: 0x7595b08c10
	public virtual Void UpdateCurve() { }
	// RVA: 0x34f0dec VA: 0x7595b08dec
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f0eec VA: 0x7595b08eec
	protected override String GetShaderName() { }
	// RVA: 0x34f0f2c VA: 0x7595b08f2c
	public Void .ctor() { }
}
```