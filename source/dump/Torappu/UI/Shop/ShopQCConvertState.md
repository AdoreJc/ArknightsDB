# ShopQCConvertState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopQCConvertStateBean _stateBean`

- `ShopQCConvertItemContainer _view`

- `Text _textDesc`


## Methods

- `Void SendConvert()`

- `Void DecomposeGPItem(List`1)`

- `Void DecomposeClassicGPItem(List`1)`

- `Void <DecomposeGPItem>b__6_0(DecomposePotentialItemResponse)`

- `Void <DecomposeClassicGPItem>b__7_0(DecomposeClassicPotentialItemResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopQCConvertState : PopupFloatState
{
	private ShopQCConvertStateBean _stateBean; // 0x70
	private ShopQCConvertItemContainer _view; // 0x78
	private Text _textDesc; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_SendConvert; // 0x10
	private static DelegateBridge __Hotfix0_DecomposeGPItem; // 0x18
	private static DelegateBridge __Hotfix0_DecomposeClassicGPItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2473158 VA: 0x7594a8b158
	public override IStateBean GetCacheBean() { }
	// RVA: 0x24731c0 VA: 0x7594a8b1c0
	protected override Void OnEnter() { }
	// RVA: 0x24732cc VA: 0x7594a8b2cc
	public Void SendConvert() { }
	// RVA: 0x2473734 VA: 0x7594a8b734
	public Void DecomposeGPItem(List`1 convertList) { }
	// RVA: 0x24733ec VA: 0x7594a8b3ec
	public Void DecomposeClassicGPItem(List`1 convertList) { }
	// RVA: 0x2473a7c VA: 0x7594a8ba7c
	public Void .ctor() { }
	// RVA: 0x2473aec VA: 0x7594a8baec
	private Void <DecomposeGPItem>b__6_0(DecomposePotentialItemResponse response) { }
	// RVA: 0x2473bbc VA: 0x7594a8bbbc
	private Void <DecomposeClassicGPItem>b__7_0(DecomposeClassicPotentialItemResponse response) { }
	// RVA: 0x2473c8c VA: 0x7594a8bc8c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```