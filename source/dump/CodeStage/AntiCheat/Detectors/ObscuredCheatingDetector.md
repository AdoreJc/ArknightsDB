# ObscuredCheatingDetector

**Namespace:** `CodeStage.AntiCheat.Detectors`


## Fields

- `Double doubleEpsilon`

- `Single floatEpsilon`

- `Single vector2Epsilon`

- `Single vector3Epsilon`

- `Single quaternionEpsilon`


## Methods

- `Void Awake()`

- `Void OnLevelWasLoadedNew(Scene, LoadSceneMode)`

- `Void OnLevelLoadedCallback()`

- `Void StartDetectionInternal(Action)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : CodeStage.AntiCheat.Detectors
public class ObscuredCheatingDetector : ActDetectorBase
{
	internal const String ComponentName; // 0x0
	internal const String FinalLogPrefix; // 0x0
	private static Int32 instancesInScene; // 0x0
	public Double doubleEpsilon; // 0x38
	public Single floatEpsilon; // 0x40
	public Single vector2Epsilon; // 0x44
	public Single vector3Epsilon; // 0x48
	public Single quaternionEpsilon; // 0x4c
	private static ObscuredCheatingDetector <Instance>k__BackingField; // 0x8

	public static ObscuredCheatingDetector Instance { get; set; }
	private static ObscuredCheatingDetector GetOrCreateInstance { get; }
	internal static Boolean ExistsAndIsRunning { get; }

	// RVA: 0x66b1ac4 VA: 0x7598cc9ac4
	public static ObscuredCheatingDetector AddToSceneOrGetExisting() { }
	// RVA: 0x66b1c98 VA: 0x7598cc9c98
	public static Void StartDetection() { }
	// RVA: 0x66b1f10 VA: 0x7598cc9f10
	public static Void StartDetection(Action callback) { }
	// RVA: 0x66b1f30 VA: 0x7598cc9f30
	public static Void StopDetection() { }
	// RVA: 0x66b2008 VA: 0x7598cca008
	public static Void Dispose() { }
	// RVA: 0x66b20e0 VA: 0x7598cca0e0
	public static ObscuredCheatingDetector get_Instance() { }
	// RVA: 0x66b2128 VA: 0x7598cca128
	private static Void set_Instance(ObscuredCheatingDetector value) { }
	// RVA: 0x66b1ac8 VA: 0x7598cc9ac8
	private static ObscuredCheatingDetector get_GetOrCreateInstance() { }
	// RVA: 0x66a4f30 VA: 0x7598cbcf30
	internal static Boolean get_ExistsAndIsRunning() { }
	// RVA: 0x66b2178 VA: 0x7598cca178
	private Void .ctor() { }
	// RVA: 0x66b21b0 VA: 0x7598cca1b0
	private Void Awake() { }
	// RVA: 0x66b230c VA: 0x7598cca30c
	protected override Void OnDestroy() { }
	// RVA: 0x66b2368 VA: 0x7598cca368
	private Void OnLevelWasLoadedNew(Scene scene, LoadSceneMode mode) { }
	// RVA: 0x66b236c VA: 0x7598cca36c
	private Void OnLevelLoadedCallback() { }
	// RVA: 0x66b1dac VA: 0x7598cc9dac
	private Void StartDetectionInternal(Action callback) { }
	// RVA: 0x66b2454 VA: 0x7598cca454
	protected override Void StartDetectionAutomatically() { }
	// RVA: 0x66b245c VA: 0x7598cca45c
	protected override Void DisposeInternal() { }
}
```