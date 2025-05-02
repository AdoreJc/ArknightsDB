# CriAtomExAsrRack

**Namespace:** `CriWare`


## Fields

- `Int32 _rackId`

- `Boolean hasExistingRackId`


## Properties

- `Int32 rackId`


## Methods

- `Void AttachDspBusSetting(String)`

- `Void DetachDspBusSetting()`

- `Void ApplyDspBusSnapshot(String, Int32)`

- `String GetAppliedDspBusSnapshotName()`

- `PerformanceInfo GetPerformanceInfo()`

- `Void ResetPerformanceMonitor()`

- `Int32 get_rackId()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExAsrRack : CriDisposable
{
	public const Int32 defaultRackId; // 0x0
	public const Int32 IllegalRackId; // 0x0
	private Int32 _rackId; // 0x20
	private Boolean hasExistingRackId; // 0x24

	public Int32 rackId { get; }
	public static Config defaultConfig { get; }

	// RVA: 0x4110e94 VA: 0x7596728e94
	public static Void SetDefaultConfig_ANDROID(ref PlatformConfigAndroid platformConfig) { }
	// RVA: 0x4110f38 VA: 0x7596728f38
	public Void .ctor(Config config, IPlatformConfig platformConfig) { }
	// RVA: 0x411120c VA: 0x759672920c
	public Void .ctor(Config config, PlatformConfig platformConfig) { }
	// RVA: 0x41113e0 VA: 0x75967293e0
	public Void .ctor(Int32 existingRackId) { }
	// RVA: 0x41114b4 VA: 0x75967294b4
	public Void AttachDspBusSetting(String settingName) { }
	// RVA: 0x41115c8 VA: 0x75967295c8
	public Void DetachDspBusSetting() { }
	// RVA: 0x411164c VA: 0x759672964c
	public Void ApplyDspBusSnapshot(String snapshotName, Int32 timeMs) { }
	// RVA: 0x41116fc VA: 0x75967296fc
	public static String GetAppliedDspBusSnapshotName(Int32 rackId) { }
	// RVA: 0x4111818 VA: 0x7596729818
	public String GetAppliedDspBusSnapshotName() { }
	// RVA: 0x41118b8 VA: 0x75967298b8
	public PerformanceInfo GetPerformanceInfo() { }
	// RVA: 0x41119e8 VA: 0x75967299e8
	public static PerformanceInfo GetPerformanceInfoByRackId(Int32 rackId) { }
	// RVA: 0x4111a24 VA: 0x7596729a24
	public Void ResetPerformanceMonitor() { }
	// RVA: 0x4111aa8 VA: 0x7596729aa8
	public static Void ResetPerformanceMonitorByRackId(Int32 rackId) { }
	// RVA: 0x4111aac VA: 0x7596729aac
	public static Void SetAisacControl(Int32 rackId, String controlName, Single value) { }
	// RVA: 0x4111b58 VA: 0x7596729b58
	public static Void SetAisacControl(Int32 rackId, Int32 controlId, Single value) { }
	// RVA: 0x4111bf0 VA: 0x7596729bf0
	public static Void SetDefaultConfig(ref Config config) { }
	// RVA: 0x4111c70 VA: 0x7596729c70
	public override Void Dispose() { }
	// RVA: 0x4111d94 VA: 0x7596729d94
	public static Void GetNumRenderedSamples(Int32 rackId, out Int64 numSamples, out Int32 samplingRate) { }
	// RVA: 0x4111e3c VA: 0x7596729e3c
	public static Int32 GetAmbisonicRackId() { }
	// RVA: 0x4111ea8 VA: 0x7596729ea8
	public static Int32 GetChannelBasedAudioRackId() { }
	// RVA: 0x4111f14 VA: 0x7596729f14
	public static Int32 GetObjectBasedAudioRackId() { }
	// RVA: 0x4111f80 VA: 0x7596729f80
	public static Int32 GetPassThroughRackId() { }
	// RVA: 0x4111fec VA: 0x7596729fec
	public Int32 get_rackId() { }
	// RVA: 0x4111ff4 VA: 0x7596729ff4
	public static Config get_defaultConfig() { }
	// RVA: 0x4112064 VA: 0x759672a064
	protected override Void Finalize() { }
	// RVA: 0x4111178 VA: 0x7596729178
	private static extern Int32 criAtomExAsrRack_Create(in Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x411135c VA: 0x759672935c
	private static extern Int32 CRIWARE598E742F(in Config config, in PlatformConfig platformConfig) { }
	// RVA: 0x4111d18 VA: 0x7596729d18
	private static extern Void criAtomExAsrRack_Destroy(Int32 rackId) { }
	// RVA: 0x4111518 VA: 0x7596729518
	private static extern Void criAtomExAsrRack_AttachDspBusSetting(Int32 rackId, String setting, IntPtr work, Int32 workSize) { }
	// RVA: 0x41115d0 VA: 0x75967295d0
	private static extern Void criAtomExAsrRack_DetachDspBusSetting(Int32 rackId) { }
	// RVA: 0x411179c VA: 0x759672979c
	private static extern IntPtr criAtomExAsrRack_GetAppliedDspBusSnapshotName(Int32 rackId) { }
	// RVA: 0x4111654 VA: 0x7596729654
	private static extern Void criAtomExAsrRack_ApplyDspBusSnapshot(Int32 rackId, String snapshotName, Int32 timeMs) { }
	// RVA: 0x4111bf4 VA: 0x7596729bf4
	private static extern Void CRIWAREBFFFF28B(ref Config config) { }
	// RVA: 0x4111964 VA: 0x7596729964
	private static extern Void criAtomExAsrRack_GetPerformanceInfo(Int32 rackId, out PerformanceInfo perfInfo) { }
	// RVA: 0x4111a2c VA: 0x7596729a2c
	private static extern Void criAtomExAsrRack_ResetPerformanceMonitor(Int32 rackId) { }
	// RVA: 0x4111b5c VA: 0x7596729b5c
	private static extern Void criAtomExAsrRack_SetAisacControlById(Int32 rackId, UInt16 controlId, Single value) { }
	// RVA: 0x4111ab0 VA: 0x7596729ab0
	private static extern Void criAtomExAsrRack_SetAisacControlByName(Int32 rackId, String controlName, Single value) { }
	// RVA: 0x4111da8 VA: 0x7596729da8
	private static extern Void criAtomExAsrRack_GetNumRenderedSamples(Int32 rack_id, ref Int64 num_samples, ref Int32 sampling_rate) { }
	// RVA: 0x4111e40 VA: 0x7596729e40
	private static extern Int32 criAtomExAsrRack_GetAmbisonicRackId() { }
	// RVA: 0x4111eac VA: 0x7596729eac
	private static extern Int32 criAtomExAsrRack_GetChannelBasedAudioRackId() { }
	// RVA: 0x4111f18 VA: 0x7596729f18
	private static extern Int32 criAtomExAsrRack_GetObjectBasedAudioRackId() { }
	// RVA: 0x4111f84 VA: 0x7596729f84
	private static extern Int32 criAtomExAsrRack_GetPassThroughRackId() { }
}
```