# GradingPPSettings

**Namespace:** ` `


## Dump
```C#
// Dll : Unity.Postprocessing.Runtime.dll
// Namespace : 
public class GradingPPSettings
{
	public static Boolean s_colorGrading; // 0x0
	public static Boolean s_bloom; // 0x1
	public static Boolean s_vignette; // 0x2
	public static Boolean s_antialiasing; // 0x3
	public static GradingLevel s_gradingLevel; // 0x4

	public static Boolean PostProcessEnabled { get; }

	// RVA: 0x67f13b4 VA: 0x7598e093b4
	public static Boolean get_PostProcessEnabled() { }
	// RVA: 0x67f1470 VA: 0x7598e09470
	public static Vector4 GetMobileBlurParam(Boolean forceLow) { }
	// RVA: 0x67f149c VA: 0x7598e0949c
	public Void .ctor() { }
	// RVA: 0x67f14a4 VA: 0x7598e094a4
	private static Void .cctor() { }
}
```