# CriAtomExAuxIn

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`

- `CriAudioReadStream inputReadStream`


## Methods

- `Void Start()`

- `Void Stop()`

- `Void SetFormat(Int32, Int32)`

- `Void GetFormat(out, out)`

- `Void SetVolume(Single)`

- `Void SetFrequencyRatio(Single)`

- `Void SetBusSendLevel(String, Single)`

- `Void SetInputReadStream(CriAudioReadStream)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExAuxIn : CriDisposable
{
	private const String errorInvalidHandle; // 0x0
	private IntPtr handle; // 0x20
	private CriAudioReadStream inputReadStream; // 0x28


	// RVA: 0x412b374 VA: 0x7596743374
	public Void .ctor(Nullable`1 config) { }
	// RVA: 0x412b530 VA: 0x7596743530
	protected override Void Finalize() { }
	// RVA: 0x412b5cc VA: 0x75967435cc
	public override Void Dispose() { }
	// RVA: 0x412b718 VA: 0x7596743718
	public Void Start() { }
	// RVA: 0x412b79c VA: 0x759674379c
	public Void Stop() { }
	// RVA: 0x412b884 VA: 0x7596743884
	public Void SetFormat(Int32 numChannels, Int32 samplingRate) { }
	// RVA: 0x412b920 VA: 0x7596743920
	public Void GetFormat(out Int32 numChannels, out Int32 samplingRate) { }
	// RVA: 0x412b9bc VA: 0x75967439bc
	public Void SetVolume(Single volume) { }
	// RVA: 0x412ba50 VA: 0x7596743a50
	public Void SetFrequencyRatio(Single frequencyRatio) { }
	// RVA: 0x412bae4 VA: 0x7596743ae4
	public Void SetBusSendLevel(String busName, Single level) { }
	// RVA: 0x412bb94 VA: 0x7596743b94
	public Void SetInputReadStream(CriAudioReadStream stream) { }
	// RVA: 0x412b49c VA: 0x759674349c
	private static extern IntPtr criAtomAuxIn_Create(in Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x412b69c VA: 0x759674369c
	private static extern Void criAtomAuxIn_Destroy(IntPtr aux_in) { }
	// RVA: 0x412b720 VA: 0x7596743720
	private static extern Void criAtomAuxIn_Start(IntPtr aux_in) { }
	// RVA: 0x412b808 VA: 0x7596743808
	private static extern Void criAtomAuxIn_Stop(IntPtr aux_in) { }
	// RVA: 0x412b9c4 VA: 0x75967439c4
	private static extern Void criAtomAuxIn_SetVolume(IntPtr aux_in, Single volume) { }
	// RVA: 0x412ba58 VA: 0x7596743a58
	private static extern Void criAtomAuxIn_SetFrequencyRatio(IntPtr aux_in, Single ratio) { }
	// RVA: 0x412baec VA: 0x7596743aec
	private static extern Void criAtomAuxIn_SetBusSendLevelByName(IntPtr aux_in, String bus_name, Single level) { }
	// RVA: 0x412b88c VA: 0x759674388c
	private static extern Void criAtomAuxIn_SetFormat(IntPtr aux_in, Int32 num_channels, Int32 sampling_rate) { }
	// RVA: 0x412b928 VA: 0x7596743928
	private static extern Void criAtomAuxIn_GetFormat(IntPtr aux_in, out Int32 num_channels, out Int32 sampling_rate) { }
	// RVA: 0x412bbc8 VA: 0x7596743bc8
	private static extern Void criAtomAuxIn_SetInputReadStream(IntPtr aux_in, IntPtr stream_cbfunc, IntPtr stream_ptr) { }
}
```