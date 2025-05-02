# BakeCache

**Namespace:** ` `


## Fields

- `TrailContext trailContext`


## Methods

- `Void ClearMemo(String)`

- `Void ClearAllMemo()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class BakeCache
{
	public const String KEY_UV_FRAME_OVERTIME; // 0x0
	public const String KEY_TRAIL_WIDTH; // 0x0
	public const String KEY_TRAIL_COLOR; // 0x0
	public const String KEY_COLOR_OVER_LIFETIME; // 0x0
	public const String KEY_COLOR_BY_SPEED; // 0x0
	public const String KEY_TRAIL_COLOR_LIFETIME; // 0x0
	public const String KEY_TRAIL_LIFETIME; // 0x0
	public const String KEY_START_TIME; // 0x0
	private Dictionary`2 m_curveMemo; // 0x10
	private Dictionary`2 m_gradientMemo; // 0x18
	public TrailContext trailContext; // 0x20


	// RVA: 0x67a2240 VA: 0x7598dba240
	public Void ClearMemo(String key) { }
	// RVA: 0x67a22b0 VA: 0x7598dba2b0
	public Void ClearAllMemo() { }
	// RVA: 0x VA: 0x0
	public static MinMaxCurve ReadCurveMemo(BakeCache nullableCache, String key, TContext context, Func`2 reader) { }
	// RVA: 0x VA: 0x0
	public static MinMaxGradient ReadGradientMemo(BakeCache nullableCache, String key, TContext context, Func`2 reader) { }
	// RVA: 0x VA: 0x0
	private static TData _ReadStructMemo(String key, TContext context, Func`2 reader, ref Dictionary`2 memo) { }
	// RVA: 0x67a232c VA: 0x7598dba32c
	public Void .ctor() { }
}
```