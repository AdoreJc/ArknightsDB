# BlurScreenTexGenerator

**Namespace:** `Torappu`


## Fields

- `Int32 m_targetBlurLevel`

- `Int32 m_downSample`

- `String m_outputTextureName`

- `Material m_blurMat`

- `BlurMode m_blurMode`

- `Camera m_camera`

- `CommandBuffer m_commandBuffer`

- `Vector2Int m_fullScreenSize`

- `Vector2Int m_initScreenSize`

- `Int32 m_blurLevel`

- `Boolean m_keepCameraTarget`

- `RenderTexture m_cameraTarget`

- `Boolean m_isEnabled`

- `Boolean m_hasConfig`


## Properties

- `Boolean initialized`

- `Int32 blurLevel`


## Methods

- `Boolean CheckIfTexEnabled()`

- `Boolean get_initialized()`

- `Void SetConfig(Config)`

- `Void SetBlurLevel(Int32)`

- `Int32 get_blurLevel()`

- `Void _Cleanup()`

- `Boolean _InitIfNot()`

- `Void _MarkEnabled(Boolean)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BlurScreenTexGenerator : MonoBehaviour, IHotfixable
{
	private const Int32 BLUR_LEVEL_MIN; // 0x0
	private const Int32 BLUR_LEVEL_MAX; // 0x0
	private const String BLUR_SAHDER; // 0x0
	private const RenderTextureFormat TEX_FORMAT; // 0x0
	private const CameraEvent CAMERA_EVT; // 0x0
	private const Single BLUR_GUASSIAN_SIZE; // 0x0
	private Int32 m_targetBlurLevel; // 0x18
	private Int32 m_downSample; // 0x1c
	private String m_outputTextureName; // 0x20
	private Material m_blurMat; // 0x28
	private BlurMode m_blurMode; // 0x30
	private Camera m_camera; // 0x38
	private CommandBuffer m_commandBuffer; // 0x40
	private Vector2Int m_fullScreenSize; // 0x48
	private Vector2Int m_initScreenSize; // 0x50
	private Int32 m_blurLevel; // 0x58
	private Action`1 m_onEnableStateChanged; // 0x60
	private Boolean m_keepCameraTarget; // 0x68
	private RenderTexture m_cameraTarget; // 0x70
	private Boolean m_isEnabled; // 0x78
	private Boolean m_hasConfig; // 0x79
	private static DelegateBridge __Hotfix0_CheckIfTexEnabled; // 0x0
	private static DelegateBridge __Hotfix0_get_initialized; // 0x8
	private static DelegateBridge __Hotfix0_SetConfig; // 0x10
	private static DelegateBridge __Hotfix0_SetBlurLevel; // 0x18
	private static DelegateBridge __Hotfix0_get_blurLevel; // 0x20
	private static DelegateBridge __Hotfix0__Cleanup; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__MarkEnabled; // 0x38
	private static DelegateBridge __Hotfix0__CommandOutputGlassMode; // 0x40
	private static DelegateBridge __Hotfix0__CommandOutputGuassianMode; // 0x48
	private static DelegateBridge __Hotfix0_OnEnable; // 0x50
	private static DelegateBridge __Hotfix0_OnDisable; // 0x58
	private static DelegateBridge __Hotfix0_Update; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private Boolean initialized { get; }
	public Int32 blurLevel { get; }

	// RVA: 0x32c716c VA: 0x75958df16c
	public Boolean CheckIfTexEnabled() { }
	// RVA: 0x32c71d4 VA: 0x75958df1d4
	private Boolean get_initialized() { }
	// RVA: 0x32c7244 VA: 0x75958df244
	public Void SetConfig(Config config) { }
	// RVA: 0x32c7488 VA: 0x75958df488
	public Void SetBlurLevel(Int32 blurLevel) { }
	// RVA: 0x32c7538 VA: 0x75958df538
	public Int32 get_blurLevel() { }
	// RVA: 0x32c7350 VA: 0x75958df350
	private Void _Cleanup() { }
	// RVA: 0x32c75a0 VA: 0x75958df5a0
	private Boolean _InitIfNot() { }
	// RVA: 0x32c8128 VA: 0x75958e0128
	private Void _MarkEnabled(Boolean enable) { }
	// RVA: 0x32c7d2c VA: 0x75958dfd2c
	private static Void _CommandOutputGlassMode(CommandBuffer cmd, RenderTargetIdentifier srcRT, Material mat, Vector2 size, Int32 blurLevel, String outputTexName) { }
	// RVA: 0x32c793c VA: 0x75958df93c
	private static Void _CommandOutputGuassianMode(CommandBuffer cmd, RenderTargetIdentifier srcRT, Material mat, Vector2 size, Int32 blurLevel, String outputTexName) { }
	// RVA: 0x32c81e0 VA: 0x75958e01e0
	public Void OnEnable() { }
	// RVA: 0x32c826c VA: 0x75958e026c
	public Void OnDisable() { }
	// RVA: 0x32c82e0 VA: 0x75958e02e0
	private Void Update() { }
	// RVA: 0x32c83b0 VA: 0x75958e03b0
	public Void .ctor() { }
}
```