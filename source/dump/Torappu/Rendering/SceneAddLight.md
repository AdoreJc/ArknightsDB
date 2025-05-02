# SceneAddLight

**Namespace:** `Torappu.Rendering`


## Fields

- `RenderTexture cookiesRT`

- `Boolean _needUpdate`

- `Shader _lightCookieMergeShader`

- `Boolean m_inited`

- `Int32 m_cookiesNum`

- `Material m_mergeMat`

- `Int32 m_addLightColorArrID`

- `Int32 m_addLightPosArrID`

- `Int32 m_addLightNumID`

- `Int32 m_addLightAngleID`

- `Int32 m_addLightDirID`

- `Int32 m_addLightCookie`

- `Int32 m_addWorldToLight`

- `Int32 m_addLightCookieID`


## Properties

- `Boolean addLightEnabled`

- `Int32 lightNum`

- `Boolean lightCookieEnabled`


## Methods

- `Boolean get_addLightEnabled()`

- `Int32 get_lightNum()`

- `Boolean get_lightCookieEnabled()`

- `Void _Init()`

- `Void _UpdateLight()`

- `Vector4 CalculateSpotData(Single, Single, LightType)`

- `Boolean _GetCookieAtlasTexture(Texture2D[], ref)`

- `Void Awake()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class SceneAddLight : BaseSceneEffect, IHotfixable
{
	private const Int32 RUNTIME_FIXED_LIGHT_NUM; // 0x0
	private const Int32 RUNTIME_LIGHT_COOKIE_NUM; // 0x0
	private RenderTexture cookiesRT; // 0x18
	private Boolean _needUpdate; // 0x20
	private Light[] _addtionalLights; // 0x28
	private Shader _lightCookieMergeShader; // 0x30
	public SpotLightConfig[] spotConfig; // 0x38
	private Boolean m_inited; // 0x40
	private Int32 m_cookiesNum; // 0x44
	private Material m_mergeMat; // 0x48
	private AddLight[] m_addLightData; // 0x50
	private Vector4[] m_lightList; // 0x58
	private Vector4[] m_lightPosList; // 0x60
	private Vector4[] m_lightAngleList; // 0x68
	private Vector4[] m_lightDirList; // 0x70
	private Matrix4x4[] m_worldToLight; // 0x78
	private Texture2D[] m_lightCookies; // 0x80
	private Vector4[] m_lightCookieIDs; // 0x88
	private Int32 m_addLightColorArrID; // 0x90
	private Int32 m_addLightPosArrID; // 0x94
	private Int32 m_addLightNumID; // 0x98
	private Int32 m_addLightAngleID; // 0x9c
	private Int32 m_addLightDirID; // 0xa0
	private Int32 m_addLightCookie; // 0xa4
	private Int32 m_addWorldToLight; // 0xa8
	private Int32 m_addLightCookieID; // 0xac
	private static readonly String[] cookiesName; // 0x0
	private static DelegateBridge __Hotfix0_get_addLightEnabled; // 0x8
	private static DelegateBridge __Hotfix0_get_lightNum; // 0x10
	private static DelegateBridge __Hotfix0_get_lightCookieEnabled; // 0x18
	private static DelegateBridge __Hotfix0__Init; // 0x20
	private static DelegateBridge __Hotfix0__UpdateLight; // 0x28
	private static DelegateBridge __Hotfix0_CalculateSpotData; // 0x30
	private static DelegateBridge __Hotfix0__GetCookieAtlasTexture; // 0x38
	private static DelegateBridge __Hotfix0_Awake; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Boolean addLightEnabled { get; }
	private Int32 lightNum { get; }
	private Boolean lightCookieEnabled { get; }

	// RVA: 0x3f01100 VA: 0x7596519100
	private Boolean get_addLightEnabled() { }
	// RVA: 0x3f011a0 VA: 0x75965191a0
	private Int32 get_lightNum() { }
	// RVA: 0x3f01228 VA: 0x7596519228
	private Boolean get_lightCookieEnabled() { }
	// RVA: 0x3f012ec VA: 0x75965192ec
	private Void _Init() { }
	// RVA: 0x3f01608 VA: 0x7596519608
	private Void _UpdateLight() { }
	// RVA: 0x3f02090 VA: 0x759651a090
	private Vector4 CalculateSpotData(Single innerSpotAngle, Single outerSpotAngle, LightType type) { }
	// RVA: 0x3f02178 VA: 0x759651a178
	private Boolean _GetCookieAtlasTexture(Texture2D[] cookies, ref RenderTexture target) { }
	// RVA: 0x3f023ec VA: 0x759651a3ec
	private Void Awake() { }
	// RVA: 0x3f02464 VA: 0x759651a464
	private Void OnDestroy() { }
	// RVA: 0x3f02548 VA: 0x759651a548
	public Void .ctor() { }
	// RVA: 0x3f02714 VA: 0x759651a714
	private static Void .cctor() { }
}
```