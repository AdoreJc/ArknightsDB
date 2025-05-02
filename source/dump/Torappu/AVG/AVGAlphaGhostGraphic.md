# AVGAlphaGhostGraphic

**Namespace:** `Torappu.AVG`


## Fields

- `CanvasGroup m_canvasGroup`

- `Texture m_mainTex`

- `Boolean m_isAlaphTex`

- `Int32 m_baseMatGUID`

- `Material m_material`

- `Texture m_dynTex`

- `Vector2 m_dynScale`

- `Vector2 m_dynOffset`

- `AlphaTracker m_alphaTracker`


## Methods

- `Void SetTextures(Textures)`

- `Void SetMaterial(Material)`

- `Void _SetMaterialImpl(Material)`

- `Void _SetHostImage(CanvasGroup, Image)`

- `Void _SetBaseAlpha(Single)`

- `Void OnDestroy()`

- `Texture <>xLuaBaseProxy_get_mainTexture()`

- `Material <>xLuaBaseProxy_get_material()`

- `Void <>xLuaBaseProxy_set_material(Material)`

- `Material <>xLuaBaseProxy_get_materialForRendering()`

- `Void <>xLuaBaseProxy_UpdateMaterial()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGAlphaGhostGraphic : Image, IHotfixable
{
	private CanvasGroup m_canvasGroup; // 0x188
	private Texture m_mainTex; // 0x190
	private Boolean m_isAlaphTex; // 0x198
	private Int32 m_baseMatGUID; // 0x19c
	private Material m_material; // 0x1a0
	private Texture m_dynTex; // 0x1a8
	private Vector2 m_dynScale; // 0x1b0
	private Vector2 m_dynOffset; // 0x1b8
	private AlphaTracker m_alphaTracker; // 0x1c0
	private SetWhenBind`2 m_setMatProps; // 0x1c8
	private static DelegateBridge __Hotfix0__SetMaterialParams; // 0x0
	private static DelegateBridge __Hotfix0_SetTextures; // 0x8
	private static DelegateBridge __Hotfix0_SetMaterial; // 0x10
	private static DelegateBridge __Hotfix0__SetMaterialImpl; // 0x18
	private static DelegateBridge __Hotfix0__SetHostImage; // 0x20
	private static DelegateBridge __Hotfix0__SetBaseAlpha; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0_get_mainTexture; // 0x38
	private static DelegateBridge __Hotfix0_get_material; // 0x40
	private static DelegateBridge __Hotfix0_set_material; // 0x48
	private static DelegateBridge __Hotfix0_get_materialForRendering; // 0x50
	private static DelegateBridge __Hotfix0_UpdateMaterial; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override Texture mainTexture { get; }
	public override Material material { get; set; }
	public override Material materialForRendering { get; }

	// RVA: 0x3e94b98 VA: 0x75964acb98
	private static Void _SetMaterialParams(Material mat, AVGAlphaGhostGraphic self) { }
	// RVA: 0x3e94cf4 VA: 0x75964accf4
	public Void SetTextures(Textures textures) { }
	// RVA: 0x3e950dc VA: 0x75964ad0dc
	public Void SetMaterial(Material material) { }
	// RVA: 0x3e951d0 VA: 0x75964ad1d0
	private Void _SetMaterialImpl(Material baseOrCurMaterial) { }
	// RVA: 0x3e95378 VA: 0x75964ad378
	private Void _SetHostImage(CanvasGroup canvasGroup, Image host) { }
	// RVA: 0x3e954b4 VA: 0x75964ad4b4
	private Void _SetBaseAlpha(Single alpha) { }
	// RVA: 0x3e9554c VA: 0x75964ad54c
	protected Void OnDestroy() { }
	// RVA: 0x3e95638 VA: 0x75964ad638
	public override Texture get_mainTexture() { }
	// RVA: 0x3e956a0 VA: 0x75964ad6a0
	public override Material get_material() { }
	// RVA: 0x3e95708 VA: 0x75964ad708
	public override Void set_material(Material value) { }
	// RVA: 0x3e95780 VA: 0x75964ad780
	public override Material get_materialForRendering() { }
	// RVA: 0x3e9583c VA: 0x75964ad83c
	protected override Void UpdateMaterial() { }
	// RVA: 0x3e95950 VA: 0x75964ad950
	public Void .ctor() { }
	// RVA: 0x3e95ad0 VA: 0x75964adad0
	private Texture <>xLuaBaseProxy_get_mainTexture() { }
	// RVA: 0x3e95ad8 VA: 0x75964adad8
	private Material <>xLuaBaseProxy_get_material() { }
	// RVA: 0x3e95ae0 VA: 0x75964adae0
	private Void <>xLuaBaseProxy_set_material(Material P0) { }
	// RVA: 0x3e95ae8 VA: 0x75964adae8
	private Material <>xLuaBaseProxy_get_materialForRendering() { }
	// RVA: 0x3e95af0 VA: 0x75964adaf0
	private Void <>xLuaBaseProxy_UpdateMaterial() { }
}
```