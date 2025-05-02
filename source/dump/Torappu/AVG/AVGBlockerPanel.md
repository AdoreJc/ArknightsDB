# AVGBlockerPanel

**Namespace:** `Torappu.AVG`


## Fields

- `Image _blocker`

- `Single _defaultFadetime`

- `Sprite _defaultBlocker`


## Methods

- `Boolean _ExecuteBlocker(Command)`

- `Tween _GenTweenerWithParam(Color, Single, Int32)`

- `Void _CleanMaterial()`

- `Void _SetMaterial(String)`

- `Void _ChangeBlockerImg(String, Int32)`

- `Void _ResetBlockerImg()`

- `Void _FinishCommand()`

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGBlockerPanel : ExecutorComponent, IFadeTimeRatio
{
	private const Int32 BLOCKER_STYLE_DEFAULT; // 0x0
	private const Int32 BLOCKER_STYLE_SLIDER; // 0x0
	private Image _blocker; // 0x50
	private Single _defaultFadetime; // 0x58
	private Sprite _defaultBlocker; // 0x60
	private const String STYLE_DEFAULT; // 0x0
	private const String STYLE_SLIDER; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0__ExecuteBlocker; // 0x10
	private static DelegateBridge __Hotfix0__GenTweenerWithParam; // 0x18
	private static DelegateBridge __Hotfix0__CleanMaterial; // 0x20
	private static DelegateBridge __Hotfix0__SetMaterial; // 0x28
	private static DelegateBridge __Hotfix0__ChangeBlockerImg; // 0x30
	private static DelegateBridge __Hotfix0__ConvertBlockerStyle; // 0x38
	private static DelegateBridge __Hotfix0__ResetBlockerImg; // 0x40
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x48
	private static DelegateBridge __Hotfix0_OnFinish; // 0x50
	private static DelegateBridge __Hotfix0__FinishCommand; // 0x58
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0x60
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x3e62098 VA: 0x759647a098
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e621d0 VA: 0x759647a1d0
	public override Void OnReset() { }
	// RVA: 0x3e6237c VA: 0x759647a37c
	private Boolean _ExecuteBlocker(Command command) { }
	// RVA: 0x3e62b7c VA: 0x759647ab7c
	private Tween _GenTweenerWithParam(Color targetColor, Single fadetime, Int32 blockerStyle) { }
	// RVA: 0x3e62d44 VA: 0x759647ad44
	private Void _CleanMaterial() { }
	// RVA: 0x3e62dc4 VA: 0x759647adc4
	private Void _SetMaterial(String resPath) { }
	// RVA: 0x3e62908 VA: 0x759647a908
	private Void _ChangeBlockerImg(String imgName, Int32 blockerStyle) { }
	// RVA: 0x3e6284c VA: 0x759647a84c
	private static Int32 _ConvertBlockerStyle(String style) { }
	// RVA: 0x3e62304 VA: 0x759647a304
	private Void _ResetBlockerImg() { }
	// RVA: 0x3e62f08 VA: 0x759647af08
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e62f6c VA: 0x759647af6c
	protected override Void OnFinish() { }
	// RVA: 0x3e62fd4 VA: 0x759647afd4
	private Void _FinishCommand() { }
	// RVA: 0x3e62ad4 VA: 0x759647aad4
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e630c4 VA: 0x759647b0c4
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e63168 VA: 0x759647b168
	public Void .ctor() { }
	// RVA: 0x3e631e0 VA: 0x759647b1e0
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e631e4 VA: 0x759647b1e4
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```