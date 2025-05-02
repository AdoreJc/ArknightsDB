# AudioEmitterLogInterface

**Namespace:** `Torappu.Battle.DevelopTools`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.DevelopTools
public class AudioEmitterLogInterface
{
	public const String HANDLER_CLS_NAME; // 0x0
	private static IHandler s_handler; // 0x0


	// RVA: 0x1d2c3ac VA: 0x75943443ac
	public static Void EmitLog(String module, String subSignal, String eventName, Vector3 worldPosition) { }
	// RVA: 0x1d2c4d4 VA: 0x75943444d4
	public static Void AddAudioLogDataAtLast(AudioChannel channel) { }
	// RVA: 0x1d2c5b4 VA: 0x75943445b4
	public static Boolean IsSystemEnabled() { }
	// RVA: 0x1d2c608 VA: 0x7594344608
	private static IHandler _GetHandler() { }
	// RVA: 0x1d2c650 VA: 0x7594344650
	public Void .ctor() { }
}
```