# CriAtomExAsr

**Namespace:** `CriWare`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExAsr
{


	// RVA: 0x410df0c VA: 0x7596725f0c
	public static Void AttachBusAnalyzer(String busName, Int32 interval, Int32 peakHoldTime) { }
	// RVA: 0x410df80 VA: 0x7596725f80
	public static Void AttachBusAnalyzer(Int32 interval, Int32 peakHoldTime) { }
	// RVA: 0x410df24 VA: 0x7596725f24
	public static Void DetachBusAnalyzer(String busName) { }
	// RVA: 0x410dfb4 VA: 0x7596725fb4
	public static Void DetachBusAnalyzer() { }
	// RVA: 0x410e008 VA: 0x7596726008
	public static Void GetBusAnalyzerInfo(String busName, out BusAnalyzerInfo info) { }
	// RVA: 0x410e238 VA: 0x7596726238
	public static Void GetBusAnalyzerInfo(Int32 busId, out BusAnalyzerInfo info) { }
	// RVA: 0x411f97c VA: 0x759673797c
	public static Void SetBusVolume(String busName, Single volume) { }
	// RVA: 0x411fa1c VA: 0x7596737a1c
	public static Void SetBusVolume(Int32 busId, Single volume) { }
	// RVA: 0x411faac VA: 0x7596737aac
	public static Void SetBusSendLevel(String busName, String sendTo, Single level) { }
	// RVA: 0x411fb6c VA: 0x7596737b6c
	public static Void SetBusSendLevel(Int32 busId, Int32 sendTo, Single level) { }
	// RVA: 0x411fc04 VA: 0x7596737c04
	public static Void SetBusMatrix(String busName, Int32 inputChannels, Int32 outputChannels, Single[] matrix) { }
	// RVA: 0x411fcbc VA: 0x7596737cbc
	public static Void SetBusMatrix(Int32 busId, Int32 inputChannels, Int32 outputChannels, Single[] matrix) { }
	// RVA: 0x411fd64 VA: 0x7596737d64
	public static Void SetEffectBypass(String busName, String effectName, Boolean bypass) { }
	// RVA: 0x411fe28 VA: 0x7596737e28
	public static Void SetEffectParameter(String busName, String effectName, UInt32 parameterIndex, Single parameterValue) { }
	// RVA: 0x411ffc8 VA: 0x7596737fc8
	public static Single GetEffectParameter(String busName, String effectName, UInt32 parameterIndex) { }
	// RVA: 0x4113c90 VA: 0x759672bc90
	public static Boolean RegisterEffectInterface(IntPtr afx_interface) { }
	// RVA: 0x412011c VA: 0x759673811c
	public static Void UnregisterEffectInterface(IntPtr afx_interface) { }
	// RVA: 0x412019c VA: 0x759673819c
	public static Void GetBusVolume(String busName, out Single volume) { }
	// RVA: 0x4120234 VA: 0x7596738234
	public static Void EnableBinauralizer(Boolean enabled) { }
	// RVA: 0x41202b8 VA: 0x75967382b8
	public static Boolean IsEnabledBinauralizer() { }
	// RVA: 0x412032c VA: 0x759673832c
	public static Int32 GetPcmOutput(Int32 outputChannels, Int32 outputSamples, Single[][] buffer) { }
	// RVA: 0x4120334 VA: 0x7596738334
	public static Int32 GetNumBufferedPcmOutputSamples() { }
	// RVA: 0x4113234 VA: 0x759672b234
	public static Void SetPcmBufferSize(Int32 numSamples) { }
	// RVA: 0x412033c VA: 0x759673833c
	public static Void PauseOutputVoice(Boolean sw) { }
	// RVA: 0x411f3ec VA: 0x75967373ec
	private static extern Void criAtomExAsr_AttachBusAnalyzerByName(String busName, ref BusAnalyzerConfig config) { }
	// RVA: 0x411f480 VA: 0x7596737480
	private static extern Void criAtomExAsr_AttachBusAnalyzer(Int32 busNo, ref BusAnalyzerConfig config) { }
	// RVA: 0x411f504 VA: 0x7596737504
	private static extern Void criAtomExAsr_DetachBusAnalyzerByName(String busName) { }
	// RVA: 0x411f590 VA: 0x7596737590
	private static extern Void criAtomExAsr_DetachBusAnalyzer(Int32 busNo) { }
	// RVA: 0x411f60c VA: 0x759673760c
	private static extern Void criAtomExAsr_GetBusAnalyzerInfoByName(String busName, IntPtr info) { }
	// RVA: 0x411f8f8 VA: 0x75967378f8
	private static extern Void criAtomExAsr_GetBusAnalyzerInfo(Int32 busNo, IntPtr info) { }
	// RVA: 0x411f980 VA: 0x7596737980
	private static extern Void criAtomExAsr_SetBusVolumeByName(String busName, Single volume) { }
	// RVA: 0x411fa20 VA: 0x7596737a20
	private static extern Void criAtomExAsr_SetBusVolume(Int32 busNo, Single volume) { }
	// RVA: 0x411fab0 VA: 0x7596737ab0
	private static extern Void criAtomExAsr_SetBusSendLevelByName(String busName, String sendtoName, Single level) { }
	// RVA: 0x411fb70 VA: 0x7596737b70
	private static extern Void criAtomExAsr_SetBusSendLevel(Int32 busNo, Int32 sendtoNo, Single level) { }
	// RVA: 0x411fc08 VA: 0x7596737c08
	private static extern Void criAtomExAsr_SetBusMatrixByName(String busName, Int32 inputChannels, Int32 outputChannels, Single[] matrix) { }
	// RVA: 0x411fcc0 VA: 0x7596737cc0
	private static extern Void criAtomExAsr_SetBusMatrix(Int32 busNo, Int32 inputChannels, Int32 outputChannels, Single[] matrix) { }
	// RVA: 0x411fd6c VA: 0x7596737d6c
	private static extern Void criAtomExAsr_SetEffectBypass(String busName, String effectName, Boolean bypass) { }
	// RVA: 0x411ff1c VA: 0x7596737f1c
	private static extern Void criAtomExAsr_UpdateEffectParameters(String busName, String effectName) { }
	// RVA: 0x411fe50 VA: 0x7596737e50
	private static extern Void criAtomExAsr_SetEffectParameter(String busName, String effectName, UInt32 parameterIndex, Single parameterValue) { }
	// RVA: 0x411ffcc VA: 0x7596737fcc
	private static extern Single criAtomExAsr_GetEffectParameter(String busName, String effectName, UInt32 parameterIndex) { }
	// RVA: 0x4120098 VA: 0x7596738098
	private static extern Boolean criAtomExAsr_RegisterEffectInterface(IntPtr afx_interface) { }
	// RVA: 0x4120120 VA: 0x7596738120
	private static extern Void criAtomExAsr_UnregisterEffectInterface(IntPtr afx_interface) { }
	// RVA: 0x412023c VA: 0x759673823c
	private static extern Void criAtomExAsr_EnableBinauralizer(Boolean enabled) { }
	// RVA: 0x41202bc VA: 0x75967382bc
	private static extern Boolean criAtomExAsr_IsEnabledBinauralizer() { }
	// RVA: 0x4120344 VA: 0x7596738344
	private static extern Void criAtomExAsr_PauseOutputVoice(Boolean sw) { }
	// RVA: 0x41201a0 VA: 0x75967381a0
	private static extern Void criAtomExAsr_GetBusVolumeByName(String busName, out Single volume) { }
	// RVA: 0x41203c0 VA: 0x75967383c0
	public Void .ctor() { }
}
```