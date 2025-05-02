# UIBlendRTHost

**Namespace:** `Torappu.UI`


## Fields

- `BlurScreenTexGenerator _texGenerator`

- `Boolean m_isInited`

- `Boolean m_isRTEnabled`

- `Material m_baseImgMat`

- `Assets m_loadedAssets`

- `Boolean m_isDestroyed`

- `Material m_guassianBlurMat`

- `Material m_highColorImgMat`

- `Material m_lowColorImgMat`

- `Material m_alphaOnlyImgMat`


## Methods

- `Void InitWithBlurMode(BlurOptions)`

- `Void Bind(UIBlendRTImage)`

- `Void Unbind(UIBlendRTImage)`

- `Material SelectPropMaterial(MatOptions)`

- `Void _BindImageWhenInited(UIBlendRTImage)`

- `Config _CreateBlurConfig(BlurOptions)`

- `Material _LoadMaterial(String)`

- `Material _CreateMatByNameIfNot(String, ref)`

- `Material _GetOrCreateHighColorImgMat(Material)`

- `Material _GetOrCreateLowColorImgMat(Material)`

- `Material _GetOrCreateAlphaOnlyImgMat(Material)`

- `Void _ClearCustomImgMats()`

- `Void OnDestroy()`

- `Void _OnBlurEnableStateChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBlendRTHost : MonoBehaviour, IHotfixable
{
	private const String MAT_KEY_RGB_WEIGHT; // 0x0
	private const Single WEIGHT_HIGH_BLEND; // 0x0
	private const Single WEIGHT_LOW_BLEND; // 0x0
	private BlurScreenTexGenerator _texGenerator; // 0x18
	private HashSet`1 m_bindedImages; // 0x20
	private Boolean m_isInited; // 0x28
	private Boolean m_isRTEnabled; // 0x29
	private Material m_baseImgMat; // 0x30
	private Assets m_loadedAssets; // 0x38
	private Boolean m_isDestroyed; // 0x40
	private Material m_guassianBlurMat; // 0x48
	private Material m_highColorImgMat; // 0x50
	private Material m_lowColorImgMat; // 0x58
	private Material m_alphaOnlyImgMat; // 0x60
	private static DelegateBridge __Hotfix0_InitWithBlurMode; // 0x0
	private static DelegateBridge __Hotfix0_Bind; // 0x8
	private static DelegateBridge __Hotfix0_Unbind; // 0x10
	private static DelegateBridge __Hotfix0_SelectPropMaterial; // 0x18
	private static DelegateBridge __Hotfix0__BindImageWhenInited; // 0x20
	private static DelegateBridge __Hotfix0__CreateBlurConfig; // 0x28
	private static DelegateBridge __Hotfix0__LoadMaterial; // 0x30
	private static DelegateBridge __Hotfix0__CreateMatByNameIfNot; // 0x38
	private static DelegateBridge __Hotfix0__GetOrCreateHighColorImgMat; // 0x40
	private static DelegateBridge __Hotfix0__GetOrCreateLowColorImgMat; // 0x48
	private static DelegateBridge __Hotfix0__GetOrCreateAlphaOnlyImgMat; // 0x50
	private static DelegateBridge __Hotfix0__ClearCustomImgMats; // 0x58
	private static DelegateBridge __Hotfix0__GetOrCreateImgMat; // 0x60
	private static DelegateBridge __Hotfix0__DestroyMat; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge __Hotfix0__OnBlurEnableStateChanged; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x210e12c VA: 0x759472612c
	public Void InitWithBlurMode(BlurOptions options) { }
	// RVA: 0x210e660 VA: 0x7594726660
	public Void Bind(UIBlendRTImage image) { }
	// RVA: 0x210e75c VA: 0x759472675c
	public Void Unbind(UIBlendRTImage image) { }
	// RVA: 0x210e894 VA: 0x7594726894
	public Material SelectPropMaterial(MatOptions options) { }
	// RVA: 0x210e588 VA: 0x7594726588
	private Void _BindImageWhenInited(UIBlendRTImage image) { }
	// RVA: 0x210e374 VA: 0x7594726374
	private Config _CreateBlurConfig(BlurOptions options) { }
	// RVA: 0x210e9f4 VA: 0x75947269f4
	private Material _LoadMaterial(String path) { }
	// RVA: 0x210ecd0 VA: 0x7594726cd0
	private Material _CreateMatByNameIfNot(String shaderName, ref Material curMat) { }
	// RVA: 0x210eadc VA: 0x7594726adc
	private Material _GetOrCreateHighColorImgMat(Material baseMat) { }
	// RVA: 0x210eb64 VA: 0x7594726b64
	private Material _GetOrCreateLowColorImgMat(Material baseMat) { }
	// RVA: 0x210ebec VA: 0x7594726bec
	private Material _GetOrCreateAlphaOnlyImgMat(Material baseMat) { }
	// RVA: 0x210efa0 VA: 0x7594726fa0
	private Void _ClearCustomImgMats() { }
	// RVA: 0x210ee14 VA: 0x7594726e14
	private static Material _GetOrCreateImgMat(Material baseMat, Single weight, ref Material imgMat) { }
	// RVA: 0x210f018 VA: 0x7594727018
	private static Void _DestroyMat(ref Material imgMat) { }
	// RVA: 0x210f0f0 VA: 0x75947270f0
	private Void OnDestroy() { }
	// RVA: 0x210f31c VA: 0x759472731c
	private Void _OnBlurEnableStateChanged(Boolean isEnabled) { }
	// RVA: 0x210f530 VA: 0x7594727530
	public Void .ctor() { }
}
```