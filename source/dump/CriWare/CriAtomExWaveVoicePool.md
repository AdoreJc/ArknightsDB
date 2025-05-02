# CriAtomExWaveVoicePool

**Namespace:** `CriWare`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExWaveVoicePool : CriAtomExVoicePool
{


	// RVA: 0x413a798 VA: 0x7596752798
	public static Void SetDefaultConfigForWaveVoicePool(ref Config config) { }
	// RVA: 0x413a8a8 VA: 0x75967528a8
	public Void .ctor(Config config) { }
	// RVA: 0x413aa88 VA: 0x7596752a88
	public Void .ctor(Int32 numVoices, Int32 maxChannels, Int32 maxSamplingRate, Boolean streamingFlag, UInt32 identifier) { }
	// RVA: 0x413a964 VA: 0x7596752964
	private static extern IntPtr criAtomExVoicePool_AllocateWaveVoicePool(ref Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x413a79c VA: 0x759675279c
	private static extern Void CRIWARE7D9C1C2B(ref Config config) { }
}
```