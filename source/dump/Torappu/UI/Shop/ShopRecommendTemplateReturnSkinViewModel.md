# ShopRecommendTemplateReturnSkinViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Int64 m_showStartTs`

- `Int64 m_showEndTs`


## Properties

- `Int64 showStartTs`

- `Int64 showEndTs`


## Methods

- `Int64 get_showStartTs()`

- `Int64 get_showEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendTemplateReturnSkinViewModel : ShopRecommendTemplateViewModelBase
{
	protected Int64 m_showStartTs; // 0x18
	protected Int64 m_showEndTs; // 0x20
	private static DelegateBridge __Hotfix0_get_showStartTs; // 0x0
	private static DelegateBridge __Hotfix0_get_showEndTs; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Int64 showStartTs { get; }
	public Int64 showEndTs { get; }

	// RVA: 0x24614c0 VA: 0x7594a794c0
	public Int64 get_showStartTs() { }
	// RVA: 0x2461528 VA: 0x7594a79528
	public Int64 get_showEndTs() { }
	// RVA: 0x2461590 VA: 0x7594a79590
	public override Void LoadData(ShopRecommendItem recommendItem) { }
	// RVA: 0x2461644 VA: 0x7594a79644
	public Void .ctor() { }
}
```