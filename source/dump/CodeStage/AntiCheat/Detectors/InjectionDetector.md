# InjectionDetector

**Namespace:** `CodeStage.AntiCheat.Detectors`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : CodeStage.AntiCheat.Detectors
public class InjectionDetector : ActDetectorBase
{
	internal const String ComponentName; // 0x0
	internal const String FinalLogPrefix; // 0x0

	public static InjectionDetector Instance { get; }

	// RVA: 0x66b1834 VA: 0x7598cc9834
	public static InjectionDetector get_Instance() { }
	// RVA: 0x66b18a4 VA: 0x7598cc98a4
	public static Void StartDetection() { }
	// RVA: 0x66b190c VA: 0x7598cc990c
	public static Void StartDetection(Action`1 callback) { }
	// RVA: 0x66b1974 VA: 0x7598cc9974
	public static Void StopDetection() { }
	// RVA: 0x66b19dc VA: 0x7598cc99dc
	public static Void Dispose() { }
	// RVA: 0x66b1a44 VA: 0x7598cc9a44
	protected override Void StartDetectionAutomatically() { }
	// RVA: 0x66b1aac VA: 0x7598cc9aac
	public Void .ctor() { }
}
```