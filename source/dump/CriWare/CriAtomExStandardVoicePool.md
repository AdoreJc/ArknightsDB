# CriAtomExStandardVoicePool

**Namespace:** `CriWare`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExStandardVoicePool : CriAtomExVoicePool
{


	// RVA: 0x413a314 VA: 0x7596752314
	public static Void SetDefaultConfigForStandardVoicePool(ref Config config) { }
	// RVA: 0x413a424 VA: 0x7596752424
	public Void .ctor(Config config) { }
	// RVA: 0x413a604 VA: 0x7596752604
	public Void .ctor(Int32 numVoices, Int32 maxChannels, Int32 maxSamplingRate, Boolean streamingFlag, UInt32 identifier) { }
	// RVA: 0x413a4e0 VA: 0x75967524e0
	private static extern IntPtr criAtomExVoicePool_AllocateStandardVoicePool(ref Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x413a318 VA: 0x7596752318
	private static extern Void CRIWAREEBBAD341(ref Config config) { }
}
```