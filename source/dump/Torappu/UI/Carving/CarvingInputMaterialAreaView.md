# CarvingInputMaterialAreaView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingMaterialItem _materialItemPrefab`

- `Boolean m_isInited`


## Methods

- `Void Render(CarvingInputMaterialModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingInputMaterialAreaView : MonoBehaviour, IHotfixable
{
	private List`1 _materialSlots; // 0x18
	private CarvingMaterialItem _materialItemPrefab; // 0x20
	private Boolean m_isInited; // 0x28
	private List`1 m_items; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2dbf294 VA: 0x75953d7294
	public Void Render(CarvingInputMaterialModel model) { }
	// RVA: 0x2dbf448 VA: 0x75953d7448
	private Void _InitIfNot() { }
	// RVA: 0x2dbf654 VA: 0x75953d7654
	public Void .ctor() { }
}
```