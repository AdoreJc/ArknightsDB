# CrisisShopLeftCharView

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `UIAtlasImage _portraitImg`

- `Transform _itemContainer`

- `Single _scaleCount`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(CrisisShopWrapped)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopLeftCharView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _portraitImg; // 0x18
	private Transform _itemContainer; // 0x20
	private Single _scaleCount; // 0x28
	private UIItemCard m_itemCard; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c3b65c VA: 0x759525365c
	private Void _InitIfNot() { }
	// RVA: 0x2c39f2c VA: 0x7595251f2c
	public Void Render(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c3b81c VA: 0x759525381c
	public Void .ctor() { }
}
```