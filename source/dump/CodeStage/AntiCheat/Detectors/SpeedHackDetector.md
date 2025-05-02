# SpeedHackDetector

**Namespace:** `CodeStage.AntiCheat.Detectors`


## Fields

- `Single interval`

- `Byte maxFalsePositives`

- `Int32 coolDown`

- `Byte currentFalsePositives`

- `Int32 currentCooldownShots`

- `Int64 ticksOnStart`

- `Int64 vulnerableTicksOnStart`

- `Int64 previousTicks`

- `Int64 previousIntervalTicks`

- `Single vulnerableTimeOnStart`

- `AndroidJavaClass routinesClass`

- `Boolean androidTimeReadAttemptWasMade`


## Methods

- `Void Awake()`

- `Void OnLevelWasLoadedNew(Scene, LoadSceneMode)`

- `Void OnLevelLoadedCallback()`

- `Void OnApplicationPause(Boolean)`

- `Void Update()`

- `Void StartDetectionInternal(Action, Single, Byte, Int32)`

- `Void ResetStartTicks()`

- `Int64 GetReliableTicks()`

- `Int64 TryReadTicksFromAndroidRoutine()`

- `Void ReleaseAndroidClass()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : CodeStage.AntiCheat.Detectors
public class SpeedHackDetector : ActDetectorBase
{
	internal const String ComponentName; // 0x0
	internal const String LogPrefix; // 0x0
	private const Int64 TicksPerSecond; // 0x0
	private const Int32 Threshold; // 0x0
	private const Single ThresholdFloat; // 0x0
	private const String RoutinesClassPath; // 0x0
	private static Int32 instancesInScene; // 0x0
	public Single interval; // 0x34
	public Byte maxFalsePositives; // 0x38
	public Int32 coolDown; // 0x3c
	private Byte currentFalsePositives; // 0x40
	private Int32 currentCooldownShots; // 0x44
	private Int64 ticksOnStart; // 0x48
	private Int64 vulnerableTicksOnStart; // 0x50
	private Int64 previousTicks; // 0x58
	private Int64 previousIntervalTicks; // 0x60
	private Single vulnerableTimeOnStart; // 0x68
	private AndroidJavaClass routinesClass; // 0x70
	private Boolean androidTimeReadAttemptWasMade; // 0x78
	private static SpeedHackDetector <Instance>k__BackingField; // 0x8

	public static SpeedHackDetector Instance { get; set; }
	private static SpeedHackDetector GetOrCreateInstance { get; }

	// RVA: 0x66b2538 VA: 0x7598cca538
	public static SpeedHackDetector AddToSceneOrGetExisting() { }
	// RVA: 0x66b270c VA: 0x7598cca70c
	public static Void StartDetection() { }
	// RVA: 0x66b29d8 VA: 0x7598cca9d8
	public static Void StartDetection(Action callback) { }
	// RVA: 0x66b29fc VA: 0x7598cca9fc
	public static Void StartDetection(Action callback, Single interval) { }
	// RVA: 0x66b2a30 VA: 0x7598ccaa30
	public static Void StartDetection(Action callback, Single interval, Byte maxFalsePositives) { }
	// RVA: 0x66b2a74 VA: 0x7598ccaa74
	public static Void StartDetection(Action callback, Single interval, Byte maxFalsePositives, Int32 coolDown) { }
	// RVA: 0x66b2abc VA: 0x7598ccaabc
	public static Void StopDetection() { }
	// RVA: 0x66b2b94 VA: 0x7598ccab94
	public static Void Dispose() { }
	// RVA: 0x66b2c6c VA: 0x7598ccac6c
	public static SpeedHackDetector get_Instance() { }
	// RVA: 0x66b2cb4 VA: 0x7598ccacb4
	private static Void set_Instance(SpeedHackDetector value) { }
	// RVA: 0x66b253c VA: 0x7598cca53c
	private static SpeedHackDetector get_GetOrCreateInstance() { }
	// RVA: 0x66b2d04 VA: 0x7598ccad04
	private Void .ctor() { }
	// RVA: 0x66b2d34 VA: 0x7598ccad34
	private Void Awake() { }
	// RVA: 0x66b2e90 VA: 0x7598ccae90
	protected override Void OnDestroy() { }
	// RVA: 0x66b2eec VA: 0x7598ccaeec
	private Void OnLevelWasLoadedNew(Scene scene, LoadSceneMode mode) { }
	// RVA: 0x66b2ef0 VA: 0x7598ccaef0
	private Void OnLevelLoadedCallback() { }
	// RVA: 0x66b2fd8 VA: 0x7598ccafd8
	private Void OnApplicationPause(Boolean pause) { }
	// RVA: 0x66b3024 VA: 0x7598ccb024
	private Void Update() { }
	// RVA: 0x66b282c VA: 0x7598cca82c
	private Void StartDetectionInternal(Action callback, Single checkInterval, Byte falsePositives, Int32 shotsTillCooldown) { }
	// RVA: 0x66b3258 VA: 0x7598ccb258
	protected override Void StartDetectionAutomatically() { }
	// RVA: 0x66b326c VA: 0x7598ccb26c
	protected override Void DisposeInternal() { }
	// RVA: 0x66b2fe4 VA: 0x7598ccafe4
	private Void ResetStartTicks() { }
	// RVA: 0x66b31e0 VA: 0x7598ccb1e0
	private Int64 GetReliableTicks() { }
	// RVA: 0x66b336c VA: 0x7598ccb36c
	private Int64 TryReadTicksFromAndroidRoutine() { }
	// RVA: 0x66b3350 VA: 0x7598ccb350
	private Void ReleaseAndroidClass() { }
}
```