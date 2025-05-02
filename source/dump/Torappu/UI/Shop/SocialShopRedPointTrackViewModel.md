# SocialShopRedPointTrackViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Boolean m_isSocialShopActive`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class SocialShopRedPointTrackViewModel : ITrackPointModel, IHotfixable
{
	private Boolean m_isSocialShopActive; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfShowTrackPoint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x246f004 VA: 0x7594a87004
	public Boolean get_isShow() { }
	// RVA: 0x246f120 VA: 0x7594a87120
	public Void UpdateState(Object param) { }
	// RVA: 0x246f080 VA: 0x7594a87080
	public static Boolean CheckIfShowTrackPoint() { }
	// RVA: 0x246f1e0 VA: 0x7594a871e0
	public Void .ctor() { }
}
```