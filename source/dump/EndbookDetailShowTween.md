# EndbookDetailShowTween

**Namespace:** ` `


## Fields

- `ArchiveEndbookDetailDataBinder m_closure`


## Methods

- `Void <>xLuaBaseProxy_BeforeShowEffect()`

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EndbookDetailShowTween : UISwitchTween
{
	private const Single ANIM_DURATION; // 0x0
	private ArchiveEndbookDetailDataBinder m_closure; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10
	private static DelegateBridge __Hotfix0_BeforeShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28


	// RVA: 0x304d0b4 VA: 0x75956650b4
	public Void .ctor(ArchiveEndbookDetailDataBinder closure) { }
	// RVA: 0x304d580 VA: 0x7595665580
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x304d688 VA: 0x7595665688
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x304d790 VA: 0x7595665790
	protected override Void BeforeShowEffect() { }
	// RVA: 0x304d834 VA: 0x7595665834
	protected override Void AfterHideEffect() { }
	// RVA: 0x304d8d8 VA: 0x75956658d8
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x304d9a4 VA: 0x75956659a4
	private Void <>xLuaBaseProxy_BeforeShowEffect() { }
	// RVA: 0x304d9ac VA: 0x75956659ac
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x304d9b4 VA: 0x75956659b4
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```