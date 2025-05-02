# Act3D0ReplicateItem

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Transform _itemContainer1`

- `Transform _itemContainer2`

- `GameObject _lastIgnoreObj`

- `Single _scaleFactor`

- `Boolean m_isInited`

- `UIItemCard m_itemCard1`

- `UIItemCard m_itemCard2`


## Methods

- `Void _InitIfNot()`

- `Void Render(ReplicateData, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0ReplicateItem : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer1; // 0x18
	private Transform _itemContainer2; // 0x20
	private GameObject _lastIgnoreObj; // 0x28
	private Single _scaleFactor; // 0x30
	private Boolean m_isInited; // 0x34
	private UIItemCard m_itemCard1; // 0x38
	private UIItemCard m_itemCard2; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3236464 VA: 0x759584e464
	private Void _InitIfNot() { }
	// RVA: 0x32366c8 VA: 0x759584e6c8
	public Void Render(ReplicateData data, Boolean isLast) { }
	// RVA: 0x3236824 VA: 0x759584e824
	public Void .ctor() { }
}
```