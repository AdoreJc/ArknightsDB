# OverdrawMonitor

**Namespace:** ` `


## Fields

- `Camera camera`

- `RenderTexture overdrawTexture`

- `ComputeShader computeShader`

- `ComputeBuffer resultBuffer`

- `Shader replacementShader`

- `Int64 <TotalShadedFragments>k__BackingField`

- `Single <OverdrawRatio>k__BackingField`

- `Int64 <IntervalShadedFragments>k__BackingField`

- `Single <IntervalAverageShadedFragments>k__BackingField`

- `Single <IntervalAverageOverdraw>k__BackingField`

- `Single <MaxOverdraw>k__BackingField`

- `Int64 accumulatedIntervalFragments`

- `Single accumulatedIntervalOverdraw`

- `Int64 intervalFrames`

- `Single intervalTime`

- `Single SampleTime`

- `Boolean disabled`


## Properties

- `Int64 TotalShadedFragments`

- `Single OverdrawRatio`

- `Int64 IntervalShadedFragments`

- `Single IntervalAverageShadedFragments`

- `Single IntervalAverageOverdraw`

- `Single AccumulatedAverageOverdraw`

- `Single MaxOverdraw`


## Methods

- `Int64 get_TotalShadedFragments()`

- `Void set_TotalShadedFragments(Int64)`

- `Single get_OverdrawRatio()`

- `Void set_OverdrawRatio(Single)`

- `Int64 get_IntervalShadedFragments()`

- `Void set_IntervalShadedFragments(Int64)`

- `Single get_IntervalAverageShadedFragments()`

- `Void set_IntervalAverageShadedFragments(Single)`

- `Single get_IntervalAverageOverdraw()`

- `Void set_IntervalAverageOverdraw(Single)`

- `Single get_AccumulatedAverageOverdraw()`

- `Single get_MaxOverdraw()`

- `Void set_MaxOverdraw(Single)`

- `Void Touch()`

- `Void Awake()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void LateUpdate()`

- `Void RecreateTexture(Camera)`

- `Void RecreateComputeBuffer()`

- `Void OnDestroy()`

- `Void OnPostRender()`

- `Void StartMeasurement()`

- `Void Start()`

- `Void Stop()`

- `Void SetSampleTime(Single)`

- `Void ResetSampling()`

- `Void ResetExtreemes()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class OverdrawMonitor : MonoBehaviour
{
	private static OverdrawMonitor instance; // 0x0
	public static Camera targetCamera; // 0x8
	private Camera camera; // 0x18
	private RenderTexture overdrawTexture; // 0x20
	private ComputeShader computeShader; // 0x28
	private const Int32 dataSize; // 0x0
	private Int32[] inputData; // 0x30
	private Int32[] resultData; // 0x38
	private ComputeBuffer resultBuffer; // 0x40
	private Shader replacementShader; // 0x48
	private Int64 <TotalShadedFragments>k__BackingField; // 0x50
	private Single <OverdrawRatio>k__BackingField; // 0x58
	private Int64 <IntervalShadedFragments>k__BackingField; // 0x60
	private Single <IntervalAverageShadedFragments>k__BackingField; // 0x68
	private Single <IntervalAverageOverdraw>k__BackingField; // 0x6c
	private Single <MaxOverdraw>k__BackingField; // 0x70
	private Int64 accumulatedIntervalFragments; // 0x78
	private Single accumulatedIntervalOverdraw; // 0x80
	private Int64 intervalFrames; // 0x88
	private Single intervalTime; // 0x90
	public Single SampleTime; // 0x94
	private Boolean disabled; // 0x98

	public static OverdrawMonitor Instance { get; }
	public Int64 TotalShadedFragments { get; set; }
	public Single OverdrawRatio { get; set; }
	public Int64 IntervalShadedFragments { get; set; }
	public Single IntervalAverageShadedFragments { get; set; }
	public Single IntervalAverageOverdraw { get; set; }
	public Single AccumulatedAverageOverdraw { get; }
	public Single MaxOverdraw { get; set; }
	public static Boolean HasInstance { get; }

	// RVA: 0x645c71c VA: 0x7598a7471c
	public static OverdrawMonitor get_Instance() { }
	// RVA: 0x645c890 VA: 0x7598a74890
	public Int64 get_TotalShadedFragments() { }
	// RVA: 0x645c898 VA: 0x7598a74898
	private Void set_TotalShadedFragments(Int64 value) { }
	// RVA: 0x645c8a0 VA: 0x7598a748a0
	public Single get_OverdrawRatio() { }
	// RVA: 0x645c8a8 VA: 0x7598a748a8
	private Void set_OverdrawRatio(Single value) { }
	// RVA: 0x645c8b0 VA: 0x7598a748b0
	public Int64 get_IntervalShadedFragments() { }
	// RVA: 0x645c8b8 VA: 0x7598a748b8
	private Void set_IntervalShadedFragments(Int64 value) { }
	// RVA: 0x645c8c0 VA: 0x7598a748c0
	public Single get_IntervalAverageShadedFragments() { }
	// RVA: 0x645c8c8 VA: 0x7598a748c8
	private Void set_IntervalAverageShadedFragments(Single value) { }
	// RVA: 0x645c8d0 VA: 0x7598a748d0
	public Single get_IntervalAverageOverdraw() { }
	// RVA: 0x645c8d8 VA: 0x7598a748d8
	private Void set_IntervalAverageOverdraw(Single value) { }
	// RVA: 0x645c8e0 VA: 0x7598a748e0
	public Single get_AccumulatedAverageOverdraw() { }
	// RVA: 0x645c8f4 VA: 0x7598a748f4
	public Single get_MaxOverdraw() { }
	// RVA: 0x645c8fc VA: 0x7598a748fc
	private Void set_MaxOverdraw(Single value) { }
	// RVA: 0x645c904 VA: 0x7598a74904
	public static Boolean get_HasInstance() { }
	// RVA: 0x645c97c VA: 0x7598a7497c
	public Void Touch() { }
	// RVA: 0x645c980 VA: 0x7598a74980
	public Void Awake() { }
	// RVA: 0x645ce58 VA: 0x7598a74e58
	public Void OnEnable() { }
	// RVA: 0x645ce60 VA: 0x7598a74e60
	public Void OnDisable() { }
	// RVA: 0x645cf04 VA: 0x7598a74f04
	public Void LateUpdate() { }
	// RVA: 0x645cbcc VA: 0x7598a74bcc
	private Void RecreateTexture(Camera main) { }
	// RVA: 0x645cdc8 VA: 0x7598a74dc8
	private Void RecreateComputeBuffer() { }
	// RVA: 0x645ce6c VA: 0x7598a74e6c
	public Void OnDestroy() { }
	// RVA: 0x645d0b0 VA: 0x7598a750b0
	public Void OnPostRender() { }
	// RVA: 0x645d2c0 VA: 0x7598a752c0
	public Void StartMeasurement() { }
	// RVA: 0x645d2f0 VA: 0x7598a752f0
	public Void Start() { }
	// RVA: 0x645d334 VA: 0x7598a75334
	public Void Stop() { }
	// RVA: 0x645d3f0 VA: 0x7598a753f0
	public Void SetSampleTime(Single time) { }
	// RVA: 0x645d318 VA: 0x7598a75318
	public Void ResetSampling() { }
	// RVA: 0x645d32c VA: 0x7598a7532c
	public Void ResetExtreemes() { }
	// RVA: 0x645d3f8 VA: 0x7598a753f8
	public Void .ctor() { }
}
```