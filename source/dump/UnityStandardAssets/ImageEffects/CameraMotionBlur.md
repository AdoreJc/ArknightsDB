# CameraMotionBlur

**Namespace:** `UnityStandardAssets.ImageEffects`


## Fields

- `MotionBlurFilter filterType`

- `Boolean preview`

- `Vector3 previewScale`

- `Single movementScale`

- `Single rotationScale`

- `Single maxVelocity`

- `Single minVelocity`

- `Single velocityScale`

- `Single softZDistance`

- `Int32 velocityDownsample`

- `LayerMask excludeLayers`

- `GameObject tmpCam`

- `Shader shader`

- `Shader dx11MotionBlurShader`

- `Shader replacementClear`

- `Material motionBlurMaterial`

- `Material dx11MotionBlurMaterial`

- `Texture2D noiseTexture`

- `Single jitter`

- `Boolean showVelocity`

- `Single showVelocityScale`

- `Matrix4x4 currentViewProjMat`

- `Matrix4x4 prevViewProjMat`

- `Int32 prevFrameCount`

- `Boolean wasActive`

- `Vector3 prevFrameForward`

- `Vector3 prevFrameUp`

- `Vector3 prevFramePos`

- `Camera _camera`


## Methods

- `Void CalculateViewProjection()`

- `Void Start()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnRenderImage(RenderTexture, RenderTexture)`

- `Void Remember()`

- `Camera GetTmpCam()`

- `Void StartFrame()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityStandardAssets.ImageEffects
public class CameraMotionBlur : PostEffectsBase
{
	private static Single MAX_RADIUS; // 0x0
	public MotionBlurFilter filterType; // 0x28
	public Boolean preview; // 0x2c
	public Vector3 previewScale; // 0x30
	public Single movementScale; // 0x3c
	public Single rotationScale; // 0x40
	public Single maxVelocity; // 0x44
	public Single minVelocity; // 0x48
	public Single velocityScale; // 0x4c
	public Single softZDistance; // 0x50
	public Int32 velocityDownsample; // 0x54
	public LayerMask excludeLayers; // 0x58
	private GameObject tmpCam; // 0x60
	public Shader shader; // 0x68
	public Shader dx11MotionBlurShader; // 0x70
	public Shader replacementClear; // 0x78
	private Material motionBlurMaterial; // 0x80
	private Material dx11MotionBlurMaterial; // 0x88
	public Texture2D noiseTexture; // 0x90
	public Single jitter; // 0x98
	public Boolean showVelocity; // 0x9c
	public Single showVelocityScale; // 0xa0
	private Matrix4x4 currentViewProjMat; // 0xa4
	private Matrix4x4[] currentStereoViewProjMat; // 0xe8
	private Matrix4x4 prevViewProjMat; // 0xf0
	private Matrix4x4[] prevStereoViewProjMat; // 0x130
	private Int32 prevFrameCount; // 0x138
	private Boolean wasActive; // 0x13c
	private Vector3 prevFrameForward; // 0x140
	private Vector3 prevFrameUp; // 0x14c
	private Vector3 prevFramePos; // 0x158
	private Camera _camera; // 0x168


	// RVA: 0x64737bc VA: 0x7598a8b7bc
	private Void CalculateViewProjection() { }
	// RVA: 0x6473a1c VA: 0x7598a8ba1c
	private Void Start() { }
	// RVA: 0x6473cac VA: 0x7598a8bcac
	private Void OnEnable() { }
	// RVA: 0x6473d6c VA: 0x7598a8bd6c
	private Void OnDisable() { }
	// RVA: 0x6473ed0 VA: 0x7598a8bed0
	public override Boolean CheckResources() { }
	// RVA: 0x6473f84 VA: 0x7598a8bf84
	private Void OnRenderImage(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x6473b4c VA: 0x7598a8bb4c
	private Void Remember() { }
	// RVA: 0x6475ad8 VA: 0x7598a8dad8
	private Camera GetTmpCam() { }
	// RVA: 0x6475a54 VA: 0x7598a8da54
	private Void StartFrame() { }
	// RVA: 0x6475ac8 VA: 0x7598a8dac8
	private static Int32 divRoundUp(Int32 x, Int32 d) { }
	// RVA: 0x6475e6c VA: 0x7598a8de6c
	public Void .ctor() { }
	// RVA: 0x6475fb8 VA: 0x7598a8dfb8
	private static Void .cctor() { }
}
```