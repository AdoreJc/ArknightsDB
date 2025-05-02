# ItemRepoItemDetailLeftView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Text _title`

- `Image _itemIcon`

- `Text _itemCount`

- `RectTransform _itemCountFrame`

- `GameObject _onTimePart`

- `Text _onTimeText`

- `Single _timePartBGMinWidth`

- `Single _timePartBGPaddingWidth`

- `RectTransform _timePartBGRectTrans`

- `RectTransform _timePartSuffixRectTrans`

- `RectTransform _timePartTimeContentRectTrans`


## Methods

- `Void Render(UIItemViewModel)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoItemDetailLeftView : MonoBehaviour, IHotfixable
{
	private Text _title; // 0x18
	private Image _itemIcon; // 0x20
	private Text _itemCount; // 0x28
	private RectTransform _itemCountFrame; // 0x30
	private GameObject _onTimePart; // 0x38
	private Text _onTimeText; // 0x40
	private Single _timePartBGMinWidth; // 0x48
	private Single _timePartBGPaddingWidth; // 0x4c
	private RectTransform _timePartBGRectTrans; // 0x50
	private RectTransform _timePartSuffixRectTrans; // 0x58
	private RectTransform _timePartTimeContentRectTrans; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d2a2b0 VA: 0x75953422b0
	public Void Render(UIItemViewModel itemViewModel) { }
	// RVA: 0x2d2fae8 VA: 0x7595347ae8
	private Void Update() { }
	// RVA: 0x2d2fc90 VA: 0x7595347c90
	public Void .ctor() { }
}
```