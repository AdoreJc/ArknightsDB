# LMTGSResourceBar

**Namespace:** `Torappu.UI.Shop`


## Fields

- `SimpleLayoutContent _content`

- `SpriteHub m_priceTypeHub`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void UpdateValue()`

- `Void RenderEmpty()`

- `Void RenderAll()`

- `Void RenderRes(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class LMTGSResourceBar : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private SpriteHub m_priceTypeHub; // 0x20
	private Adapter m_adapter; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_UpdateValue; // 0x8
	private static DelegateBridge __Hotfix0_RenderEmpty; // 0x10
	private static DelegateBridge __Hotfix0_RenderAll; // 0x18
	private static DelegateBridge __Hotfix0_RenderRes; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x244b8d8 VA: 0x7594a638d8
	private Void _InitIfNot() { }
	// RVA: 0x244ba68 VA: 0x7594a63a68
	public Void UpdateValue() { }
	// RVA: 0x244bae8 VA: 0x7594a63ae8
	public Void RenderEmpty() { }
	// RVA: 0x244bbc0 VA: 0x7594a63bc0
	public Void RenderAll() { }
	// RVA: 0x244be04 VA: 0x7594a63e04
	public Void RenderRes(String lmtgsId) { }
	// RVA: 0x244c02c VA: 0x7594a6402c
	public Void .ctor() { }
}
```