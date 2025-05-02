# BuffProgressFloatSource

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `String _maxKey`

- `String _progressKey`

- `Single _defaultVal`

- `Single _finishedVal`

- `AnimationCurve _curve`

- `Boolean m_isFinished`


## Methods

- `FP GetBlackboardProgress(Buff, String, String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Single <>xLuaBaseProxy_GetValueOnPlay()`

- `Single <>xLuaBaseProxy_GetValue()`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Void <>xLuaBaseProxy_OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class BuffProgressFloatSource : AnimatorFloatSource
{
	private String _buffKey; // 0x20
	private String _maxKey; // 0x28
	private String _progressKey; // 0x30
	private Single _defaultVal; // 0x38
	private Single _finishedVal; // 0x3c
	private AnimationCurve _curve; // 0x40
	private Boolean m_isFinished; // 0x48
	private ObjectPtr`1 m_buff; // 0x50
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GetValueOnPlay; // 0x8
	private static DelegateBridge __Hotfix0_GetValue; // 0x10
	private static DelegateBridge __Hotfix0_GetBlackboardProgress; // 0x18
	private static DelegateBridge __Hotfix0_OnFinish; // 0x20
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1ff6734 VA: 0x759460e734
	public override Void OnPlay() { }
	// RVA: 0x1ff67a4 VA: 0x759460e7a4
	public override Single GetValueOnPlay() { }
	// RVA: 0x1ff680c VA: 0x759460e80c
	public override Single GetValue() { }
	// RVA: 0x1ff6a34 VA: 0x759460ea34
	public FP GetBlackboardProgress(Buff buff, String key, String maxKey) { }
	// RVA: 0x1ff6c90 VA: 0x759460ec90
	public override Void OnFinish() { }
	// RVA: 0x1ff6d04 VA: 0x759460ed04
	public override Void OnRecycle() { }
	// RVA: 0x1ff6da0 VA: 0x759460eda0
	public Void .ctor() { }
	// RVA: 0x1ff6e0c VA: 0x759460ee0c
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff6e10 VA: 0x759460ee10
	private Single <>xLuaBaseProxy_GetValueOnPlay() { }
	// RVA: 0x1ff6e14 VA: 0x759460ee14
	private Single <>xLuaBaseProxy_GetValue() { }
	// RVA: 0x1ff6e18 VA: 0x759460ee18
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x1ff6e1c VA: 0x759460ee1c
	private Void <>xLuaBaseProxy_OnRecycle() { }
}
```