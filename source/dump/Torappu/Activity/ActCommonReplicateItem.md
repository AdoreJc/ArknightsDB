# ActCommonReplicateItem

**Namespace:** `Torappu.Activity`


## Fields

- `Transform _itemContainer1`

- `Transform _itemContainer2`

- `GameObject _lastIgnoreObj`

- `GameObject _itemNameGo`

- `Single _scaleFactor`

- `Boolean m_isInited`

- `UIItemCard m_itemCard1`

- `UIItemCard m_itemCard2`

- `Text m_text_name1`

- `UIAutoSlideRect m_slideName1`

- `Coroutine m_slideCoroutine`


## Methods

- `Void _InitIfNot()`

- `Void Render(ReplicateData, Boolean)`

- `IEnumerator _TryEnableTextSlide()`

- `Void _ClearCoroutine()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonReplicateItem : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer1; // 0x18
	private Transform _itemContainer2; // 0x20
	private GameObject _lastIgnoreObj; // 0x28
	private GameObject _itemNameGo; // 0x30
	private Single _scaleFactor; // 0x38
	private Boolean m_isInited; // 0x3c
	private UIItemCard m_itemCard1; // 0x40
	private UIItemCard m_itemCard2; // 0x48
	private Text m_text_name1; // 0x50
	private UIAutoSlideRect m_slideName1; // 0x58
	private Coroutine m_slideCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__TryEnableTextSlide; // 0x10
	private static DelegateBridge __Hotfix0__ClearCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_OnDisable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x30c79f0 VA: 0x75956df9f0
	private Void _InitIfNot() { }
	// RVA: 0x30c7ce8 VA: 0x75956dfce8
	public Void Render(ReplicateData data, Boolean isLast) { }
	// RVA: 0x30c7f94 VA: 0x75956dff94
	private IEnumerator _TryEnableTextSlide() { }
	// RVA: 0x30c7f00 VA: 0x75956dff00
	private Void _ClearCoroutine() { }
	// RVA: 0x30c8068 VA: 0x75956e0068
	private Void OnDisable() { }
	// RVA: 0x30c80d0 VA: 0x75956e00d0
	public Void .ctor() { }
}
```