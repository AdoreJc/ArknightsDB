# MotionBlur

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `Single blurAmount`

- `Boolean extraBlur`

- `RenderTexture accumTexture`


## Methods

- `Void OnRenderImage(RenderTexture, RenderTexture)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class MotionBlur : ImageEffectBase
{
	public Single blurAmount; // 0x28
	public Boolean extraBlur; // 0x2c
	private RenderTexture accumTexture; // 0x30


	// RVA: 0x656452c VA: 0x7598b7c52c
	protected override Void Start() { }
	// RVA: 0x6564530 VA: 0x7598b7c530
	protected override Void OnDisable() { }
	// RVA: 0x6564594 VA: 0x7598b7c594
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x65648fc VA: 0x7598b7c8fc
	public Void .ctor() { }
}
```