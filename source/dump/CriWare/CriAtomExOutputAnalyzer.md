# CriAtomExOutputAnalyzer

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`

- `CriAtomExPlayer player`

- `String busName`

- `Int32 numBands`

- `Int32 numCapturedPcmSamples`

- `PcmCaptureCallback userPcmCaptureCallback`


## Properties

- `IntPtr nativeHandle`


## Methods

- `IntPtr get_nativeHandle()`

- `Void Dispose(Boolean)`

- `Boolean AttachExPlayer(CriAtomExPlayer)`

- `Void DetachExPlayer()`

- `Boolean AttachDspBus(String)`

- `Void DetachDspBus()`

- `Single GetRms(Int32)`

- `Void GetSpectrumLevels(ref)`

- `Void GetPcmData(ref, Int32)`

- `Void SetPcmCaptureCallback(PcmCaptureCallback)`

- `Void ExecutePcmCaptureCallback()`

- `Void ExecutePcmCaptureCallback(PcmCaptureCallback)`

- `Void InitializeWithConfig(Config)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExOutputAnalyzer : CriDisposable
{
	public const Int32 MaximumSpectrumBands; // 0x0
	protected IntPtr handle; // 0x20
	protected CriAtomExPlayer player; // 0x28
	protected String busName; // 0x30
	protected Int32 numBands; // 0x38
	protected Int32 numCapturedPcmSamples; // 0x3c
	protected PcmCaptureCallback userPcmCaptureCallback; // 0x40
	protected Single[] dataL; // 0x48
	protected Single[] dataR; // 0x50
	protected const Int32 pcmCapturerNumMaxData; // 0x0
	protected static IntPtr InternalCallbackFunctionPointer; // 0x0
	protected static InternalPcmCaptureCallback DelegateObject; // 0x8
	protected static Single[] DataL; // 0x10
	protected static Single[] DataR; // 0x18
	protected static PcmCaptureCallback UserPcmCaptureCallback; // 0x20

	public IntPtr nativeHandle { get; }

	// RVA: 0x412de00 VA: 0x7596745e00
	public IntPtr get_nativeHandle() { }
	// RVA: 0x412de08 VA: 0x7596745e08
	public Void .ctor(Config config) { }
	// RVA: 0x412e2ac VA: 0x75967462ac
	public override Void Dispose() { }
	// RVA: 0x412e2b4 VA: 0x75967462b4
	protected Void Dispose(Boolean disposing) { }
	// RVA: 0x412e774 VA: 0x7596746774
	public Boolean AttachExPlayer(CriAtomExPlayer player) { }
	// RVA: 0x412e574 VA: 0x7596746574
	public Void DetachExPlayer() { }
	// RVA: 0x412e9ac VA: 0x75967469ac
	public Boolean AttachDspBus(String busName) { }
	// RVA: 0x412e640 VA: 0x7596746640
	public Void DetachDspBus() { }
	// RVA: 0x412eba0 VA: 0x7596746ba0
	public Single GetRms(Int32 channel) { }
	// RVA: 0x412ed58 VA: 0x7596746d58
	public Void GetSpectrumLevels(ref Single[] levels) { }
	// RVA: 0x412ef18 VA: 0x7596746f18
	public Void GetPcmData(ref Single[] data, Int32 ch) { }
	// RVA: 0x412f0fc VA: 0x75967470fc
	public Void SetPcmCaptureCallback(PcmCaptureCallback callback) { }
	// RVA: 0x412f104 VA: 0x7596747104
	public Void ExecutePcmCaptureCallback() { }
	// RVA: 0x412f458 VA: 0x7596747458
	public Void ExecutePcmCaptureCallback(PcmCaptureCallback callback) { }
	// RVA: 0x412f474 VA: 0x7596747474
	protected Void .ctor() { }
	// RVA: 0x412f51c VA: 0x759674751c
	protected override Void Finalize() { }
	// RVA: 0x412def4 VA: 0x7596745ef4
	protected Void InitializeWithConfig(Config config) { }
	// RVA: 0x412dc74 VA: 0x7596745c74
	private static Void Callback(IntPtr ptrL, IntPtr ptrR, Int32 numChannels, Int32 numData) { }
	// RVA: 0x412f5b4 VA: 0x75967475b4
	protected static extern IntPtr criAtomExOutputAnalyzer_Create(in Config config) { }
	// RVA: 0x412e6f8 VA: 0x75967466f8
	protected static extern Void criAtomExOutputAnalyzer_Destroy(IntPtr analyzer) { }
	// RVA: 0x412e8a4 VA: 0x75967468a4
	protected static extern Void criAtomExOutputAnalyzer_AttachExPlayer(IntPtr analyzer, IntPtr player) { }
	// RVA: 0x412e928 VA: 0x7596746928
	protected static extern Void criAtomExOutputAnalyzer_DetachExPlayer(IntPtr analyzer, IntPtr player) { }
	// RVA: 0x412ea70 VA: 0x7596746a70
	protected static extern Void criAtomExOutputAnalyzer_AttachDspBusByName(IntPtr analyzer, String busName) { }
	// RVA: 0x412eb08 VA: 0x7596746b08
	protected static extern Void criAtomExOutputAnalyzer_DetachDspBusByName(IntPtr analyzer, String busName) { }
	// RVA: 0x412ecd4 VA: 0x7596746cd4
	protected static extern Single criAtomExOutputAnalyzer_GetRms(IntPtr analyzer, Int32 channel) { }
	// RVA: 0x412ee9c VA: 0x7596746e9c
	protected static extern IntPtr criAtomExOutputAnalyzer_GetSpectrumLevels(IntPtr analyzer) { }
	// RVA: 0x412f078 VA: 0x7596747078
	protected static extern IntPtr criAtomExOutputAnalyzer_GetPcmData(IntPtr analyzer, Int32 ch) { }
	// RVA: 0x412f3d4 VA: 0x75967473d4
	protected static extern Void criAtomExOutputAnalyzer_ExecuteQueuedPcmCapturerCallbacks(IntPtr analyzer, IntPtr callback) { }
	// RVA: 0x412f658 VA: 0x7596747658
	private static Void .cctor() { }
}
```