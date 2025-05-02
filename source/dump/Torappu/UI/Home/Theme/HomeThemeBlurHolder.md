# HomeThemeBlurHolder

**Namespace:** `Torappu.UI.Home.Theme`


## Fields

- `BlurScreenTexGenerator _blurGen`

- `Material _blurMaterial`

- `Vector2 _screenSize`

- `Int32 _downSample`


## Methods

- `Void SetBlurParam(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Theme
public class HomeThemeBlurHolder : MonoBehaviour, IHotfixable
{
	private BlurScreenTexGenerator _blurGen; // 0x18
	private Material _blurMaterial; // 0x20
	private Vector2 _screenSize; // 0x28
	private Int32 _downSample; // 0x30
	private const String DEFAULT_BLUR_TEX_NAME; // 0x0
	private static DelegateBridge __Hotfix0_SetBlurParam; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x284b7cc VA: 0x7594e637cc
	public Void SetBlurParam(Int32 blurLevel, Int32 downSample) { }
	// RVA: 0x284bc04 VA: 0x7594e63c04
	public Void .ctor() { }
}
```