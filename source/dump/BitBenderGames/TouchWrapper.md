# TouchWrapper

**Namespace:** `BitBenderGames`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class TouchWrapper
{

	public static Int32 TouchCount { get; }
	public static WrappedTouch Touch0 { get; }
	public static Boolean IsFingerDown { get; }
	public static List`1 Touches { get; }
	public static Vector2 AverageTouchPos { get; }

	// RVA: 0x2c23580 VA: 0x759523b580
	public static Int32 get_TouchCount() { }
	// RVA: 0x2c23e4c VA: 0x759523be4c
	public static WrappedTouch get_Touch0() { }
	// RVA: 0x2c2ca98 VA: 0x7595244a98
	public static Boolean get_IsFingerDown() { }
	// RVA: 0x2c2db5c VA: 0x7595245b5c
	public static List`1 get_Touches() { }
	// RVA: 0x2c2dd2c VA: 0x7595245d2c
	private static List`1 GetTouchesFromInputTouches() { }
	// RVA: 0x2c2db14 VA: 0x7595245b14
	public static Vector2 get_AverageTouchPos() { }
	// RVA: 0x2c2de7c VA: 0x7595245e7c
	private static Vector2 GetAverageTouchPosFromInputTouches() { }
	// RVA: 0x2c2df98 VA: 0x7595245f98
	public Void .ctor() { }
}
```