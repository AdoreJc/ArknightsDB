# CriAtomExRawPcmVoicePool

**Namespace:** `CriWare`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExRawPcmVoicePool : CriAtomExVoicePool
{


	// RVA: 0x413ac24 VA: 0x7596752c24
	public Void .ctor(Int32 numVoices, Int32 maxChannels, Int32 maxSamplingRate, RawPcmFormat format, UInt32 identifier) { }
	// RVA: 0x413ad7c VA: 0x7596752d7c
	private static extern IntPtr criAtomExVoicePool_AllocateRawPcmVoicePool(ref RawPcmVoicePoolConfig config, IntPtr work, Int32 work_size) { }
}
```