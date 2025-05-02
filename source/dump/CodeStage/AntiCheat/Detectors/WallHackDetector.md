# WallHackDetector

**Namespace:** `CodeStage.AntiCheat.Detectors`


## Fields

- `Boolean checkRigidbody`

- `Boolean checkController`

- `Boolean checkWireframe`

- `Boolean checkRaycast`

- `Int32 wireframeDelay`

- `Int32 raycastDelay`

- `Vector3 spawnPosition`

- `Byte maxFalsePositives`

- `GameObject serviceContainer`

- `GameObject solidWall`

- `GameObject thinWall`

- `Camera wfCamera`

- `MeshRenderer foregroundRenderer`

- `MeshRenderer backgroundRenderer`

- `Color wfColor1`

- `Color wfColor2`

- `Shader wfShader`

- `Material wfMaterial`

- `Texture2D shaderTexture`

- `Texture2D targetTexture`

- `RenderTexture renderTexture`

- `Int32 whLayer`

- `Int32 raycastMask`

- `Rigidbody rigidPlayer`

- `CharacterController charControllerPlayer`

- `Single charControllerVelocity`

- `Byte rigidbodyDetections`

- `Byte controllerDetections`

- `Byte wireframeDetections`

- `Byte raycastDetections`

- `Boolean wireframeDetected`


## Properties

- `Boolean CheckRigidbody`

- `Boolean CheckController`

- `Boolean CheckWireframe`

- `Boolean CheckRaycast`


## Methods

- `Boolean get_CheckRigidbody()`

- `Void set_CheckRigidbody(Boolean)`

- `Boolean get_CheckController()`

- `Void set_CheckController(Boolean)`

- `Boolean get_CheckWireframe()`

- `Void set_CheckWireframe(Boolean)`

- `Boolean get_CheckRaycast()`

- `Void set_CheckRaycast(Boolean)`

- `Void Awake()`

- `Void OnLevelWasLoadedNew(Scene, LoadSceneMode)`

- `Void OnLevelLoadedCallback()`

- `Void FixedUpdate()`

- `Void Update()`

- `Void StartDetectionInternal(Action, Vector3, Byte)`

- `Void UpdateServiceContainer()`

- `IEnumerator InitDetector()`

- `Void StartRigidModule()`

- `Void StartControllerModule()`

- `Void StartWireframeModule()`

- `Void ShootWireframeModule()`

- `IEnumerator CaptureFrame()`

- `Void StartRaycastModule()`

- `Void ShootRaycastModule()`

- `Void StopRigidModule()`

- `Void StopControllerModule()`

- `Void StopWireframeModule()`

- `Void StopRaycastModule()`

- `Void InitRigidModule()`

- `Void InitControllerModule()`

- `Void UninitRigidModule()`

- `Void UninitControllerModule()`

- `Boolean Detect()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : CodeStage.AntiCheat.Detectors
public class WallHackDetector : ActDetectorBase
{
	internal const String ComponentName; // 0x0
	internal const String FinalLogPrefix; // 0x0
	private const String ServiceContainerName; // 0x0
	private const String WireframeShaderName; // 0x0
	private const Int32 ShaderTextureSize; // 0x0
	private const Int32 RenderTextureSize; // 0x0
	private readonly Vector3 rigidPlayerVelocity; // 0x34
	private static Int32 instancesInScene; // 0x0
	private readonly WaitForEndOfFrame waitForEndOfFrame; // 0x40
	private Boolean checkRigidbody; // 0x48
	private Boolean checkController; // 0x49
	private Boolean checkWireframe; // 0x4a
	private Boolean checkRaycast; // 0x4b
	public Int32 wireframeDelay; // 0x4c
	public Int32 raycastDelay; // 0x50
	public Vector3 spawnPosition; // 0x54
	public Byte maxFalsePositives; // 0x60
	private GameObject serviceContainer; // 0x68
	private GameObject solidWall; // 0x70
	private GameObject thinWall; // 0x78
	private Camera wfCamera; // 0x80
	private MeshRenderer foregroundRenderer; // 0x88
	private MeshRenderer backgroundRenderer; // 0x90
	private Color wfColor1; // 0x98
	private Color wfColor2; // 0xa8
	private Shader wfShader; // 0xb8
	private Material wfMaterial; // 0xc0
	private Texture2D shaderTexture; // 0xc8
	private Texture2D targetTexture; // 0xd0
	private RenderTexture renderTexture; // 0xd8
	private Int32 whLayer; // 0xe0
	private Int32 raycastMask; // 0xe4
	private Rigidbody rigidPlayer; // 0xe8
	private CharacterController charControllerPlayer; // 0xf0
	private Single charControllerVelocity; // 0xf8
	private Byte rigidbodyDetections; // 0xfc
	private Byte controllerDetections; // 0xfd
	private Byte wireframeDetections; // 0xfe
	private Byte raycastDetections; // 0xff
	private Boolean wireframeDetected; // 0x100
	private readonly RaycastHit[] rayHits; // 0x108
	private static WallHackDetector <Instance>k__BackingField; // 0x8

	public Boolean CheckRigidbody { get; set; }
	public Boolean CheckController { get; set; }
	public Boolean CheckWireframe { get; set; }
	public Boolean CheckRaycast { get; set; }
	public static WallHackDetector Instance { get; set; }
	private static WallHackDetector GetOrCreateInstance { get; }

	// RVA: 0x66b6ab4 VA: 0x7598cceab4
	public Boolean get_CheckRigidbody() { }
	// RVA: 0x66b6abc VA: 0x7598cceabc
	public Void set_CheckRigidbody(Boolean value) { }
	// RVA: 0x66b84a0 VA: 0x7598cd04a0
	public Boolean get_CheckController() { }
	// RVA: 0x66b84a8 VA: 0x7598cd04a8
	public Void set_CheckController(Boolean value) { }
	// RVA: 0x66b86f4 VA: 0x7598cd06f4
	public Boolean get_CheckWireframe() { }
	// RVA: 0x66b86fc VA: 0x7598cd06fc
	public Void set_CheckWireframe(Boolean value) { }
	// RVA: 0x66b8870 VA: 0x7598cd0870
	public Boolean get_CheckRaycast() { }
	// RVA: 0x66b8878 VA: 0x7598cd0878
	public Void set_CheckRaycast(Boolean value) { }
	// RVA: 0x66b89d8 VA: 0x7598cd09d8
	public static WallHackDetector AddToSceneOrGetExisting() { }
	// RVA: 0x66b8bac VA: 0x7598cd0bac
	public static Void StartDetection() { }
	// RVA: 0x66b8e98 VA: 0x7598cd0e98
	public static Void StartDetection(Action callback) { }
	// RVA: 0x66b8ec0 VA: 0x7598cd0ec0
	public static Void StartDetection(Action callback, Vector3 spawnPosition) { }
	// RVA: 0x66b8f0c VA: 0x7598cd0f0c
	public static Void StartDetection(Action callback, Vector3 spawnPosition, Byte maxFalsePositives) { }
	// RVA: 0x66b8f64 VA: 0x7598cd0f64
	public static Void StopDetection() { }
	// RVA: 0x66b903c VA: 0x7598cd103c
	public static Void Dispose() { }
	// RVA: 0x66b9114 VA: 0x7598cd1114
	public static WallHackDetector get_Instance() { }
	// RVA: 0x66b915c VA: 0x7598cd115c
	private static Void set_Instance(WallHackDetector value) { }
	// RVA: 0x66b89dc VA: 0x7598cd09dc
	private static WallHackDetector get_GetOrCreateInstance() { }
	// RVA: 0x66b91ac VA: 0x7598cd11ac
	private Void .ctor() { }
	// RVA: 0x66b92a0 VA: 0x7598cd12a0
	private Void Awake() { }
	// RVA: 0x66b93fc VA: 0x7598cd13fc
	protected override Void OnDestroy() { }
	// RVA: 0x66b9590 VA: 0x7598cd1590
	private Void OnLevelWasLoadedNew(Scene scene, LoadSceneMode mode) { }
	// RVA: 0x66b9594 VA: 0x7598cd1594
	private Void OnLevelLoadedCallback() { }
	// RVA: 0x66b967c VA: 0x7598cd167c
	private Void FixedUpdate() { }
	// RVA: 0x66b97a8 VA: 0x7598cd17a8
	private Void Update() { }
	// RVA: 0x66b8ccc VA: 0x7598cd0ccc
	private Void StartDetectionInternal(Action callback, Vector3 servicePosition, Byte falsePositivesInRow) { }
	// RVA: 0x66b9930 VA: 0x7598cd1930
	protected override Void StartDetectionAutomatically() { }
	// RVA: 0x66b9944 VA: 0x7598cd1944
	protected override Void PauseDetector() { }
	// RVA: 0x66b998c VA: 0x7598cd198c
	protected override Boolean ResumeDetector() { }
	// RVA: 0x66b9a08 VA: 0x7598cd1a08
	protected override Void StopDetectionInternal() { }
	// RVA: 0x66b9a44 VA: 0x7598cd1a44
	protected override Void DisposeInternal() { }
	// RVA: 0x66b6b5c VA: 0x7598cceb5c
	private Void UpdateServiceContainer() { }
	// RVA: 0x66b98bc VA: 0x7598cd18bc
	private IEnumerator InitDetector() { }
	// RVA: 0x66b8204 VA: 0x7598cd0204
	private Void StartRigidModule() { }
	// RVA: 0x66b8548 VA: 0x7598cd0548
	private Void StartControllerModule() { }
	// RVA: 0x66b879c VA: 0x7598cd079c
	private Void StartWireframeModule() { }
	// RVA: 0x66ba06c VA: 0x7598cd206c
	private Void ShootWireframeModule() { }
	// RVA: 0x66ba0d8 VA: 0x7598cd20d8
	private IEnumerator CaptureFrame() { }
	// RVA: 0x66b8918 VA: 0x7598cd0918
	private Void StartRaycastModule() { }
	// RVA: 0x66ba174 VA: 0x7598cd2174
	private Void ShootRaycastModule() { }
	// RVA: 0x66b83cc VA: 0x7598cd03cc
	private Void StopRigidModule() { }
	// RVA: 0x66b866c VA: 0x7598cd066c
	private Void StopControllerModule() { }
	// RVA: 0x66b8824 VA: 0x7598cd0824
	private Void StopWireframeModule() { }
	// RVA: 0x66b898c VA: 0x7598cd098c
	private Void StopRaycastModule() { }
	// RVA: 0x66b9d2c VA: 0x7598cd1d2c
	private Void InitRigidModule() { }
	// RVA: 0x66b9f30 VA: 0x7598cd1f30
	private Void InitControllerModule() { }
	// RVA: 0x66b9c78 VA: 0x7598cd1c78
	private Void UninitRigidModule() { }
	// RVA: 0x66b9e7c VA: 0x7598cd1e7c
	private Void UninitControllerModule() { }
	// RVA: 0x66b9750 VA: 0x7598cd1750
	private Boolean Detect() { }
	// RVA: 0x66b9b20 VA: 0x7598cd1b20
	private static Color32 GenerateColor() { }
	// RVA: 0x66b9b78 VA: 0x7598cd1b78
	private static Boolean ColorsSimilar(Color32 c1, Color32 c2, Int32 tolerance) { }
}
```