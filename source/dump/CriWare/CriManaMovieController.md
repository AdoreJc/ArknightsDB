# CriManaMovieController

**Namespace:** `CriWare`


## Fields

- `Renderer target`

- `Boolean useOriginalMaterial`

- `Material originalMaterial`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriManaMovieController : CriManaMovieMaterial
{
	public Renderer target; // 0x98
	public Boolean useOriginalMaterial; // 0xa0
	private Material originalMaterial; // 0xa8


	// RVA: 0x41462c0 VA: 0x759675e2c0
	public override Void CriInternalUpdate() { }
	// RVA: 0x414637c VA: 0x759675e37c
	public override Boolean RenderTargetManualSetup() { }
	// RVA: 0x41464e4 VA: 0x759675e4e4
	public override Void RenderTargetManualFinalize() { }
	// RVA: 0x414658c VA: 0x759675e58c
	protected override Void OnMaterialAvailableChanged() { }
	// RVA: 0x4146658 VA: 0x759675e658
	public Void .ctor() { }
}
```