# Wiggle

**Namespace:** `Colorful`


## Fields

- `Algorithm Mode`

- `Single Timer`

- `Single Speed`

- `Single Frequency`

- `Single Amplitude`

- `Boolean AutomaticTimer`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Colorful
public class Wiggle : BaseEffect
{
	public Algorithm Mode; // 0x28
	public Single Timer; // 0x2c
	public Single Speed; // 0x30
	public Single Frequency; // 0x34
	public Single Amplitude; // 0x38
	public Boolean AutomaticTimer; // 0x3c


	// RVA: 0x34f1c84 VA: 0x7595b09c84
	protected virtual Void Update() { }
	// RVA: 0x34f1ce0 VA: 0x7595b09ce0
	protected override Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x34f1dc8 VA: 0x7595b09dc8
	protected override String GetShaderName() { }
	// RVA: 0x34f1e08 VA: 0x7595b09e08
	public Void .ctor() { }
}
```