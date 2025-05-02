# MeldingProgressSwitchTween

**Namespace:** ` `


## Fields

- `Act24sideMeldingView m_closure`


## Properties

- `Boolean isTweening`


## Methods

- `Boolean get_isTweening()`

- `Void KillIfNecessary()`

- `Void ResetDirectly()`

- `Void TweenProgress()`

- `Void _ResetSlotSlider()`

- `Void _ResetSlotLightTweens()`

- `Boolean _NeedAdjustInputProgress(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MeldingProgressSwitchTween : IHotfixable
{
	private Act24sideMeldingView m_closure; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_isTweening; // 0x8
	private static DelegateBridge __Hotfix0_KillIfNecessary; // 0x10
	private static DelegateBridge __Hotfix0_ResetDirectly; // 0x18
	private static DelegateBridge __Hotfix0_TweenProgress; // 0x20
	private static DelegateBridge __Hotfix0__ResetSlotSlider; // 0x28
	private static DelegateBridge __Hotfix0__ResetSlotLightTweens; // 0x30
	private static DelegateBridge __Hotfix0__NeedAdjustInputProgress; // 0x38

	public Boolean isTweening { get; }

	// RVA: 0x32a8748 VA: 0x75958c0748
	public Void .ctor(Act24sideMeldingView itemView) { }
	// RVA: 0x32a9580 VA: 0x75958c1580
	public Boolean get_isTweening() { }
	// RVA: 0x32a841c VA: 0x75958c041c
	public Void KillIfNecessary() { }
	// RVA: 0x32a8884 VA: 0x75958c0884
	public Void ResetDirectly() { }
	// RVA: 0x32a8c18 VA: 0x75958c0c18
	public Void TweenProgress() { }
	// RVA: 0x32ab488 VA: 0x75958c3488
	private Void _ResetSlotSlider() { }
	// RVA: 0x32ab04c VA: 0x75958c304c
	private Void _ResetSlotLightTweens() { }
	// RVA: 0x32ab358 VA: 0x75958c3358
	private Boolean _NeedAdjustInputProgress(List`1 changeInfoList) { }
}
```