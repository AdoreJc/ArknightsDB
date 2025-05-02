# AVGSceneEffectManager

**Namespace:** `Torappu.AVG`


## Fields

- `InitOptions m_initOptions`

- `Boolean m_isUpdating`

- `PostDisplayGroup m_postDisplayItems`

- `CommandBuffer m_cmd`

- `TickFunction m_updateTick`

- `RenderTextureDescriptor m_sourceDesc`


## Methods

- `Void UpdateEffect(EffectConfig)`

- `Single GetEffectAmount(String, String)`

- `PostDisplayHandler BindPostDisplay(PostDisplayKey)`

- `Void Dispose()`

- `Void _UpdateTick(Single)`

- `Void _InitEffectImpls()`

- `Void _SetEffectAmount(EffectConfig)`

- `Void _InterruptTweens(String, List`1)`

- `Void _InvokeCallbackAndRelease(TweenAction)`

- `Void _SetUpdateEnable(Boolean)`

- `Void _OnAllTweensFinished()`

- `Void _UpdateCommandStatus()`

- `Void _ClearCommandBuffer()`

- `Void _UpdateCommandBufferStatus(Boolean, Boolean)`

- `Void _RebuildCommandBuffer()`

- `Material _LoadMaterial(String)`

- `RenderTargetIdentifier _RequireTempRT(String)`

- `Void _ReleaseTempRT(RenderTargetIdentifier)`

- `Void _BuiltinBlit(CommandBuffer, RenderTargetIdentifier, RenderTargetIdentifier)`

- `Void _TestOnlyBlitToProfileRT(CommandBuffer, RenderTargetIdentifier)`

- `Int32 _PropertyToID(String)`

- `RenderTextureDescriptor _EnsureSourceDesc()`

- `RenderTextureDescriptor _CreateRTDesc(Int32)`

- `RTInfo _GetOrCreateRT(String)`

- `RenderTargetIdentifier _GetOrCreateScreenDefaultRT()`

- `ILoadAsset GetAssetLoader()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGSceneEffectManager : IHotfixable, IDisposable, IHost
{
	public const String KEY_GRAYSCALE; // 0x0
	public const String KEY_FOCUSOUT; // 0x0
	public const String CH_DEFAULT; // 0x0
	public const String RT_DOWNSAMPLE0; // 0x0
	public const String RT_DOWNSAMPLE1; // 0x0
	public const String RT_SCREEN0; // 0x0
	private const String RT_SCREEN_DFT; // 0x0
	private const Int32 DS_LVL_BLUR; // 0x0
	private const Int32 DS_LVL_SCREEN; // 0x0
	private const String CMD_NAME; // 0x0
	private const CameraEvent CMD_EVT; // 0x0
	private readonly RenderTargetIdentifier CAMERA_TARGET; // 0x10
	private static readonly String[] EFFECT_ORDER; // 0x0
	private InitOptions m_initOptions; // 0x38
	private Dictionary`2 m_effectImpls; // 0x50
	private Dictionary`2 m_activeChannels; // 0x58
	private List`1 m_cacheChannels; // 0x60
	private List`1 m_activeTweens; // 0x68
	private LocalGenericPool`1 m_tweenPool; // 0x70
	private LocalGenericPool`1 m_callbackPool; // 0x78
	private Boolean m_isUpdating; // 0x80
	private PostDisplayGroup m_postDisplayItems; // 0x88
	private CommandBuffer m_cmd; // 0x90
	private List`1 m_activeEffects; // 0x98
	private TickFunction m_updateTick; // 0xa0
	private List`1 m_activeRTs; // 0xa8
	private LocalGenericPool`1 m_RTInfoPool; // 0xb0
	private Dictionary`2 m_propertyToID; // 0xb8
	private RenderTextureDescriptor m_sourceDesc; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_UpdateEffect; // 0x10
	private static DelegateBridge __Hotfix0_GetEffectAmount; // 0x18
	private static DelegateBridge __Hotfix0_BindPostDisplay; // 0x20
	private static DelegateBridge __Hotfix0_Dispose; // 0x28
	private static DelegateBridge __Hotfix0__UpdateTick; // 0x30
	private static DelegateBridge __Hotfix0__InitEffectImpls; // 0x38
	private static DelegateBridge __Hotfix0__SetEffectAmount; // 0x40
	private static DelegateBridge __Hotfix0__InterruptTweens; // 0x48
	private static DelegateBridge __Hotfix0__InvokeCallbackAndRelease; // 0x50
	private static DelegateBridge __Hotfix0__SetUpdateEnable; // 0x58
	private static DelegateBridge __Hotfix0__OnAllTweensFinished; // 0x60
	private static DelegateBridge __Hotfix0__UpdateCommandStatus; // 0x68
	private static DelegateBridge __Hotfix0__ClearCommandBuffer; // 0x70
	private static DelegateBridge __Hotfix0__UpdateCommandBufferStatus; // 0x78
	private static DelegateBridge __Hotfix0__RebuildCommandBuffer; // 0x80
	private static DelegateBridge __Hotfix0__LoadMaterial; // 0x88
	private static DelegateBridge __Hotfix0__RequireTempRT; // 0x90
	private static DelegateBridge __Hotfix0__ReleaseTempRT; // 0x98
	private static DelegateBridge __Hotfix0__BuiltinBlit; // 0xa0
	private static DelegateBridge __Hotfix0__TestOnlyBlitToProfileRT; // 0xa8
	private static DelegateBridge __Hotfix0__PropertyToID; // 0xb0
	private static DelegateBridge __Hotfix0__EnsureSourceDesc; // 0xb8
	private static DelegateBridge __Hotfix0__CreateRTDesc; // 0xc0
	private static DelegateBridge __Hotfix0__GetOrCreateRT; // 0xc8
	private static DelegateBridge __Hotfix0__GetOrCreateScreenDefaultRT; // 0xd0
	private static DelegateBridge __Hotfix0_GetAssetLoader; // 0xd8


	// RVA: 0x3e9678c VA: 0x75964ae78c
	public Void .ctor(InitOptions initOptions) { }
	// RVA: 0x3e96fac VA: 0x75964aefac
	public Void UpdateEffect(EffectConfig config) { }
	// RVA: 0x3e97e0c VA: 0x75964afe0c
	public Single GetEffectAmount(String key, String channel) { }
	// RVA: 0x3e97ee8 VA: 0x75964afee8
	public PostDisplayHandler BindPostDisplay(PostDisplayKey key) { }
	// RVA: 0x3e984e8 VA: 0x75964b04e8
	public Void Dispose() { }
	// RVA: 0x3e987e4 VA: 0x75964b07e4
	private Void _UpdateTick(Single delta) { }
	// RVA: 0x3e96bf8 VA: 0x75964aebf8
	private Void _InitEffectImpls() { }
	// RVA: 0x3e971ac VA: 0x75964af1ac
	private Void _SetEffectAmount(EffectConfig config) { }
	// RVA: 0x3e98ed8 VA: 0x75964b0ed8
	private Void _InterruptTweens(String key, List`1 channels) { }
	// RVA: 0x3e989dc VA: 0x75964b09dc
	private Void _InvokeCallbackAndRelease(TweenAction tween) { }
	// RVA: 0x3e98acc VA: 0x75964b0acc
	private Void _SetUpdateEnable(Boolean enable) { }
	// RVA: 0x3e98c50 VA: 0x75964b0c50
	private Void _OnAllTweensFinished() { }
	// RVA: 0x3e977b8 VA: 0x75964af7b8
	private Void _UpdateCommandStatus() { }
	// RVA: 0x3e986e8 VA: 0x75964b06e8
	private Void _ClearCommandBuffer() { }
	// RVA: 0x3e990b8 VA: 0x75964b10b8
	private Void _UpdateCommandBufferStatus(Boolean prevActive, Boolean curActive) { }
	// RVA: 0x3e99258 VA: 0x75964b1258
	private Void _RebuildCommandBuffer() { }
	// RVA: 0x3e99ad4 VA: 0x75964b1ad4
	private Material _LoadMaterial(String resPath) { }
	// RVA: 0x3e99c00 VA: 0x75964b1c00
	private RenderTargetIdentifier _RequireTempRT(String key) { }
	// RVA: 0x3e997f0 VA: 0x75964b17f0
	private Void _ReleaseTempRT(RenderTargetIdentifier rt) { }
	// RVA: 0x3e999b8 VA: 0x75964b19b8
	private Void _BuiltinBlit(CommandBuffer cmd, RenderTargetIdentifier src, RenderTargetIdentifier dst) { }
	// RVA: 0x3e9a288 VA: 0x75964b2288
	private Void _TestOnlyBlitToProfileRT(CommandBuffer cmd, RenderTargetIdentifier src) { }
	// RVA: 0x3e9a190 VA: 0x75964b2190
	private Int32 _PropertyToID(String key) { }
	// RVA: 0x3e9a3dc VA: 0x75964b23dc
	private RenderTextureDescriptor _EnsureSourceDesc() { }
	// RVA: 0x3e9a5b4 VA: 0x75964b25b4
	private RenderTextureDescriptor _CreateRTDesc(Int32 downsampleLevel) { }
	// RVA: 0x3e99cd4 VA: 0x75964b1cd4
	private RTInfo _GetOrCreateRT(String key) { }
	// RVA: 0x3e99714 VA: 0x75964b1714
	private RenderTargetIdentifier _GetOrCreateScreenDefaultRT() { }
	// RVA: 0x3e9a730 VA: 0x75964b2730
	public ILoadAsset GetAssetLoader() { }
	// RVA: 0x3e9a7a8 VA: 0x75964b27a8
	private static Void .cctor() { }
}
```