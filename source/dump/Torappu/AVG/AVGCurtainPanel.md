# AVGCurtainPanel

**Namespace:** `Torappu.AVG`


## Fields

- `Single _defaultFadetime`


## Methods

- `Void _ResetCurtains()`

- `Void _HideAllCurtains(Single)`

- `Void _RecycleCurtains()`

- `Boolean _ExecuteCurtain(Command)`

- `Vector2 _GenSizeDeltaWithMultiplior(Vector2, Int32, Single)`

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCurtainPanel : ExecutorComponent, IFadeTimeRatio
{
	private Single _defaultFadetime; // 0x4c
	private AVGCurtain[] _curtainWidgets; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0__ResetCurtains; // 0x10
	private static DelegateBridge __Hotfix0__HideAllCurtains; // 0x18
	private static DelegateBridge __Hotfix0__RecycleCurtains; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteCurtain; // 0x28
	private static DelegateBridge __Hotfix0__GenSizeDeltaWithMultiplior; // 0x30
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x38
	private static DelegateBridge __Hotfix0_OnFinish; // 0x40
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0x48
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3e6e3f0 VA: 0x75964863f0
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e6e52c VA: 0x759648652c
	public override Void OnReset() { }
	// RVA: 0x3e6e5a0 VA: 0x75964865a0
	private Void _ResetCurtains() { }
	// RVA: 0x3e6e67c VA: 0x759648667c
	private Void _HideAllCurtains(Single fadetime) { }
	// RVA: 0x3e6e7b8 VA: 0x75964867b8
	private Void _RecycleCurtains() { }
	// RVA: 0x3e6e894 VA: 0x7596486894
	private Boolean _ExecuteCurtain(Command command) { }
	// RVA: 0x3e6efa4 VA: 0x7596486fa4
	private Vector2 _GenSizeDeltaWithMultiplior(Vector2 originSize, Int32 idx, Single multiplier) { }
	// RVA: 0x3e6f074 VA: 0x7596487074
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e6f0d8 VA: 0x75964870d8
	protected override Void OnFinish() { }
	// RVA: 0x3e6eefc VA: 0x7596486efc
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e6f14c VA: 0x759648714c
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e6f1f0 VA: 0x75964871f0
	public Void .ctor() { }
	// RVA: 0x3e6f26c VA: 0x759648726c
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e6f274 VA: 0x7596487274
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```