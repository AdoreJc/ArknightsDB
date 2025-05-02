# CriAtomExMic

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`

- `CriAudioWriteStream outputWriteStream`


## Methods

- `Void Dispose(Boolean)`

- `Void Start()`

- `Void Stop()`

- `Int32 GetNumChannels()`

- `Int32 GetSamplingRate()`

- `UInt32 GetNumBufferedSamples()`

- `UInt32 GetNumBufferredSamples()`

- `Boolean IsAvailable()`

- `UInt32 ReadData(Single[])`

- `UInt32 ReadData(Single[], UInt32)`

- `UInt32 ReadData(Single[], Single[])`

- `UInt32 ReadData(Single[], Single[], UInt32)`

- `UInt32 ReadData(Single[][])`

- `UInt32 ReadData(Single[][], UInt32)`

- `Void SetOutputWriteStream(CriAudioWriteStream)`

- `CriAudioReadStream GetOutputReadStream()`

- `Effect AttachEffect(IntPtr, Single[])`

- `Void DetachEffect(Effect)`

- `Void SetEffectParameter(Effect, Int32, Single)`

- `Single GetEffectParameter(Effect, Int32)`

- `Void SetEffectBypass(Effect, Boolean)`

- `Void UpdateEffectParameters(Effect)`

- `UInt32 InternalReadDataFromBufferPointers(UInt32)`

- `Void InternalClearBuffers()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExMic : CriDisposable
{
	private const String errorInvalidHandle; // 0x0
	private const String errorInvalidBufferLength; // 0x0
	private const String errorInvalidNumBuffers; // 0x0
	private const String errorAlreadyInitialized; // 0x0
	private const String errorNotInitialized; // 0x0
	private static Boolean <isInitialized>k__BackingField; // 0x0
	private IntPtr handle; // 0x20
	private IntPtr[] bufferPointers; // 0x28
	private GCHandle[] gcHandles; // 0x30
	private CriAudioWriteStream outputWriteStream; // 0x38
	private static Int32 _initializationCount; // 0x4

	public static Boolean isInitialized { get; set; }

	// RVA: 0x412bc5c VA: 0x7596743c5c
	public static Boolean get_isInitialized() { }
	// RVA: 0x412bca4 VA: 0x7596743ca4
	private static Void set_isInitialized(Boolean value) { }
	// RVA: 0x412bcf0 VA: 0x7596743cf0
	public static Void InitializeModule() { }
	// RVA: 0x412be58 VA: 0x7596743e58
	public static Void FinalizeModule() { }
	// RVA: 0x412bff4 VA: 0x7596743ff4
	public static Void SetupOutputCategoryForMic_IOS(Boolean enable) { }
	// RVA: 0x412bff8 VA: 0x7596743ff8
	public static DeviceInfo[] GetDevices() { }
	// RVA: 0x412c290 VA: 0x7596744290
	public static Int32 GetNumDevices() { }
	// RVA: 0x412c294 VA: 0x7596744294
	public static Nullable`1 GetDefaultDevice() { }
	// RVA: 0x412c498 VA: 0x7596744498
	public static Boolean IsFormatSupported(Config config) { }
	// RVA: 0x412c538 VA: 0x7596744538
	public static CriAtomExMic Create(Nullable`1 config) { }
	// RVA: 0x412c7c8 VA: 0x75967447c8
	private Void .ctor(IntPtr handle) { }
	// RVA: 0x412c8e4 VA: 0x75967448e4
	protected override Void Finalize() { }
	// RVA: 0x412c980 VA: 0x7596744980
	public override Void Dispose() { }
	// RVA: 0x412c9e4 VA: 0x75967449e4
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x412cb04 VA: 0x7596744b04
	public Void Start() { }
	// RVA: 0x412cb88 VA: 0x7596744b88
	public Void Stop() { }
	// RVA: 0x412c8dc VA: 0x75967448dc
	public Int32 GetNumChannels() { }
	// RVA: 0x412cc88 VA: 0x7596744c88
	public Int32 GetSamplingRate() { }
	// RVA: 0x412cd0c VA: 0x7596744d0c
	public UInt32 GetNumBufferedSamples() { }
	// RVA: 0x412cd90 VA: 0x7596744d90
	public UInt32 GetNumBufferredSamples() { }
	// RVA: 0x412cd98 VA: 0x7596744d98
	public Boolean IsAvailable() { }
	// RVA: 0x412ce8c VA: 0x7596744e8c
	public UInt32 ReadData(Single[] bufferMono) { }
	// RVA: 0x412cea4 VA: 0x7596744ea4
	public UInt32 ReadData(Single[] bufferMono, UInt32 numToRead) { }
	// RVA: 0x412d02c VA: 0x759674502c
	public UInt32 ReadData(Single[] bufferL, Single[] bufferR) { }
	// RVA: 0x412d044 VA: 0x7596745044
	public UInt32 ReadData(Single[] bufferL, Single[] bufferR, UInt32 numToRead) { }
	// RVA: 0x412d1b8 VA: 0x75967451b8
	public UInt32 ReadData(Single[][] buffers) { }
	// RVA: 0x412d200 VA: 0x7596745200
	public UInt32 ReadData(Single[][] buffers, UInt32 numToRead) { }
	// RVA: 0x412d320 VA: 0x7596745320
	public Void SetOutputWriteStream(CriAudioWriteStream stream) { }
	// RVA: 0x412d428 VA: 0x7596745428
	public CriAudioReadStream GetOutputReadStream() { }
	// RVA: 0x412d508 VA: 0x7596745508
	public Effect AttachEffect(IntPtr afxInterface, Single[] configParameters) { }
	// RVA: 0x412d730 VA: 0x7596745730
	public Void DetachEffect(Effect effect) { }
	// RVA: 0x412d7d0 VA: 0x75967457d0
	public Void SetEffectParameter(Effect effect, Int32 parameterIndex, Single parameterValue) { }
	// RVA: 0x412d890 VA: 0x7596745890
	public Single GetEffectParameter(Effect effect, Int32 parameterIndex) { }
	// RVA: 0x412d940 VA: 0x7596745940
	public Void SetEffectBypass(Effect effect, Boolean bypass) { }
	// RVA: 0x412d9f4 VA: 0x75967459f4
	public Void UpdateEffectParameters(Effect effect) { }
	// RVA: 0x412cf34 VA: 0x7596744f34
	private UInt32 InternalReadDataFromBufferPointers(UInt32 numToRead) { }
	// RVA: 0x412cf48 VA: 0x7596744f48
	private Void InternalClearBuffers() { }
	// RVA: 0x412bdf4 VA: 0x7596743df4
	private static extern Void criAtomMicUnity_Initialize() { }
	// RVA: 0x412bf90 VA: 0x7596743f90
	private static extern Void criAtomMicUnity_Finalize() { }
	// RVA: 0x412c128 VA: 0x7596744128
	private static extern Int32 criAtomMic_GetNumDevices() { }
	// RVA: 0x412c190 VA: 0x7596744190
	private static extern Boolean criAtomMic_GetDevice(Int32 index, out DeviceInfo info) { }
	// RVA: 0x412c3a8 VA: 0x75967443a8
	private static extern Boolean criAtomMic_GetDefaultDevice(out DeviceInfo info) { }
	// RVA: 0x412c49c VA: 0x759674449c
	private static extern Boolean criAtomMic_IsFormatSupported(in Config config) { }
	// RVA: 0x412c71c VA: 0x759674471c
	private static extern IntPtr criAtomMic_Create(in Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x412ca88 VA: 0x7596744a88
	private static extern Void criAtomMic_Destroy(IntPtr mic) { }
	// RVA: 0x412cb0c VA: 0x7596744b0c
	private static extern Void criAtomMic_Start(IntPtr mic) { }
	// RVA: 0x412cb90 VA: 0x7596744b90
	private static extern Void criAtomMic_Stop(IntPtr mic) { }
	// RVA: 0x412cc0c VA: 0x7596744c0c
	private static extern Int32 criAtomMic_GetNumChannels(IntPtr mic) { }
	// RVA: 0x412cc90 VA: 0x7596744c90
	private static extern Int32 criAtomMic_GetSamplingRate(IntPtr mic) { }
	// RVA: 0x412cd14 VA: 0x7596744d14
	private static extern UInt32 criAtomMic_GetNumBufferedSamples(IntPtr mic) { }
	// RVA: 0x412ce08 VA: 0x7596744e08
	private static extern Boolean criAtomMic_IsAvailable(IntPtr mic) { }
	// RVA: 0x412da94 VA: 0x7596745a94
	private static extern UInt32 criAtomMic_ReadData(IntPtr mic, IntPtr[] data, UInt32 num_samples) { }
	// RVA: 0x412d394 VA: 0x7596745394
	private static extern Void criAtomMic_SetOutputWriteStream(IntPtr mic, IntPtr stream_cbfunc, IntPtr stream_ptr) { }
	// RVA: 0x412d4a0 VA: 0x75967454a0
	private static extern IntPtr criAtomMic_GetOutputReadStream() { }
	// RVA: 0x412db30 VA: 0x7596745b30
	private static extern Int32 criAtomMic_CalculateWorkSizeForEffect(IntPtr mic, IntPtr afx_interface, Single[] config_parameters, UInt32 num_config_parameters) { }
	// RVA: 0x412d5f0 VA: 0x75967455f0
	private static extern IntPtr criAtomMic_AttachEffect(IntPtr mic, IntPtr afx_interface, Single[] config_parameters, UInt32 num_config_parameters, IntPtr work, Int32 work_size) { }
	// RVA: 0x412d74c VA: 0x759674574c
	private static extern Void criAtomMic_DetachEffect(IntPtr mic, IntPtr effect) { }
	// RVA: 0x412d6ac VA: 0x75967456ac
	private static extern IntPtr criAtomMic_GetEffectInstance(IntPtr mic, IntPtr effect) { }
	// RVA: 0x412d960 VA: 0x7596745960
	private static extern Void criAtomMic_SetEffectBypass(IntPtr mic, IntPtr effect, Boolean bypass) { }
	// RVA: 0x412d7ec VA: 0x75967457ec
	private static extern Void criAtomMic_SetEffectParameter(IntPtr mic, IntPtr effect, UInt32 parameter_index, Single parameter_value) { }
	// RVA: 0x412d8ac VA: 0x75967458ac
	private static extern Single criAtomMic_GetEffectParameter(IntPtr mic, IntPtr effect, UInt32 parameter_index) { }
	// RVA: 0x412da10 VA: 0x7596745a10
	private static extern Void criAtomMic_UpdateEffectParameters(IntPtr mic, IntPtr effect) { }
}
```