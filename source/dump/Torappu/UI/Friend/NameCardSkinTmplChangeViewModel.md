# NameCardSkinTmplChangeViewModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Int32 selectSkinTmpl`

- `String skinId`

- `String skinName`


## Methods

- `Boolean TryLoadSkinTmplData(String)`

- `Void _LoadCurSelectSkinTmpl(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinTmplChangeViewModel : IHotfixable
{
	public List`1 skinTmplItemModels; // 0x10
	public Int32 selectSkinTmpl; // 0x18
	public String skinId; // 0x20
	public String skinName; // 0x28
	private static DelegateBridge __Hotfix0_TryLoadSkinTmplData; // 0x0
	private static DelegateBridge __Hotfix0__LoadCurSelectSkinTmpl; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28bf02c VA: 0x7594ed702c
	public Boolean TryLoadSkinTmplData(String skinId) { }
	// RVA: 0x28bf224 VA: 0x7594ed7224
	private Void _LoadCurSelectSkinTmpl(String skinId) { }
	// RVA: 0x28bf310 VA: 0x7594ed7310
	public Void .ctor() { }
}
```