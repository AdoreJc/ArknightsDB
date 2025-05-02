# SwitchPlayHandler

**Namespace:** ` `


## Properties

- `Boolean isShow`

- `Boolean fastMode`

- `Single fixedDuration`


## Methods

- `Boolean get_isShow()`

- `Boolean get_fastMode()`

- `Single get_fixedDuration()`

- `Single GetProgressOfIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchPlayHandler : IHotfixable
{
	private readonly RoguelikeShopGoodsLoopAdapter m_closure; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_get_fastMode; // 0x8
	private static DelegateBridge __Hotfix0_get_fixedDuration; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0_GetProgressOfIndex; // 0x20

	public Boolean isShow { get; }
	public Boolean fastMode { get; }
	public Single fixedDuration { get; }

	// RVA: 0x2ae9c08 VA: 0x7595101c08
	public Boolean get_isShow() { }
	// RVA: 0x2ae9cc8 VA: 0x7595101cc8
	public Boolean get_fastMode() { }
	// RVA: 0x2ae9d88 VA: 0x7595101d88
	public Single get_fixedDuration() { }
	// RVA: 0x2ae9adc VA: 0x7595101adc
	public Void .ctor(RoguelikeShopGoodsLoopAdapter closure) { }
	// RVA: 0x2ae9e3c VA: 0x7595101e3c
	public Single GetProgressOfIndex(Int32 index) { }
}
```