# ShopGPTrackPointViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Boolean m_permitShow`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPTrackPointViewModel : ITrackPointModel, IHotfixable
{
	private Boolean m_permitShow; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfShowTrackPoint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isShow { get; }

	// RVA: 0x2448f0c VA: 0x7594a60f0c
	public Boolean get_isShow() { }
	// RVA: 0x2449024 VA: 0x7594a61024
	public Void UpdateState(Object permitShowBool) { }
	// RVA: 0x2448f8c VA: 0x7594a60f8c
	public static Boolean CheckIfShowTrackPoint() { }
	// RVA: 0x24490e8 VA: 0x7594a610e8
	public Void .ctor() { }
}
```