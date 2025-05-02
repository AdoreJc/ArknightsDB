# UIShopCashIconText

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _text`


## Methods

- `Void Init(Image)`

- `Void Render(String, Color)`

- `Void SetEnabled(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class UIShopCashIconText : MonoBehaviour, IHotfixable
{
	private Text _text; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_SetEnabled; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2476568 VA: 0x7594a8e568
	public Void Init(Image image) { }
	// RVA: 0x2476818 VA: 0x7594a8e818
	public Void Render(String currency, Color color) { }
	// RVA: 0x247690c VA: 0x7594a8e90c
	public Void SetEnabled(Boolean isEnabled) { }
	// RVA: 0x24769c0 VA: 0x7594a8e9c0
	public Void .ctor() { }
}
```